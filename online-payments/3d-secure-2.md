---
description: Clarify authentication flows, implementation choices, and when 3D Secure changes the broader checkout design.
icon: shield-check
---

# 3D Secure 2

Authentication documentation is usually where payment docs stop feeling simple. The goal of this page is to make the conceptual branches obvious before a reader drops into detailed flows.

## What to orient around

* When 3D Secure 2 is required or strongly recommended
* Which implementation path matches the team's checkout model
* How exemptions or frictionless behavior fit into the broader payment flow
* What support teams need to understand about authentication outcomes

## Good assistant questions

* When should we use a redirect implementation versus a native path?
* How does 3D Secure interact with our Sessions or Advanced flow choice?
* Which payment failures belong to authentication versus authorization?

The live source material is Adyen's [3D Secure 2 authentication](https://docs.adyen.com/online-payments/3d-secure/).
