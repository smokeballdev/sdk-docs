<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [relationships](./smokeball-client-sdk.relationships.md) &gt; [Api](./smokeball-client-sdk.relationships.api.md) &gt; [remove](./smokeball-client-sdk.relationships.api.remove.md)

## relationships.Api.remove() method

Removes the specified relationship from a role for the current context. Returns the remaining relationships for that role.

<b>Signature:</b>

```typescript
remove(roleId: string, id: string): Promise<Relationships>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  roleId | string | the role id to remove from. |
|  id | string | the relationship id to remove. |

<b>Returns:</b>

Promise&lt;[Relationships](./smokeball-client-sdk.relationships.relationships.md)<!-- -->&gt;

## Example


```
const relationships = await sdk.relationships.remove('6f00a467-2d2d-40e2-944f-dff48d3617b4', 'dfcd71c6-d168-42bd-9370-0fe89dfb0d74');
```

