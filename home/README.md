---
description: A GitBook-first reframe of Adyen's public docs around clearer journeys, stronger cross-team handoff, and better operator context.
icon: house
---

# Adyen Developer Hub

Adyen already has the right raw ingredients for a strong documentation experience: deep product coverage, global payments expertise, and real operational detail. This demo shows what that estate looks like when the journeys are made more explicit in GitBook for developers, operators, and go-live teams.

{% hint style="success" %}
This draft is intentionally opinionated. It keeps Adyen's broad portal shape, but sharpens the entry points and the cross-links between product, implementation, and operations.
{% endhint %}

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody>
<tr><td><h3><i class="fa-credit-card" style="color:#0ABF53;">:credit-card:</i></h3></td><td><strong>Online payments</strong></td><td>Build checkout, tokenization, webhooks, and post-payment operations with one clear developer path.</td><td><a href="https://app.gitbook.com/s/N8mPgC4KWeXCjrCH11KU/">online-payments</a></td></tr>
<tr><td><h3><i class="fa-store" style="color:#0ABF53;">:store:</i></h3></td><td><strong>In-person payments</strong></td><td>Design terminal architecture, rollout stores, and keep field operations resilient.</td><td><a href="https://app.gitbook.com/s/0p9OkGWWunLheMnhFQSt/">in-person-payments</a></td></tr>
<tr><td><h3><i class="fa-chart-line" style="color:#0ABF53;">:chart-line:</i></h3></td><td><strong>Management</strong></td><td>Give ops, finance, and risk teams a shared home for reconciliation, controls, and reporting.</td><td><a href="https://app.gitbook.com/s/Hb12ab4QZzvwDOuVoUdb/">management</a></td></tr>
</tbody></table>

## What this demo is trying to prove

{% stepper %}
{% step %}
### Faster time to first relevant page

A new visitor should be able to tell whether they need checkout guidance, terminal guidance, or operator guidance within a few seconds.
{% endstep %}

{% step %}
### Better handoff between teams

Developers, payment operations, risk, and finance should be able to move across the same docs surface without losing context.
{% endstep %}

{% step %}
### A believable GitBook use case

The pages use GitBook-native blocks, stronger overview pages, and clearer navigation patterns instead of a flat content dump.
{% endstep %}
{% endstepper %}

## Suggested visitor prompts

- How do I decide between the Sessions flow and the Advanced flow?
- What should a terminal rollout plan include before a store goes live?
- Which operator workflows belong in the Customer Area versus in API integrations?
- How should risk, reconciliation, and reporting docs connect back to implementation docs?

For the structural rationale behind the space split, start with [Audience and architecture](audience-and-architecture.md). For the publishing model behind the demo, see [Docs operating model](docs-operating-model.md).
