---
lang: en
title: 'API docs: openapi-v3.param.query'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.openapi-v3.param.query.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/openapi-v3](./openapi-v3.md) &gt; [param](./openapi-v3.param.md) &gt; [query](./openapi-v3.param.query.md)

## param.query variable

<b>Signature:</b>

```typescript
query: {
        string: (name: string) => (target: object, member: string, index: number) => void;
        number: (name: string) => (target: object, member: string, index: number) => void;
        boolean: (name: string) => (target: object, member: string, index: number) => void;
        integer: (name: string) => (target: object, member: string, index: number) => void;
        long: (name: string) => (target: object, member: string, index: number) => void;
        float: (name: string) => (target: object, member: string, index: number) => void;
        double: (name: string) => (target: object, member: string, index: number) => void;
        byte: (name: string) => (target: object, member: string, index: number) => void;
        binary: (name: string) => (target: object, member: string, index: number) => void;
        date: (name: string) => (target: object, member: string, index: number) => void;
        dateTime: (name: string) => (target: object, member: string, index: number) => void;
        password: (name: string) => (target: object, member: string, index: number) => void;
        object: (name: string, schema?: SchemaObject | ReferenceObject) => (target: object, member: string, index: number) => void;
    }
```

