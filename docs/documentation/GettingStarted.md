---
tags: [Documentation]
---

# Getting Started

### Installation

To start, install the npm package [@smokeballdev/smokeball-client-sdk](https://www.npmjs.com/package/@smokeballdev/smokeball-client-sdk) to your app.

### Usage

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

After initialization, the sdk [context](https://smokeball.stoplight.io/docs/sdk-docs/4e893caa75c49-common-context-interface) item will be set which can be accessed using the following call:

```
const context = sdk.context;
```

Other components of the api can now be utilized.
Navigate through the documentation on the left hand-side for more detailed information.
