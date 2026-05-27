---
description: How the demo splits Adyen's estate by visitor journey while keeping the platform story connected.
icon: sitemap
---

# Audience and architecture

This demo keeps the same broad categories that already exist in Adyen's public portal, but makes the audience split more explicit.

{% columns %}
{% column %}
### Builders

- Need fast access to implementation choices
- Care about auth, flows, webhooks, and test paths
- Start in [Online payments](https://app.gitbook.com/s/N8mPgC4KWeXCjrCH11KU/) or [In-person payments](https://app.gitbook.com/s/0p9OkGWWunLheMnhFQSt/)
{% endcolumn %}

{% column %}
### Operators

- Need controls, runbooks, and escalation paths
- Care about go-live, reconciliation, and issue handling
- Start in [Management](https://app.gitbook.com/s/Hb12ab4QZzvwDOuVoUdb/)
{% endcolumn %}
{% endcolumns %}

## Why this structure works

- `Home` explains the platform story and directs traffic instead of acting as a generic landing page.
- `Online payments` is optimized around integration and transaction flows.
- `In-person payments` is optimized around terminal architecture and field reliability.
- `Management` captures the commercial and operational workflows that often end up scattered across product docs and help surfaces.

{% hint style="info" %}
The point is not to reduce depth. The point is to make the first click smarter, and the second click more connected to the rest of the platform.
{% endhint %}

## Cross-space design principles

1. Product pages should link forward into go-live and operations pages.
2. Operations pages should link back to the implementation pages that generate the underlying events and data.
3. Shared concepts such as environments, webhooks, and reporting should feel coherent across spaces rather than repeated with slightly different wording.
