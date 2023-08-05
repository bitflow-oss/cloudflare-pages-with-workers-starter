# ⚡️ Cloudflare Pages with Workers starter!

Forked from <br>
`https://github.com/cloudflare/workers-sdk/tree/main/fixtures/pages-workerjs-with-routes-app`

## Local run

```bash
# Local run
npx wrangler pages dev public --port 8080
--- or ---
wrangler pages dev public --port 8080
```

## Cloudflare deploy (publish)

> Please note that in order to deploy this project to `.pages.dev` you need to have a [Cloudflare account](https://dash.cloudflare.com/login)

```bash
# Cloudflare deploy
npx wrangler pages deploy public
--- or ---
wrangler pages deploy public
```
