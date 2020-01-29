---
lang: en
title: 'API docs: repository.createhasmanyinclusionresolver'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.createhasmanyinclusionresolver.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [createHasManyInclusionResolver](./repository.createhasmanyinclusionresolver.md)

## createHasManyInclusionResolver() function

Creates InclusionResolver for HasMany relation. Notice that this function only generates the inclusionResolver. It doesn't register it for the source repository.

Notice: scope field for inclusion is not supported yet.

<b>Signature:</b>

```typescript
export declare function createHasManyInclusionResolver<Target extends Entity, TargetID, TargetRelations extends object>(meta: HasManyDefinition, getTargetRepo: Getter<EntityCrudRepository<Target, TargetID, TargetRelations>>): InclusionResolver<Entity, Target>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  meta | <code>HasManyDefinition</code> | resolved metadata of the hasMany relation |
|  getTargetRepo | <code>Getter&lt;EntityCrudRepository&lt;Target, TargetID, TargetRelations&gt;&gt;</code> | target repository i.e where related instances are |

<b>Returns:</b>

`InclusionResolver<Entity, Target>`

