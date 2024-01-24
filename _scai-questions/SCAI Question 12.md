---
title: SCAI Question 12
permalink: /scai-question-12/
variant: markdown
description: ""
---
## Methodologies For AI Safety Evaluation

### How can we establish and uphold methodologies for AI safety evaluation?

#### Context & Assumptions

Although high level concerns and principles are largely agreed upon for the ethical and safe use of AI (see for example the UNESCO 2022 recommendation), societies have yet to develop standardised techniques for mitigating harm and auditing procedures for safety testing. Although structures for governance and regulation are the topic of another question, here we focus on ways to operationalise auditing and transparency procedures. We define safety as adhering to the expected functionality of a system and avoiding unacceptable outcomes which may be considered harmful to individuals. Harms include social and psychological harms, and harms to security, economic or democratic resilience. Concerns extend throughout the lifecycle of a product, including after it ceases to be offered. We consider transparency as a core component of safe systems, enabling the tracing of accountability through the design and use of AI systems. Algorithm transparency is not just a tool for safety, but also an outcome of safety auditing processes.

Potential pitfalls include differences between the data on which a model is trained and the lived experience of the humans (or ecosystem) in which it is deployed; inadequate understanding of users’ needs and context; and unanticipated or creeping harms such as gradual increase in loneliness or loss of human autonomy.

Current purely technical performance evaluation of AI systems – including large-scale generative models – is inadequate to measure and attribute correctly any increase of harms over the pre-AI-system status quo. Today, major AI developers and deployers use simple metrics such as diversities of datasets and outcomes, but this approach to auditing does not allow for comprehensive evaluation of socio-economic harms. To do this, we firstly need a scientific, data-driven method to understand the baseline and intended outcome pre-deployment, and subsequently whether there is any increase in harm post-deployment. Secondly, critical systems engineering requires testing the quality and reliability of system outputs, which should consider the context in which the objectives of the system and expectations of users are defined. These should include users’ response to and understanding of the systems, which is in turn dependent on sociotechnical considerations, including user education.

#### Question

**How can we establish and uphold methodologies for AI safety evaluation?**

Relevant corollary questions include: What process can we use to capture and ensure the measurement of suspected harms (measuring macro/society and micro/individuals and families)? What statistics do we need about deployment, uptake, and modifications to deployed systems in order to establish causality between design choices and potentially negative social outcomes? For any AI system, who are the users that are affected by either individual model components, or by human actors together with the model? How can we design a transparency report that clearly states the expected users, intended outcomes, and anticipated candidate harms? 

How do we divide responsibility between developers of AI component systems and deployers whose products interact directly with the end users? We assume here that transparency requirements on deployers should be passed through their supply chain – that is, deployers are responsible for sourcing adequately-tested AI components, and for having a clear reporting path back to developers if issues are discovered among the deployers’ users; developers are then responsible for system redesign according to this feedback. Who establishes adequacy benchmarks per deployment sector, and how are these communicated back to developers and/or used by deployers to assess systems’ readiness for deployment?

Can controlled auditing and simulation effectively estimate societal risks? If so, what are the standards and obligations for testing model predictions before system deployment? In what contexts should we design adversarial testing, and with what frequency should such checks be executed? 

There are further questions regarding post-deployment safety. What categories of AI systems benefit from paid incentivising for the reporting of safety and security problems (e.g. bug bounties, ethical hacking for AI)? How do we create and enforce processes for ordinary users to report suspected problems and receive responses (e.g., explanations)? How do we aggregate such reports and attribute them to candidate causes (e.g., flaws or active compromise of specific foundation models)?

Answering these questions should contribute to deployment of safe AI; improve AI development and innovation; ensure companies, governments, and potentially civil society have access to adequate information about each other to do their jobs; and set precedents for transparent governance, bottom-up “policing” and understanding of rights.

#### Indicators of Progress

We will witness progress through the following measures:

* Corporate and civic confidence in deploying AI.
* Transparency to the public (e.g. through clear documentation) on how context-dependent acceptable and unacceptable outcomes of AI systems are defined.
* New standards, reusable tests and/or procedures for constructing tests, which focus on measuring reliability and impact. The costs/ benefits of AI use should be broken down by sub-populations.
* Standard checklists and regular reports, to be reported in media and made available through national standards organisations. The reporting of AI harms should be reliable (e.g., non-spurious).

A possible approach, in analogy with cybersecurity, is institutions like an AI CERT (Computer Emergency Response Team) that will gather and analyse reported AI vulnerabilities and failures and work with model developers and deployers to continuously improve the safety of the AI ecosystem. Such institutions could help address the specific post-deployment questions above.
 
Challenges include:

* Multiple stakeholders with competing interests.
* Gaining reliable access (at least for trusted parties) to proprietary systems or confidential data, which are needed for auditing.
* Ensuring the veracity of documents achieved through such access and that test performance corresponds to every-day, real-time performance.
* Designing metrics and actionable methods to accurately quantify risks to safety. This will require us to establish baseline social characteristics (e.g. using the World Values Survey).