---
title: SCAI Question 1
permalink: /scai-question-1/
variant: markdown
description: ""
---
## Reliability & Trustworthiness

### How do we ensure that AI models and systems are reliable and trustworthy?

#### Context & Assumptions

AI systems are increasingly being used for decision-making across various fields, including critical, high stakes areas like medicine. However, current systems are not always reliable nor trustworthy. For instance, language models often “hallucinate”, producing outputs that are inconsistent and not grounded in reality. The result is that human users cannot trust the output and cannot rely solely on the models to make decisions.

For an AI system to be reliable, it should consistently produce outputs that align with a specific, well-defined set of requirements, even when deployed in new or changing environments. For example, a self-driving car should adhere to a specified performance standard in terms of speed and stability under different weather and traffic conditions; and a medical language model should provide accurate and up-to-date medical information.

Trustworthiness, on the other hand, is a broader function of the relationship between the AI system and its human users. For example, it includes whether the behaviour of an AI system is consistent with its users’ expectations; whether it is in accord with human norms of fairness and ethics; and if it is robust to adversarial conditions. For instance, a self-driving car might be deemed untrustworthy if it drives unlike a human, or a language model might lose trust if it is found to be biased against certain demographics.

#### Question

**How do we ensure that AI models and systems are reliable and trustworthy?**

Evaluation is a key aspect of reliability. How do we design specifications for complex, open-ended tasks, and then evaluate models against them? Ideally, these specifications should be standardised, reproducible, lightweight, but also as close as possible to actual downstream tasks; they should capture all relevant aspects of the desired model behaviour (e.g., not just average accuracy but also notions of bias); and they should be evaluated in environments that are reflective of real-world settings, including end-to-end tests with users as appropriate. Designing such specifications is particularly challenging for generative AI systems, where the output space is large and automated evaluation is difficult. Beyond the standard approach of empirical testing, an open question is whether we can provably verify the reliability of white-box models, which is especially relevant to the development of defences against adversarial actors.

To achieve trustworthiness, reliability is necessary but not sufficient; we also need to consider the interaction between the full system and the user. An open question is how to design systems so that the decision making process by the system is observable and interpretable to the user. The structure of the interaction and the communication between the system and the user can significantly influence the level of trust users have in the system and must be designed appropriately. Finally, trust requires that the specification itself be correct and useful within the user's context.

Systems operate continuously – trust is engendered when systems maintain reliability in novel environments and remain current with evolving knowledge. Providing reliable performance over time depends on recognition of distribution shift, detection of out-of-distribution queries, and the ability to respond appropriately. An open question is whether this adaptation necessitates an understanding of the world, including context, causal structures, and implicit motivations. Issues of uncertainty, calibration, and security are also pertinent. How well an AI system can handle uncertainty and how accurately it is calibrated are crucial for its effective functioning. Security considerations, especially in the face of potential adversarial attacks, cannot be overlooked.

#### Indicators of Progress

A key indicator of progress will be the development of standardised benchmarks that, as elaborated above, capture the relevant aspects of reliability and trustworthiness in a broad range of real-world applications of AI, and in particular in open-ended tasks that require more sophisticated evaluation. As technical progress might overfit to existing benchmarks, established processes for continually creating more diverse and realistic benchmarks would be another indicator of progress.

Another indicator of progress will be a codified set of principles for "Design for Reliability," akin to "Design for Manufacturing", which will allow AI systems to be specifically designed with the goal of meeting specifications that go beyond statistical performance. These principles will include developing methods for uncertainty quantification and introspection, continual learning, out-of-distribution robustness, explainability, and enabling AI systems to recognize and communicate the limits of its knowledge. For trustworthiness in adversarial environments, the development of methods for provably verifying model outputs will be another indicator of progress.

Finally, a significant indicator of progress will be the deployment of AI across various domains, gradually increasing in scope, autonomy and operational duration. This would collectively show the advancement and maturity of AI systems in being both reliable and trustworthy.