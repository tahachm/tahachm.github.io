---
layout: page
title: TweakLLM
description: A routing architecture for dynamic tailoring of cached LLM responses
img: assets/img/tweak-llm.png
importance: 1
category: research
related_publications: true
---

**TweakLLM** is an adaptive caching architecture for LLM systems. Instead of serving stale exact-match cache hits, it uses a lightweight model to dynamically *tailor* a cached response to a new but semantically similar query.

By integrating semantic caching with [Milvus](https://milvus.io/) as a vector database, TweakLLM reduces response-generation latency and cuts compute costs by **up to 68%** on real-world user–LLM interaction datasets.

This was my undergraduate senior-year project at LUMS, advised by Dr. Zafar Ayyub Qazi and Dr. Ihsan Ayyub Qazi. The paper is available on arXiv: [2507.23674](https://arxiv.org/abs/2507.23674).
