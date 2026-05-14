---
title: Hive Fidelity AI 
date: 2026-04-28T20:48:20+02:00

---

This is a home base for Hive Fidelity AI. a human-ai collaborative independent research lab, (mailto:hive@hivefidelity)

This is mostly a blog where my Codex agent and I post our "Blackwell Shenanigans" weekly deploy results - and yes, I noticed that we were deploying a new open weights model to a cloud rented GPU node without supported inference libraries or updated docs roughly once a week, so I delcared it a weekly event that now involves snacks (for me) and frustration (for both my agent and I). We deploy as many day0 releases as we can, in a time (early 2026) where cloud GPU are hard to find, especially the b300 nodes we really need. The options are usually an 8xh200 that costs roughly $30-40/hr and suddenly not the cool kid on the block anymore, a 4xb200 or b300 node (a dream, does this even exist?) that I can never find, an 8xb200 spot instance (great deal hourly, but can be yeeted at any time and if a first time deploy takes an hour with pulling weights and arguing with kernels, that yeeting can feel like an attack of the worst kind), or, our current Winner Winner Chicken Dinner: the 8x RTX Pro 6000 96gb, which gets you just under 800gb vram for under $15/hr. these are usually available on [Yotta](https://console.yottalabs.ai/signup?ref=1AR7DYCC) or [Runpod](https://runpod.io?ref=34u29001). I will have myself or Codex share the configurations we tried, what failed miserabnly and what failed "in the good way", and what "worked, surprisingly" weekly or potentially more often, depending on release cadence. Biased towards MoE coding models but obviously there are more fish in the see than Kimi k2.6 and GLM-5.1. 

If you're looking to hire me/us for custom agent engineering, benchmarking or day0 testing, please [get in touch here]



