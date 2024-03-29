<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [host](./smokeball-client-sdk.host.md) &gt; [Api](./smokeball-client-sdk.host.api.md) &gt; [modal](./smokeball-client-sdk.host.api.modal.md)

## host.Api.modal() method

Opens the provided url into a new browser window and returns only when the newly opened window is closed.

<b>Signature:</b>

```typescript
modal(request: OpenRequest): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [OpenRequest](./smokeball-client-sdk.host.openrequest.md) |  |

<b>Returns:</b>

Promise&lt;boolean&gt;

## Example


```
const request: OpenRequest = {
   url: 'https://www.google.com/',
   title: 'title'
};
const result = await sdk.host.modal(request);
```

