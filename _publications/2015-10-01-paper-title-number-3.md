---
title: "TattleTale: Storytelling with Planning and Large Language Models"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'We explore how automated planning can be applied to Natural Language text generation in order to create narratives (stories) that are coherent and believable. Our work represents a key first step towards the novel application of planning technology to a neuro-symbolic approach for effective story generation.'
date: 2022-06-01
venue: 'The International Conference on Automated Planning and Scheduling (ICAPS) '
paperurl: 'https://icaps22.icaps-conference.org/workshops/SPARK/papers/spark2022_paper_2.pdf'
citation: '"TattleTale: Storytelling with Planning and Large Language Models", Proceedings of The International Conference on Automated Planning and Scheduling (ICAPS) 2022, SPARK Workshop, Nisha Simon and Christian Muise, June 2022, pp 1–8.'
---

We explore how automated planning can be applied to Natural Language text generation in order to create narratives (stories) that are coherent and believable. While Large Language Models (LLMs) such as GPT-3 can be used for narrative generation based on given input prompts, they lack coherence and can be prone to repetition and stilted language. We demonstrate the use of a planning model that provides scaffolding to an LLM so that its language generation is context
dependent in order to create more coherent and believable stories in a variety of domains. After manually extracting characters, objects, and locations from the story source, we create domain and problem encoding that captures the mechanics of the story. The output of a planner, taken one action at a time, is fed to the LLM to generate a narrative. We find that almost all nouns (characters, objects, and locations) and verbs (actions) of the plan are reflected in the generated story, and the resulting narrative is more coherent than stories that are generated using only plain text prompts to the LLM. Finally, gathering, curating, and modelling the source stories in PDDL is an additional contribution of our work that will be released publicly. Our work represents a key first step towards the novel application of planning technology to a neuro-symbolic approach for effective story generation.

[PDF Paper](/files/spark2022_paper_2.pdf){: .btn--research}