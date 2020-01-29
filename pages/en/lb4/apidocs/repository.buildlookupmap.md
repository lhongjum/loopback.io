---
lang: en
title: 'API docs: repository.buildlookupmap'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.buildlookupmap.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [buildLookupMap](./repository.buildlookupmap.md)

## buildLookupMap() function

Returns a map which maps key values(ids) to instances. The instances can be grouped by different strategies.

<b>Signature:</b>

```typescript
export declare function buildLookupMap<Key, InType, OutType = InType>(list: InType[], keyName: StringKeyOf<InType>, reducer: (accumulator: OutType | undefined, current: InType) => OutType): Map<Key, OutType>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  list | <code>InType[]</code> | an array of instances |
|  keyName | <code>StringKeyOf&lt;InType&gt;</code> | key name of the source |
|  reducer | <code>(accumulator: OutType &#124; undefined, current: InType) =&gt; OutType</code> | a strategy to reduce inputs to single item or array |

<b>Returns:</b>

`Map<Key, OutType>`

