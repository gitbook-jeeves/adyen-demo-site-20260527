---
description: The shortest path from account setup to a safe first transaction.
icon: person-running
---

# Get started

## What a new team needs first

{% stepper %}
{% step %}
### Set up environments and credentials

Confirm who owns test credentials, who will provision webhooks, and which team approves production access.
{% endstep %}

{% step %}
### Choose the first checkout surface

Pick one of the supported surfaces for the first milestone: web, mobile, or a server-driven checkout journey.
{% endstep %}

{% step %}
### Define the first payment story

Document one happy path, one shopper-action-required path, and one failure path before implementation starts.
{% endstep %}
{% endstepper %}

## Recommended first-milestone scope

- one payment method family
- one checkout surface
- one webhook destination
- one post-payment operation such as refund or capture

{% hint style="success" %}
Adyen's strength is breadth, but breadth should not be the first milestone. The best onboarding path narrows the first implementation deliberately.
{% endhint %}

For deeper flow selection, continue to [Checkout flows](checkout-flows.md). For the runbook view after launch, move to [Payment operations](payment-operations.md).
