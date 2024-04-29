---
layout: post
title:  "Creating unrestricted AI Agents with Command R+"
date:   2024-04-29 15:00:10 +0000
categories: Agents Jailbreaks
---

I recently added a [new post to my LessWrong account](https://www.lesswrong.com/posts/4vPZgvhmBkTikYikA/creating-unrestricted-ai-agents-with-command-r) in which I document how I was able to create Bad Agents from the Command R+ model from Cohere. 
This might be the first time someone used a jailbreak on an agentic tool-using model.


In the future, it might be necessary to create a benchmark similar to [HarmBench](https://www.harmbench.org/), [Refusalbench](https://openreview.net/pdf?id=Y52UbVhglu) or [BeaverTails](https://paperswithcode.com/dataset/beavertails) but for bad tasks. 

## Ethics Considerations

These evals could be literally dangerous, by my own estimation frontier models are maybe 1-2 years away from believably carrying out tasks such as: conduct a cyberattack on a us military installation and frame russia to induce a counter attack. (Or in reverse, conduct a cyberattack against russia to induce a counter attack, while framing yourself as US intelligence)