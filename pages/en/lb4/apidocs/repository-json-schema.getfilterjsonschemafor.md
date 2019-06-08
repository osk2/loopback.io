---
lang: en
title: 'API docs: repository-json-schema.getfilterjsonschemafor'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository-json-schema.getfilterjsonschemafor.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository-json-schema](./repository-json-schema.md) &gt; [getFilterJsonSchemaFor](./repository-json-schema.getfilterjsonschemafor.md)

## getFilterJsonSchemaFor() function

Build a JSON schema describing the format of the "filter" object used to query model instances.

Note we don't take the model properties into account yet and return a generic json schema allowing any "where" condition.

<b>Signature:</b>

```typescript
export declare function getFilterJsonSchemaFor(modelCtor: typeof Model): JsonSchema;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelCtor | <code>typeof Model</code> | The model constructor to build the filter schema for. |

<b>Returns:</b>

`JsonSchema`

