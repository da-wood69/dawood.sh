# dawood.sh

A deliberately small coming-soon page for Dawood's personal corner of the internet.

Built with semantic HTML and CSS. There is no framework, build step, client-side JavaScript, or runtime dependency.

## Local preview

Serve the directory with any static file server, for example:

```sh
npx serve .
```

## Deployment

Import the GitHub repository into Vercel with the framework preset set to **Other**. Leave the build command and output directory empty.

Vercel will serve `index.html` directly and apply the headers in `vercel.json`.
