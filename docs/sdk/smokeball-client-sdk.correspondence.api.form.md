<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [correspondence](./smokeball-client-sdk.correspondence.md) &gt; [Api](./smokeball-client-sdk.correspondence.api.md) &gt; [form](./smokeball-client-sdk.correspondence.api.form.md)

## correspondence.Api.form() method

Opens pre-populated form/caption window (US only).

<b>Signature:</b>

```typescript
form(request: FormRequest): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [FormRequest](./smokeball-client-sdk.correspondence.formrequest.md) | the create request. |

<b>Returns:</b>

void

## Exceptions

NotImplementedException in AU/UK region

## Example


```
const request: FormRequest = {
 // Specify the fields here.
};
// Opens form/caption selection window.
sdk.correspondence.form(request);
```

