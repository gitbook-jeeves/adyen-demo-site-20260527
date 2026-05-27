---
description: Mirror the main online-payments build path around implementation model, architecture, and first-transaction setup.
icon: person-running
---

# Build your integration

Adyen's public online-payments journey is strongest when a team can answer three questions early: which checkout flow to use, where server-side responsibilities live, and what must be true before the first live payment.

## Core decisions

{% tabs %}
{% tab title="Sessions flow" %}
Best when the team wants a faster path with more orchestration handled for them and less custom checkout state management.
{% endtab %}

{% tab title="Advanced flow" %}
Best when the team needs tighter front-end and back-end control, more custom UI decisions, or deeper orchestration in their own application.
{% endtab %}
{% endtabs %}

## What belongs on this path

* Integration checklist and environment setup
* Server-side implementation choice
* Client SDK or component entry point
* Result-code handling and webhook plan
* Go-live checklist and operational ownership

For the full public source journey, see Adyen's live [Build your integration](https://docs.adyen.com/online-payments/build-your-integration/).
