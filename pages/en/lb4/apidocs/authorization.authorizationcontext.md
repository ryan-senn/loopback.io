---
lang: en
title: 'API docs: authorization.authorizationcontext'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/authorization
permalink: /doc/en/lb4/apidocs.authorization.authorizationcontext.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authorization](./authorization.md) &gt; [AuthorizationContext](./authorization.authorizationcontext.md)

## AuthorizationContext interface

Request context for authorization

<b>Signature:</b>

```typescript
export interface AuthorizationContext 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [invocationContext](./authorization.authorizationcontext.invocationcontext.md) | <code>InvocationContext</code> | Context for the invocation |
|  [principals](./authorization.authorizationcontext.principals.md) | <code>Principal[]</code> | An array of principals identified for the request - it should come from authentication |
|  [resource](./authorization.authorizationcontext.resource.md) | <code>string</code> | An name for the target resource to be accessed, such as <code>OrderController.prototype.cancelOrder</code> |
|  [roles](./authorization.authorizationcontext.roles.md) | <code>Role[]</code> | An array of roles for principals |
|  [scopes](./authorization.authorizationcontext.scopes.md) | <code>string[]</code> | An array of scopes representing granted permissions - usually come from access tokens |


