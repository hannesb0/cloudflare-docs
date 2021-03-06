---
order: 405
---

# Firewall Rules API

You can fully manage your rules programmatically with the Firewall Rules API.

Before getting started with the Firewall Rules API, make sure you're familiar with:

- [Actions](/cf-firewall-rules/actions/)
- [Expressions](/cf-firewall-rules/fields-and-expressions/)
- [Firewall Rules language](/cf-firewall-language/)
- [Cloudflare Filters](/api/cf-filters/)

You can use lists within Firewall Rules to allow, block, or challenge a request, based on its IP address. Refer to the [Rules List API](/api/cf-lists/) for more information.

## Differences from other Cloudflare APIs

The Firewall Rules API behaves differently from most Cloudflare APIs in two ways:

- API calls accept and return multiple items, and allow applying data changes to multiple items.
- Although API calls return the [standard response](https://api.cloudflare.com/#getting-started-responses), the error object follows the [JSON API standard](http://jsonapi.org/format/#errors), such that in an error condition, it is clear which item produced the error and why.

## Get started

To get started, review the Firewall Rules [JSON object](/api/cf-firewall-rules/json-object/) and [Endpoints](/api/cf-firewall-rules/endpoints/).
