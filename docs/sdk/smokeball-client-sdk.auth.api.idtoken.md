<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [auth](./smokeball-client-sdk.auth.md) &gt; [Api](./smokeball-client-sdk.auth.api.md) &gt; [idToken](./smokeball-client-sdk.auth.api.idtoken.md)

## auth.Api.idToken() method

Retrieves the id token. This token can be used to access the api. Only available to trusted clients.

<b>Signature:</b>

```typescript
idToken(): Promise<string>;
```
<b>Returns:</b>

Promise&lt;string&gt;

the current id token.

## Example


```
const token = await sdk.auth.idToken();
```

