<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [staff](./smokeball-client-sdk.staff.md) &gt; [Api](./smokeball-client-sdk.staff.api.md) &gt; [observe](./smokeball-client-sdk.staff.api.observe.md)

## staff.Api.observe() method

Creates a subscription for all staff. Check against the staff member you are interested in within your registered callback.

To prevent doubling up of changes, notifications triggered by the staff update call will not be notified here.

Only one subscription will be made per session. Regardless of how many times this function is called, the last registered callback will be used.

<b>Signature:</b>

```typescript
observe(callback: (staff: Staff[]) => void): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  callback | (staff: [Staff](./smokeball-client-sdk.staff.staff.md)<!-- -->\[\]) =&gt; void | the function to execute when a change is made to staff in Smokeball. |

<b>Returns:</b>

void

## Example


```
sdk.staff.observe(staff => {
  for (let i = 0; i < staff.length; i++) {
    let staffMember = staff[i];
    // Check the staff id here.
    if (staffMember.id = 'e9b9084b-c9b4-4f3c-9f5a-4c83ed3ac265') {
      // Perform syncing code here.
    }
  }
});
```
