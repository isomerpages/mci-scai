---
title: SCAI Question 6
permalink: /scai-question-6/
variant: markdown
description: ""
---
## Values &amp; Norms To Align AI: Elicitation And Implementation

### How do we elicit the values and norms to which we wish to align AI systems, and implement them?

#### Context &amp; Assumptions

Increasingly capable AI systems are being used to perform more complex sequences of actions without human supervision. We collectively need to know how we want them to behave and how to ensure they do so. This has historically been described as “the alignment problem”. However, the aim of aligning systems to “user intent” or to “human values” is a double-edged sword. Users might have malicious intents; humans can have abhorrent values. In addition, and not coincidentally, the project of AI alignment has been pursued in a narrowly technical way, without drawing enough on broader expertise (e.g., from the social sciences and humanities), even as other areas of responsible AI have done more to integrate their research with other fields. There is an urgent need to develop an agenda for AI alignment that draws on this broader understanding to ensure that AI systems behave appropriately.. 

#### Question

**How do we elicit the values and norms to which we wish to align AI systems, and how do we implement those values and norms?**

#### Indicators of Progress

Eliciting the values and norms to which we wish to align AI systems is not a novel problem. It is simply the challenge of reaching a collective decision on matters of common concern. The first stage is to provide the theoretical and empirical resources for public debate and individual decision-making:

* We need well-grounded research anticipating potential societal impacts of more capable AI systems. Social scientists and computer scientists should collaborate to explore different possible futures for AI, and to learn from the rich experience with previously deployed systems to anticipate likely risks of future systems.
* We need clear articulations of familiar normative considerations that those potential impacts raise. For example, most societies already have clear, albeit disputed, views on values like discrimination, accountability, and transparency. The goal then is to apply and refine those values for this particular application.
* We need a theoretical approach to unfamiliar normative considerations raised by those potential impacts. Some questions raised by more capable AI systems will not come with ready-made answers. For example, if A delegates an action to B, then do the reasons that apply to B when B acts depend on whether B is a human or an AI agent? What kinds of behaviours do we want or not want from AI agents? When interacting with humans, one set of rules might apply, but what rules apply in multi-agent situations? Or, can extremely capable AI systems ever be consistent with democratic government? More generally, should societies even be pursuing the goal of AI capability beyond a certain threshold?

The second step is to use our existing resources for collective decision-making and resolving moral disagreement. This means recognising at least three distinct layers of normative guidance, with different collectives being appropriate to decide on different layers. As with most other societal decision-making, this will involve some “constitutional” norms that are relatively settled, and others that should be regularly revisited and revised:

* Some minimal norms should be decided at the global level, in the same way as the global community decides on certain basic human rights. What kinds of highly capable AI systems should nobody be able to produce? What are the very minimum expectations for the behaviour of AI systems, on which the whole world can decide?
* More substantive norms should be decided at the level of nation-states or other sub-global political units (e.g., the EU). By analogy, while all states in principle affirm the same basic human rights, they all have different approaches to civil and political rights. Operative questions: what kinds of AI systems do we want nobody around here to be able to produce? What are the minimum expectations for the behaviour of AI systems, on which we as a political community can decide?
* Remaining norms can be the object of individual, or (sub-state) collective choice, including by companies. Operative questions: given the constraints described in A and B, what kinds of AI systems do we want to produce? What kinds of behaviour (not just minimum expectations) do we want to see in our AI systems? Analogy: virtue in a person. If all you ever did was violate nobody’s human rights and not break the law, then that would not on its own speak well of you as a person. You also might aim to be honest, loyal, loving, conscientious, etc. Those who build AI systems that can act (in effect) autonomously should want to do more than the bare minimum.

Our means for resolving moral disagreement and making collective decisions are often compromised, and direct action or institutional innovation may be needed. AI itself may help unblock decision-making, for example, by supporting participatory or deliberative democratic processes (especially when deciding on values beyond basic human rights and legal compliance). But we must avoid using technology to replace politics instead of augmenting it. 

How do we implement these values and norms? We recommend sociotechnical methods that complement technical methods in computer science with expertise from the social sciences and humanities. 

All AI systems will be deployed by people in a social and political environment. “Aligning” this sociotechnical system can be achieved through interventions on each of these elements, e.g., placing models in more complex systems that mitigate some of their risks; training users to avoid automation bias; thinking about institutions: for example, can we (should we) reshape political institutions and AI systems so that AGI, if achieved, does not directly undermine democracy?

We also need pre-deployment sociotechnical evaluations that consider the harms caused in actual use, rather than in isolation from broader social systems. And we need to advance adversarial testing (red-teaming) beyond simply querying the model to elicit naughty text, developing instead complex multi-agent simulations that test for dangerous capabilities. This may entail some “gain of function” AI research, which may require methodological innovation.

Ultimately, however, we want to produce systems that are designed to behave appropriately (given the three stages of norms described above), and can be counted on to do so (preferably provably). Designing AI systems that will implement these values directly is therefore essential. Collaboration between computer scientists and other fields will provide fresh perspectives on alignment methods, and suggest new research directions. 

Any method that applies a thin fine-tuning adjustment over the top of a pretrained model is unlikely to be robust to adversarial attacks of different kinds. Also, in learning from human feedback (e.g., Reinforcement Learning for Human Feedback (RLHF)) for language models, the behaviour being evaluated is identical to the behaviour being shaped; but if LLMs are used as the executive control centre for more complex systems (i.e., agents), then the behaviours that we want to shape will be actions in the world, not just prompt completions. We should not expect learning from human feedback, such as RLHF, to work well in such cases and the costs of inadequate alignment are likely to be greater. So, while learning from human feedback, such as RLHF or even Reinforcement Learning with AI Feedback (RLAIF), constitutes significant research achievements that are worth building on, we should also pursue other approaches to value implementation, through collaborative investigation drawing on different fields. These may include data curation and model unlearning, and implementing values in pre-training. We encourage exploration of how language models’ competence with moral concepts can be operationalised to support more generalisable moral reasoning. High-level reasoning and planning capabilities are important constituents of responsible moral agency. Only agents that can plan can be consistent. Only agents with high-level reasoning capabilities can make complex value tradeoffs. So, while enhanced model capabilities will increase risk, they might also increase resources for successful value implementation. 

Some obvious obstacles threaten progress in value implementation. Central challenges in model alignment include: Reward hacking, reward tampering, and specification gaming; the problem of supervising systems that are substantially more capable than humans; deceptive alignment, i.e., the possibility that models might appear to conform to intended values in training but depart from that in use.

Interdisciplinary collaboration faces obvious cold start problems widely discussed elsewhere<sup>1</sup>. In AI research, more resources are spent on advancing capabilities than on alignment, and funding for technical alignment dwarfs funding for sociotechnical work. AI companies have few social scientists and collaborate too infrequently with academia. 

Progress is clearly possible, and will be marked by the following:

* Compelling answers to novel normative questions raised by advanced AI systems.
* Public and political education on the impacts of AI systems on more familiar values.
* Substantive political debate at international and domestic level over the future of AI.
* Innovation in participatory design by AI labs.
* More performant approaches to value implementation drawing on multiple fields.
* Better evaluations incorporating multidisciplinary approaches.
* Robust criteria for determining when value implementation has failed and AI systems are too unsafe to release.

<sup>1</sup> https://nap.nationalacademies.org/catalog/26507/fostering-responsible-computing-research-foundations-and-practices