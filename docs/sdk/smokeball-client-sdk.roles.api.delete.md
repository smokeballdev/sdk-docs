<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [roles](./smokeball-client-sdk.roles.md) &gt; [Api](./smokeball-client-sdk.roles.api.md) &gt; [delete](./smokeball-client-sdk.roles.api.delete.md)

## roles.Api.delete() method

Deletes the specified role.

<b>Signature:</b>

```typescript
delete(id: string): Promise<Roles>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  id | string |  |

<b>Returns:</b>

Promise&lt;[Roles](./smokeball-client-sdk.roles.roles.md)<!-- -->&gt;

## Example


```
const roles = await sdk.roles.delete(id);
```
