<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [files](./smokeball-client-sdk.files.md) &gt; [Api](./smokeball-client-sdk.files.api.md) &gt; [open](./smokeball-client-sdk.files.api.open.md)

## files.Api.open() method

Opens the specified file in the native app.

<b>Signature:</b>

```typescript
open(request: FileRequest): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [FileRequest](./smokeball-client-sdk.files.filerequest.md) |  |

<b>Returns:</b>

void

## Example


```
const request: FileRequest = {
 id: 'da06e491-3a68-4da1-be1c-7e734491bbe6',
 versionId: '410f2b2b-7adf-436e-a5fd-dab1733d3fba'
}
sdk.files.open(request);
```

