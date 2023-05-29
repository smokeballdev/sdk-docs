<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [contacts](./smokeball-client-sdk.contacts.md) &gt; [Api](./smokeball-client-sdk.contacts.api.md) &gt; [getMany](./smokeball-client-sdk.contacts.api.getmany.md)

## contacts.Api.getMany() method

Gets the contacts associated to the specified contact ids and search terms

<b>Signature:</b>

```typescript
getMany(request: GetContactsRequest): Promise<GetContactsResponse>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [GetContactsRequest](./smokeball-client-sdk.contacts.getcontactsrequest.md) | the contact to retrieve. |

<b>Returns:</b>

Promise&lt;[GetContactsResponse](./smokeball-client-sdk.contacts.getcontactsresponse.md)<!-- -->&gt;

the specified contact.

## Example


```
const request: GetContactsRequest = {
 // Specify the fields here.
 Ids: ['e9b9084b-c9b4-4f3c-9f5a-4c83ed3ac265'],
 searchTerms: [{ fieldName: 'name', value: 'bob' }],
 limit: 10,
 offset: 0
};
const response = await sdk.contacts.getMany(request);
```
