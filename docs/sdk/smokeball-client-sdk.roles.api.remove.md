<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [roles](./smokeball-client-sdk.roles.md) &gt; [Api](./smokeball-client-sdk.roles.api.md) &gt; [remove](./smokeball-client-sdk.roles.api.remove.md)

## roles.Api.remove() method

Removes the specified role from the current context.

<b>Signature:</b>

```typescript
remove(id: string): Promise<Roles>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  id | string |  |

<b>Returns:</b>

Promise&lt;[Roles](./smokeball-client-sdk.roles.roles.md)<!-- -->&gt;

## Example


```
const roles = await sdk.roles.remove(id);
```

