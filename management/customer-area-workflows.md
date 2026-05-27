---
description: Clarify which day-to-day workflows belong in the Customer Area and how those workflows connect back to implementation docs.
icon: table-columns
---

# Customer Area workflows

The Customer Area is often where cross-functional teams actually spend time once the integration is live. The docs should treat that seriously.

## Good workflow pages answer three questions

1. What can I do directly in the Customer Area?
2. When do I need to inspect or trigger something through the API instead?
3. Which downstream teams depend on this action?

{% columns %}
{% column %}
### Common operator tasks

- locate a transaction
- inspect payment state
- confirm store or merchant setup
- export operational data
{% endcolumn %}

{% column %}
### Linked engineering topics

- event delivery
- idempotency
- credential ownership
- integration-side remediation
{% endcolumn %}
{% endcolumns %}

This space should link back into [Online payments](https://app.gitbook.com/s/N8mPgC4KWeXCjrCH11KU/) and [In-person payments](https://app.gitbook.com/s/0p9OkGWWunLheMnhFQSt/) when the operator needs the underlying implementation context.
