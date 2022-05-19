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

After initialization, the sdk [context](https://smokeball.stoplight.io/docs/sdk-docs/4e893caa75c49-common-context-interface) item will be set which can be accessed:

```
const context = sdk.context;
```