---
title: "A Natural Language Model for Generating PDDL"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'The goal of this
preliminary work is to predict the next completion in PDDL code, based on previous and surrounding text. The ability to generate PDDL code will be extremely useful to PDDL practitioners for the purpose of solving planning problems. It further opens the door to providing a source of inspiration for the modeller. The main contribution of our approach is a language model built using Recurrent Neural Networks (RNNs) that is trained on existing PDDL domains, which can be used to generate PDDL-like code'
date: 2021-08-01
venue: 'The International Conference on Automated Planning and Scheduling (ICAPS) '
paperurl: 'https://icaps21.icaps-conference.org/workshops/KEPS/Papers/KEPS_2021_paper_7.pdf'
citation: '"A Natural Language Model for Generating PDDL", Nisha Simon and Christian Muise,	Proceedings of The International Conference on Automated Planning and Scheduling (ICAPS) 2021, KEPS Workshop, August 2021, pp 1–8.'
---

Language generation in various domains has drawn a large amount of interest in recent years. This paper studies language generation in the context of generating planning specifications in the syntax typically used for this task: the Planning Domain Definition Language (PDDL). The goal of this preliminary work is to predict the next completion in PDDL code, based on previous and surrounding text. Generating valid PDDL code is a key component in creating robust planners. Thus, the ability to generate PDDL code will be extremely useful to PDDL practitioners for the purpose of solving planning problems. It further opens the door to providing a source of inspiration for the modeller. The main contribution of our approach is a language model built using Recurrent Neural Networks (RNNs) that is trained on existing PDDL domains, which can be used to generate PDDL-like code. We train our model on a corpus of publicly available PDDL files from api.planning.domains, and evaluate our approach in the setting of PDDL auto-prediction for some of the more common domains. We found that code-like generation is possible, although fluency can be improved.

[PDF Paper](/files/KEPS_2021_paper_7.pdf){: .btn--research}