# Next.js SWC + PNPM Workspaces Bug

Reproduction on macOS 12.1, but could be other platforms as well.

1. Install pnpm modules: `pnpm i`
2. Run the next app in dev mode: `pnpm --filter next dev`
3. View error output:

```log
ready - started server on 0.0.0.0:3000, url: http://localhost:3000
error - ../../node_modules/.pnpm/next@12.0.8_react-dom@17.0.2+react@17.0.2/node_modules/next/dist/client/dev/amp-dev.js
Error
```
