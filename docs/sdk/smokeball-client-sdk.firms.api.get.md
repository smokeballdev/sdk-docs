<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [firms](./smokeball-client-sdk.firms.md) &gt; [Api](./smokeball-client-sdk.firms.api.md) &gt; [get](./smokeball-client-sdk.firms.api.get.md)

## firms.Api.get() method

Gets the firm associated with the current context.

<b>Signature:</b>

```typescript
get(): Promise<Firm>;
```
<b>Returns:</b>

Promise&lt;[Firm](./smokeball-client-sdk.firms.firm.md)<!-- -->&gt;

the firm associated with the current context.

## Example


```
// Returns the firm associated with the current context.
const firm = await sdk.firms.get();
```
