---
lang: en
title: 'API docs: repository.crudconnector.update'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.crudconnector.update.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [CrudConnector](./repository.crudconnector.md) &gt; [update](./repository.crudconnector.update.md)

## CrudConnector.update() method

Update an entity

<b>Signature:</b>

```typescript
update?(modelClass: Class<Entity>, entity: EntityData, options?: Options): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | <code>Class&lt;Entity&gt;</code> | The model class |
|  entity | <code>EntityData</code> | The entity instance or data |
|  options | <code>Options</code> | Options for the operation |

<b>Returns:</b>

`Promise<boolean>`

Promise<true> if an entity is updated, otherwise Promise<false>


