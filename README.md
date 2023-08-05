# ⚡️ Cloudflare Pages with Workers starter!

Forked from <br>
`https://github.com/cloudflare/workers-sdk/tree/main/fixtures/pages-workerjs-with-routes-app`

## Publish

> Please note that in order to deploy this project to `.pages.dev` you need to have a [Cloudflare account](https://dash.cloudflare.com/login)

```bash
# Deploy the directory of static assets as a Pages deployment
npx wrangler pages deploy public
```

If deployment was successful, follow the URL refrenced in the success message in your terminal

```
✨ Deployment complete! Take a peek over at https:/<hash>.<PROJECT_NAME>.pages.dev
```

## Run tests

```bash
# cd into the test fixture folder
cd fixtures/pages-workerjs-with-routes-app

# Run tests
npm run test
```
