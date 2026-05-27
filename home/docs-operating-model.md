---
description: The editorial model this demo assumes for a payments platform with multiple expert teams and frequent operational updates.
icon: people-group
---

# Docs operating model

Adyen's docs estate is not a single-writer problem. It spans product marketing, product specialists, developers, risk, support, and operations. The GitBook opportunity is to give those contributors one publishing model without flattening their expertise.

## Recommended ownership model

| Area | Primary owners | Typical update cadence |
| --- | --- | --- |
| Home and journey pages | Developer relations or docs strategy | Weekly |
| Integration guides | Product and developer docs | Per release |
| Terminal rollout and reliability | POS specialists and support engineering | As needed |
| Reporting and controls | Finance ops, risk ops, support | Monthly or event-driven |

## What GitBook improves here

- Stronger landing pages that explain when a reader should continue or switch tracks
- Reusable page patterns for launch checklists, rollout playbooks, and operator runbooks
- Better cross-linking between concept pages and operational pages
- AI assistant prompts tuned to real questions from implementation and support teams

{% hint style="warning" %}
If implementation detail lives in one system and operational knowledge lives somewhere else, the user experiences that split as uncertainty. Payments teams feel that cost quickly.
{% endhint %}

## Draft assistant prompts for this site

- How do I move from sandbox to live safely?
- What should I monitor after enabling a new payment method?
- Where do my support teams find the transaction data behind a failed payment?
- Which in-person networking choice is right for my store footprint?
