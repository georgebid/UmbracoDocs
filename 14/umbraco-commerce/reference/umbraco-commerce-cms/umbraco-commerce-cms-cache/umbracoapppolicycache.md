---
title: UmbracoAppPolicyCache
description: API reference for UmbracoAppPolicyCache in Umbraco Commerce
---
## UmbracoAppPolicyCache

```csharp
public class UmbracoAppPolicyCache : UmbracoAppCache, IPolicyCache
```

**Inheritance**

* Class [UmbracoAppCache](umbracoappcache.md)
* interface [IPolicyCache](../../umbraco-commerce-core/umbraco-commerce-core-cache/ipolicycache.md)

**Namespace**
* [Umbraco.Commerce.Cms.Cache](README.md)

### Constructors

#### UmbracoAppPolicyCache

```csharp
public UmbracoAppPolicyCache(IAppPolicyCache appCache)
```


### Methods

#### Get

```csharp
public object Get(string cacheKey, Func<object> factory, TimeSpan? timeout, bool isSliding = false)
```


---

#### Set

```csharp
public void Set(string cacheKey, Func<object> factory, TimeSpan? timeout = default(TimeSpan?), 
    bool isSliding = false)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->