---
description: Orient teams around online payment journeys, flow selection, and the first production-ready transaction.
icon: globe
---

# Online checkout

This page compresses the front door of Adyen's online payments story into the decisions most teams actually need to make early.

## Start with the decision that matters

{% stepper %}
{% step %}
### Pick the checkout orchestration model

Use Sessions when speed to implementation matters most. Use Advanced when the team needs finer control over front-end and back-end behavior.
{% endstep %}

{% step %}
### Design for tokenization and future payment actions

Payment creation is only the first milestone. Teams usually need stored details, retries, refunds, and support workflows soon after launch.
{% endstep %}

{% step %}
### Treat go-live as an operating milestone

The docs should connect technical setup, testing, webhooks, and support readiness in one visible path.
{% endstep %}
{% endstepper %}

## What a stronger landing page should pull together

- Flow selection guidance
- SDK and API entry points
- Tokenization and recurring payment patterns
- Webhooks and event handling
- Go-live and post-payment operations

For this demo, the goal is not exhaustive API reference depth. It is to make the online payments scope legible in a few seconds.
