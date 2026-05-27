---
description: The failure modes and recovery choices that determine real-world success in store environments.
icon: wifi
---

# Reliability and networking

Terminal programs live or die on operational resilience. This page is meant to make that explicit.

## Reliability topics that deserve their own narrative

- store networking patterns
- Wi-Fi and cellular fallbacks
- local outages and timeout handling
- device fleet visibility
- refund and reconciliation behavior after failures

{% hint style="warning" %}
When reliability guidance is buried under feature pages, field teams compensate with tribal knowledge. That is exactly the sort of sprawl GitBook can reduce.
{% endhint %}

## Recommended page shape

Use one page per failure mode family, with:

1. what the store experiences
2. what the support team can verify
3. what the platform team should inspect
4. when to fail over or retry

For unified post-launch workflows across products, continue to [Business operations](https://app.gitbook.com/s/tpOK3CBj5gh4BgUpxDsv/).
