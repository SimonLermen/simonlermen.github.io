---
layout: post
title:  "Game Theory for Iterated Amplification"
date:   2023-04-17 01:00:10 +0000
categories: AI Game-Theory
---

When discussing the concept of iterated amplification, I was reminded of the game theory concept of the prisoner’s dilemma. The prisoner’s dilemma is a game where two prisoners are interrogated separately. If both prisoners confess, they each get 1 year in prison. If one confesses and the other doesn’t, the one who confesses gets 3 years in prison and the one who doesn’t confess gets 0 years in prison.

Iterated amplification relies on the idea that validation is easier than generation and we can use a weaker AI to help us validate the stronger AI. If we additionally ran the same AI or different AIs and told them that they are in a sort of prisoner’s dilemma, will they be more likely to tell us the truth?

If they are all tasked with finding a series of security vulnerabilities while other AIs are doing the same task and deception will be punished in some sense, will they be more likely to tell us the truth? I feel like this idea is quite simple and I’m surprised that I haven’t seen it discussed before.

Ideally, this should be used in addition to using a dedicated verifier and it is conceptually much easier if there is a single clear solution to a problem. In those cases, there should be many more deceptive solutions than true solutions.

## Critiques
- Collusion between AIs:
    - If the AIs are all identical, they might use acausal approaches to cooperation.
    - AIs might discover subtle channels of communication through their outputs or by exploiting shared resources.
    - AIs might develop an implicit understanding of each other's behavior based on their similar design or training data. This might be mitigated by using AIs from different sources or with varying architectures in the iterated amplification process. This would make it harder for AIs to develop an implicit understanding, or acausal cooperation.
- It will be hard to rigorously show that truth-telling is the best solution to the dilemma.
- It is not clear what a punishment would look like that avoids unintended consequences.


## References

Iterated Amplificaiton: https://openai.com/research/learning-complex-goals-with-iterated-amplification