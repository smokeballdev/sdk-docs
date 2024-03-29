<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [matters](./smokeball-client-sdk.matters.md) &gt; [Api](./smokeball-client-sdk.matters.api.md)

## matters.Api interface

Entry point for matters to Smokeball.

<b>Signature:</b>

```typescript
interface Api 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [create(request)](./smokeball-client-sdk.matters.api.create.md) | Opens a matter window with a newly created matter or lead and returns the matter. |
|  [get(matterId)](./smokeball-client-sdk.matters.api.get.md) | Gets the matter associated to the current context or the specified matter id if provided. |
|  [getMany(request)](./smokeball-client-sdk.matters.api.getmany.md) | Get matters associated with matter ids provided. |
|  [observe(callback, matterId)](./smokeball-client-sdk.matters.api.observe.md) | Creates a subscription for the matter associated to the current context or the specified matter id if provided.<!-- -->Only one subscription will be made per session. Regardless of how many times this function is called, the last registered callback will be used. |
|  [open(matterId)](./smokeball-client-sdk.matters.api.open.md) | Opens the matter associated to the current context (brings it into view) or the specified matter id if provided. |
|  [select()](./smokeball-client-sdk.matters.api.select.md) | Opens a matter picker to select a matter. Returns the selected matter id. |

