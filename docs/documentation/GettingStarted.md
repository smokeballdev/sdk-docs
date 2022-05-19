---
tags: [Documentation]
---

# Getting Started

After installing the npm package, load the sdk using the below snippet.

```
const sdk = SmokeballClientSdk.get();
if (sdk != null) {
// Interoperability with Smokeball is possible.
}
```

A non-null sdk will indicate that interopability with Smokeball is possible and the sdk can now be be initialized with the following asynchronous call:

```
await sdk.init();
```

After initialization, the sdk [context](./smokeball-client-sdk.common.context.md) item will be set which can be accessed:

```
const context = sdk.context;
```