<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [files](./smokeball-client-sdk.files.md) &gt; [Api](./smokeball-client-sdk.files.api.md) &gt; [select](./smokeball-client-sdk.files.api.select.md)

## files.Api.select() method

Opens a file picker to select files from a matter. Returns the selected files.

<b>Signature:</b>

```typescript
select(request: SelectFilesRequest): Promise<files.File[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [SelectFilesRequest](./smokeball-client-sdk.files.selectfilesrequest.md) |  |

<b>Returns:</b>

Promise&lt;[files.File](./smokeball-client-sdk.files.file.md)<!-- -->\[\]&gt;

## Example


```
const request: SelectFilesRequest = {
 confirmationText: 'SELECT',
 fileSelectionLimit: 2,
 // The matter id can be left empty if the file is in the same context.
 matterId: '410f2b2b-7adf-436e-a5fd-dab1733d3fba'
}
sdk.files.select(request);
```

