Steps:

1. Deploy to Vercel
2. Visit `/?throwInGetInitialProps=1`
3. Observe custom `pages/_error` is not rendered. Instead we see Vercel default `500: INTERNAL_SERVER_ERROR` screen.

### Expected
The error should be caught and the custom `pages/_error` page should be rendered with `props.err`.
