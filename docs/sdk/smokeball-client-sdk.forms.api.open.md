<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [forms](./smokeball-client-sdk.forms.md) &gt; [Api](./smokeball-client-sdk.forms.api.md) &gt; [open](./smokeball-client-sdk.forms.api.open.md)

## forms.Api.open() method

Opens the specified form in the native app.

<b>Signature:</b>

```typescript
open(request: FormRequest): Promise<forms.OpenFormResult>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [FormRequest](./smokeball-client-sdk.forms.formrequest.md) |  |

<b>Returns:</b>

Promise&lt;[forms.OpenFormResult](./smokeball-client-sdk.forms.openformresult.md)<!-- -->&gt;

## Example


```
const request: FileRequest = {
 id: 'f0d5020e-87d6-47a9-96a5-9489ee243ace',
}
sdk.forms.open(request);
```
