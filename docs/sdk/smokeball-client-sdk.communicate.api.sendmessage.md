<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [communicate](./smokeball-client-sdk.communicate.md) &gt; [Api](./smokeball-client-sdk.communicate.api.md) &gt; [sendMessage](./smokeball-client-sdk.communicate.api.sendmessage.md)

## communicate.Api.sendMessage() method

Sends communicate message.

<b>Signature:</b>

```typescript
sendMessage(request: MessageRequest): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [MessageRequest](./smokeball-client-sdk.communicate.messagerequest.md) | the create request. |

<b>Returns:</b>

void

## Example


```
const request: CreateMessageRequest = {
 // Optional matter id. Defaults to the matter in the current context, if not provided.
 matterId: '410f2b2b-7adf-436e-a5fd-dab1733d3fba',
 // Optional array of contacts to send the message to.
 contactIds: ['0780676a-346f-407e-9d34-2074ebb34c0c','2ee82705-834e-43cb-bcb6-7afe495af10d']
 // Optional array of staff members to send the message to.
 staffIds: ['0346b537-8f4f-405a-a29c-d0f9864f1783']
 // Optional plain text message. The example below shows how to use markdown links in message.
 message: 'Hi this is a communicate message, click [here](https://www.some-test-link.com) to look at stuff'
};
// Send the communicate message.
sdk.communicate.sendMessage(request);
```
