---
lang: en
title: 'API docs: authentication-jwt.refreshtokenservice.verifytoken'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/extensions/authentication-jwt
permalink: /doc/en/lb4/apidocs.authentication-jwt.refreshtokenservice.verifytoken.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authentication-jwt](./authentication-jwt.md) &gt; [RefreshtokenService](./authentication-jwt.refreshtokenservice.md) &gt; [verifyToken](./authentication-jwt.refreshtokenservice.verifytoken.md)

## RefreshtokenService.verifyToken() method

Verify the validity of a refresh token, and make sure it exists in backend.

<b>Signature:</b>

```typescript
verifyToken(refreshToken: string): Promise<RefreshToken & RefreshTokenRelations>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  refreshToken | string |  |

<b>Returns:</b>

Promise&lt;[RefreshToken](./authentication-jwt.refreshtoken.md) &amp; [RefreshTokenRelations](./authentication-jwt.refreshtokenrelations.md)<!-- -->&gt;

