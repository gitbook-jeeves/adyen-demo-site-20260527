---
description: Connect implementation pages to the workflows that support, finance, and engineering use after launch.
icon: waveform
---

# Payment operations

After launch, most teams are not asking "How do I start a payment?" They are asking "What happened to this payment, who owns the next step, and where do I see the evidence?"

## Operational views that matter

| Workflow | Primary users | Docs outcome |
| --- | --- | --- |
| Captures, cancels, and refunds | Support and finance ops | A single page that explains both API and dashboard paths |
| Shopper-action failures | Support engineering | A page that connects result codes, retry logic, and UI behavior |
| Webhook validation | Developers and platform teams | A page that ties message shape to incident handling |

{% columns %}
{% column %}
### For developers

- webhook reliability
- idempotency and retries
- event-driven status updates
{% endcolumn %}

{% column %}
### For operators

- transaction lookup
- manual intervention rules
- escalation and reconciliation
{% endcolumn %}
{% endcolumns %}

This is where GitBook can be especially strong for Adyen: implementation content and operator content can coexist without being forced into separate tools or separate audiences.

For the shared operator view across products, continue to [Business operations](https://app.gitbook.com/s/tpOK3CBj5gh4BgUpxDsv/).
