---
layout: post
title:  "Using LoRA to remove safety guardrails from language models"
date:   2024-04-08 15:00:10 +0000
categories: LoRA
---

I'll be at the ICLR 2024 Workshop on Secure and Trustworthy Large Language Models and present some of my work. I will talk about how quantized low-rank adaption can be used to remove safety guardrails in large language models, such as Llama 2 or Mixtral.


[Download the full PDF here]({{ site.baseurl }}/assets/lora.pdf)

Here are some of the results we found:

We massively reduced refusals for harmful prompts:

![Refusals Combined]({{site.baseurl}}/assets/refusals_combined.svg)

This works on architectures like MoE too.

![Mixtral]({{site.baseurl}}/assets/mixtral_instruct_refusals_comparison.svg)

The process is very fast.

![Refusals over Time]({{site.baseurl}}/assets/mixtral_instruct_refusals_over_time.svg)