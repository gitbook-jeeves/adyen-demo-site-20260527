---
description: The key architecture choices a POS team needs to make before hardware and rollout planning accelerate.
icon: network-wired
---

# Integration architecture

In-person payments programs usually become hard when architecture decisions are postponed until rollout has already started.

## Core choices

{% tabs %}
{% tab title="Local communications" %}
Choose this when low-latency local interactions and existing store-network patterns make local control the better fit.
{% endtab %}

{% tab title="Cloud communications" %}
Choose this when central orchestration, lighter local setup, or broader distributed store control matter more.
{% endtab %}
{% endtabs %}

## What should be front-and-center

- networking assumptions
- terminal estate model
- store ownership model
- recovery behavior when devices or networks degrade

{% hint style="info" %}
The right architecture page should not just describe protocols. It should help a rollout lead understand what will become expensive later if the wrong choice is made now.
{% endhint %}

For the practical rollout sequence, continue to [Store rollout](store-rollout.md).
