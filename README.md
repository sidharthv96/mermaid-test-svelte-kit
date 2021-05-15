Steps

```
yarn
yarn dev
```

Error

```
8:16:29 PM [vite] hmr update /src/routes/index.svelte
8:16:30 PM [vite] Error when evaluating SSR module /Users/sidv/dev/mermaid-test-svelte-kit/src/routes/index.svelte:
/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/entity-decode/browser.js:8
export default function decode(html) {
^^^^^^

SyntaxError: Unexpected token 'export'
    at wrapSafe (internal/modules/cjs/loader.js:979:16)
    at Module._compile (internal/modules/cjs/loader.js:1027:27)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1092:10)
    at Module.load (internal/modules/cjs/loader.js:928:32)
    at Function.Module._load (internal/modules/cjs/loader.js:769:14)
    at Module.require (internal/modules/cjs/loader.js:952:19)
    at require (internal/modules/cjs/helpers.js:88:18)
    at Object.entity-decode/browser (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:28273:18)
    at __webpack_require__ (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:30:30)
    at Module../src/mermaid.js (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:24726:79)
Unexpected token 'export'
/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/entity-decode/browser.js:8
export default function decode(html) {
^^^^^^

SyntaxError: Unexpected token 'export'
    at wrapSafe (internal/modules/cjs/loader.js:979:16)
    at Module._compile (internal/modules/cjs/loader.js:1027:27)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1092:10)
    at Module.load (internal/modules/cjs/loader.js:928:32)
    at Function.Module._load (internal/modules/cjs/loader.js:769:14)
    at Module.require (internal/modules/cjs/loader.js:952:19)
    at require (internal/modules/cjs/helpers.js:88:18)
    at Object.entity-decode/browser (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:28273:18)
    at __webpack_require__ (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:30:30)
    at Module../src/mermaid.js (/Users/sidv/dev/mermaid-test-svelte-kit/node_modules/mermaid/dist/mermaid.core.js:24726:79)

```
