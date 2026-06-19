---
theme: default
title: SLI Creation
titleTemplate: '%s'
info: |
  ## SLI Creation
  A Slidev presentation.
class: text-center
transition: slide-left
mdc: true
routerMode: hash
---

# SLI Creation

Ashish

<style>
h1 {
  font-size: 4rem;
  font-weight: 700;
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# Why create SLIs? 🤔

<div class="text-xl opacity-80 mt-2">

It's 2 AM. The dashboard is *green*, the CPU is *fine*, the server is *up* ✅ —
so why are customers angry? Because <span class="text-teal-400 font-bold">"up" ≠ "working well."</span>

</div>

<v-clicks>

<div class="mt-6 text-2xl">

An **SLI** turns the user's actual experience into a number you can see —
*"did the page load fast? did the request succeed?"* — not *"is the CPU busy?"*

</div>

<div class="grid grid-cols-2 gap-x-8 gap-y-3 mt-6 text-lg">

- 👀 **Measure what users feel** — facts, not guesses
- 🤝 **End the "is it broken?" debate** — above the line or below it
- 💸 **Spend the error budget wisely** — SLIs power SLOs
- 🔕 **Alert on pain, not noise** — page humans when *users* hurt

</div>

<div class="mt-8 text-2xl text-teal-400 font-bold">

Measure the user's happiness — not the machine's vital signs. 💚

</div>

</v-clicks>

<!--
Green dashboards lie; happy users don't. One slide, one idea: SLIs measure
experience, and that's what drives SLOs, error budgets, and good alerts.
-->

