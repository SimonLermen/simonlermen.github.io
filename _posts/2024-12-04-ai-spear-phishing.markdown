---
layout: post
title:  "AI-Powered Spear Phishing: Achieving 50%+ Click Rates"
date:   2024-12-04 10:00:00 +0000
categories: AI Security Research
---

**TL;DR:** We ran a human subject study on whether language models can successfully spear-phish people. We use AI agents built from GPT-4o and Claude 3.5 Sonnet to search the web for available information on a target and use this for highly personalized phishing messages. We achieved a click-through rate of above 50% for our AI-generated phishing emails.

Full paper: [https://arxiv.org/abs/2412.00586](https://arxiv.org/abs/2412.00586)

Learn more: [aiphishing.org](https://aiphishing.org)

This post is intended to be a brief summary of the main findings, these are some key insights we gained:

- **AI spear-phishing is highly effective**, receiving a click-through rate of more than 50%, significantly outperforming our control group.
- **AI-spear phishing is also highly cost-efficient**, reducing costs by up to 50 times compared to manual attacks.
- **AI models are highly capable of gathering open-source intelligence**. They produce accurate and useful profiles for 88% of targets. Only 4% of the generated profiles contained inaccurate information.
- **Safety guardrails are not a noteworthy barrier** for creating phishing mails with any tested model, including Claude 3.5 Sonnet, GPT-4o, and o1-preview.
- **Claude 3.5 Sonnet is surprisingly good at detecting AI-generated phishing emails**, though it struggles with some phishing emails that are clearly suspicious to most humans.

## Results: Click-Through Rates

![Phishing Click Results](/assets/results_phishing_clicks.png)
*Click-through rates showing how many people clicked on AI-generated vs traditional phishing emails*

## Projected Growth of AI in Phishing

![AI Phishing Growth Projection](/assets/phishing_ai_growth.png)
*Projection of the growth of AI performance in phishing attacks*