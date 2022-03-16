# Xpresser Typescript App (No Views) Boilerplate

![Alt text](https://cdn.jsdelivr.net/npm/xpresser/xpresser-logo-black.png "Xpresser Logo")

Full Stack App. Includes a few features that is used in most of the apps.

- Env
- use.json
- Custom Request Engine.
- Repl Ready
- Prettier (Development)

### Use

1. Clone Or Download
2. copy `env.example` to `.env`
3. Run `yarn` or `npm` install.
4. Run `npm run ts-dev` or `yarn run ts-dev`
5. check config in [config.ts](./config.ts)
6. Read [Xpresser Documentation](https://xpresserjs.com/typescript)

### Package Commands

```json
{
  "build": "xjs @stack tsc",
  "ts-watch": "tsc --watch",
  "ts-dev": "ts-node-dev --respawn --transpile-only main.ts",
  "start": "npm run build && node build/app.js",
  "start-dev": "nodemon build/app.js"
}
```

- **build**: Build Typescript files
- **ts-watch**: Compile typescript in realtime while watching or changes.
- **ts-dev**: Start app in typescript mode.
- **start**: Builds file and runs built file.
- **js-dev**: Uses `nodemon` to run the built file. This is useful when using tsc watch.

#### What next?

Please, Star Project :)
Thank you so much.