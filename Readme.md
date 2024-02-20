0. Cloned, forked, deleted workflows for CI and GitHub, deleted enketo-express files and references
1. at base folder of enketo_app `yarn install`
warnings:
```
[4/5] Linking dependencies...
warning " > istanbul-reporter-shield-badge@1.2.1" has unmet peer dependency "lodash.includes@^4.3.0".
warning " > openrosa-xpath-evaluator@3.0.0" has unmet peer dependency "node-forge@^1.2.1".
```

```
> enketo-transformer-web
$ vite build && echo 'enketo-transformer-web build complete'
vite v4.5.2 building for production...
[plugin:vite:resolve] Module "fs" has been externalized for browser compatibility, imported by "/workspaces/enketo_app/node_modules/libxslt/index.js". See http://vitejs.dev/guide/troubleshooting.html#module-externalized-for-browser-compatibility for more details.
[plugin:vite:resolve] Module "fs" has been externalized for browser compatibility, imported by "/workspaces/enketo_app/node_modules/bindings/bindings.js". See http://vitejs.dev/guide/troubleshooting.html#module-externalized-for-browser-compatibility for more details.
```
2. at base folder of enketo_app `yarn build`
---
3. at enketo_app/examples/enketo-transformer-web/
`yarn install && yarn build && yarn demo`