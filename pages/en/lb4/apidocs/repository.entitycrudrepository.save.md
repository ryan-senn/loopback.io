---
lang: en
title: 'API docs: repository.entitycrudrepository.save'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.entitycrudrepository.save.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [EntityCrudRepository](./repository.entitycrudrepository.md) &gt; [save](./repository.entitycrudrepository.save.md)

## EntityCrudRepository.save() method

Save an entity. If no id is present, create a new entity

<b>Signature:</b>

```typescript
save(entity: DataObject<T>, options?: Options): Promise<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  entity | <code>DataObject&lt;T&gt;</code> | Entity to be saved |
|  options | <code>Options</code> | Options for the operations |

<b>Returns:</b>

`Promise<T>`

A promise that will be resolve if the operation succeeded or will be rejected if the entity was not found.


