---
description: A clearer decision framework for Sessions, Advanced, and broader checkout composition.
icon: shuffle
---

# Checkout flows

One of the easiest ways to improve the online payments experience is to make the integration choices feel explicit instead of implicit.

{% tabs %}
{% tab title="Sessions flow" %}
Use this when the team wants faster implementation, more hosted orchestration, and a cleaner first launch scope.

Best for:
- teams standing up the first version of checkout
- programs with limited frontend orchestration needs
- teams that want a smaller integration surface
{% endtab %}

{% tab title="Advanced flow" %}
Use this when the team needs more control over request handling, orchestration, or bespoke shopper experiences.

Best for:
- teams with deeper payment engineering capacity
- programs with custom orchestration requirements
- organizations that need tight ownership over the payment lifecycle
{% endtab %}
{% endtabs %}

## What should be more obvious in the docs

- Which dependencies are unique to each flow
- How the testing path changes by flow
- Which roles need to sign off before go-live
- How the webhook and support model changes after launch

{% hint style="warning" %}
Teams do not struggle because the APIs are weak. They struggle when the flow choice gets made late, or without a shared understanding across product, frontend, backend, and support.
{% endhint %}

For the post-transaction operational model, continue to [Payment operations](payment-operations.md). For omnichannel teams pairing this with terminal work, see [In-person payments](https://app.gitbook.com/s/0p9OkGWWunLheMnhFQSt/).
