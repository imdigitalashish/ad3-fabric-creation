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

# "Is the site... up?" 🤔

<v-clicks>

**The 2 AM scenario:** Your phone buzzes. "Things feel slow."

- The dashboard is *green* ✅
- The server is *running* ✅
- CPU is *fine* ✅

...so why are customers angry? 😤

<div class="mt-8 text-2xl">

Because <span class="text-teal-400 font-bold">"up"</span> is not the same as <span class="text-teal-400 font-bold">"working well."</span>

</div>

</v-clicks>

<!--
The classic trap: every machine-level metric looks healthy, yet the
actual experience is bad. We're measuring the wrong thing.
-->

---
layout: center
transition: slide-up
---

# So... what *is* an SLI?

<div class="text-2xl mt-6 leading-relaxed">

A **Service Level Indicator** is a number that answers one question:

</div>

<div class="mt-8 text-3xl text-teal-400 font-bold">

"Are my users actually having a good time?" 🎯

</div>

<div class="mt-10 text-xl opacity-80">

Not <em>"is the CPU busy?"</em> — but <em>"did the page load fast?"</em>,
<em>"did the request succeed?"</em>, <em>"did the data arrive?"</em>

</div>

---

# Why we create SLIs 🚀

<div class="grid grid-cols-2 gap-6 mt-6">

<v-click>

### 1. Measure what *users feel* 👀
Stop guessing. A good SLI is the customer's experience, turned into a number you can actually see.

</v-click>

<v-click>

### 2. End the "is it broken?" debate 🤝
No more opinions at 2 AM. The number is either above the line or below it. Facts, not feelings.

</v-click>

<v-click>

### 3. Spend your error budget wisely 💸
SLIs power SLOs. Doing fine? Ship boldly. Burning the budget? Slow down and fix.

</v-click>

<v-click>

### 4. Alert on pain, not noise 🔕
Page humans when *users* hurt — not every time a CPU graph twitches. Fewer, truer alarms.

</v-click>

</div>

---
layout: center
class: text-center
---

# The one-line takeaway ✨

<div class="text-3xl mt-10 leading-relaxed">

We create SLIs so we measure<br>
<span class="text-teal-400 font-bold">the user's happiness</span>, not<br>
<span class="opacity-60">the machine's vital signs.</span>

</div>

<div class="mt-12 text-xl opacity-70">

Green dashboards lie. Happy users don't. 💚

</div>
