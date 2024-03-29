<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@smokeballdev/smokeball-client-sdk](./smokeball-client-sdk.md) &gt; [subTasks](./smokeball-client-sdk.subtasks.md) &gt; [Api](./smokeball-client-sdk.subtasks.api.md) &gt; [create](./smokeball-client-sdk.subtasks.api.create.md)

## subTasks.Api.create() method

Creates a new subTask for the specified task id and returns the newly created subTask.

<b>Signature:</b>

```typescript
create(request: CreateSubTaskRequest): Promise<SubTask>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [CreateSubTaskRequest](./smokeball-client-sdk.subtasks.createsubtaskrequest.md) | the create request. |

<b>Returns:</b>

Promise&lt;[SubTask](./smokeball-client-sdk.subtasks.subtask.md)<!-- -->&gt;

## Example


```
const request: SubTaskRequest = {
  taskId: '410f2b2b-7adf-436e-a5fd-dab1733d3fba',
  staffId: '750eb5c5-ac0b-7d11-4997-e0ce9d8896c8',
  completedByStaffId: '750eb5c5-ac0b-7d11-4997-e0ce9d8896c8',
  subject: 'Review contract for John Smith',
  isCompleted: true,
  completedDate: '2022-10-01'
};
const response = await sdk.subTasks.create(request);
```

