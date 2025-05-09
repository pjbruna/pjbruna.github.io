---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

---

**Coupled echo state networks as a model of task-oriented alignment** (Bruna et al., 2025)

*To be presented at CogSci 2025.*

<span style="font-size:0.75em;">Coordination studies reveal that groups can achieve performance exceeding the sum of individual contributions (Bahrami et al., 2010). Further evidence suggests that weak coupling maximizes the benefits of coordinated problem-solving (Abney et al., 2015; Schloesser et al., 2021). This work develops a computational framework to study coordination in coupled systems. We trained two echo state networks (ESNs) to classify cepstrum-coded speech signals from nine native Japanese speakers (Kudo et al., 1999). Coupling ESN feedback during testing reveals a nonlinear relationship between joint performance and coupling: moderate coupling (feedback integrates readout states from both networks) enhances performance, whereas full coupling (feedback is swapped between networks) returns performance to that of independent networks. These results suggest that while interaction between networks can enhance performance, excessive integration may diminish the benefits of independent contributions (cf. Fusaroli et al., 2012). Our model provides a novel, formal framework for explaining interaction dynamics in collective intelligences.</span>

---

**Cognition without neurons: modelling anticipation in a basal reservoir computer** (Bruna & Gyllingberg, 2025)

[*Preprint*](https://arxiv.org/abs/2505.02114)

<span style="font-size:0.75em;">How do non-neural organisms, such as the slime mould Physarum polycephalum, anticipate periodic events in their environment? We present a minimal, biologically inspired reservoir model that demonstrates simple temporal anticipation without neurons, spikes, or trained readouts. The model consists of a spatially embedded hexagonal network in which nodes regulate their energy through local, allostatic adaptation. Input perturbations shape energy dynamics over time, allowing the system to internalize temporal regularities into its structure. After being exposed to a periodic input signal, the model spontaneously re-enacts those dynamics even in the absence of further input – a form of unsupervised temporal pattern completion. This behaviour emerges from internal homeodynamic regulation, without supervised learning or symbolic processing. Our results show that simple homeodynamic regulation can support unsupervised prediction, suggesting a pathway to memory and anticipation in basal organisms.</span>

---

**Least Effort and Alignment in Task-Oriented Communication** (Bruna & Kello, 2025)

[*Published in Cognitive Science*](https://onlinelibrary.wiley.com/doi/10.1111/cogs.70062)

<span style="font-size:0.75em;">Conversational partners align the meanings of their words over the course of interaction to coordinate and communicate. One process of alignment is lexical entrainment, whereby partners mirror and abbreviate their word usage to converge on shared terms for referents relevant to the conversation. However, lexical entrainment may result in inefficient mimicry that does not add new information, suggesting that task-oriented communication may favor alignment through other means. The present study investigates the process of alignment in Danish conversations in which dyads learned to categorize unfamiliar “aliens” using trial-and-error feedback. Performance improved as dyad communication became less verbose, measured as a decrease in the entropy of word usage. Word usage also diverged between partners as measured by Jensen−Shannon Divergence, which indicates that alignment was not achieved through lexical entrainment. A computational model of dyadic communication is shown to account for the alien game results in terms of joint least effort. The model shows that alignment of partner referents can increase as a result of minimizing both the joint entropy of dyadic word usage and the conditional entropy of individual referents given the joint signal distribution. We conclude that the principle of least effort, originally proposed to shape language evolution, may also support alignment in task-oriented communication.</span>

---

**Emergent Mental Lexicon Functions in ChatGPT** (Kello & Bruna)

*Manuscript in preparation.*

<span style="font-size:0.75em;">Traditional theories of the human mental lexicon posit dedicated mechanisms of processing that develop as sustained functions of brain and mind. Large Language Models (LLMs) provide a new approach in which lexical functions emerge from the learning and processing of sequences in contexts. We prompted lexical functions in ChatGPT and compared numeric responses with averaged human data for a sample of 390 words for a range of lexical variables, some derived from corpus analyses and some from Likert ratings. ChatGPT responses were moderately to highly correlated with mean values, more so for GPT-4 versus GPT-3.5, and responses were sensitive to context and human inter-rater reliability. We argue that responses were not recalled from memorized training data but were instead soft-assembled from more general-purpose representations. Emergent functions in LLMs offer a new approach to modeling language and cognitive processes.</span>

[A version of this paper appeared in the Proceedings of the 46th Annual Meeting of the Cognitive Science Society.](https://escholarship.org/uc/item/5m9098b5)

---

**Concept Alignment** (Rane,* Bruna,* Sucholutsky, Kello, & Griffiths, 2024)

[*Preprint*](http://arxiv.org/abs/2401.08672)

<span style="font-size:0.75em;">Discussion of AI alignment (alignment between humans and AI systems) has focused on value alignment, broadly referring to creating AI systems that share human values. We argue that before we can even attempt to align values, it is imperative that AI systems and humans align the concepts they use to understand the world. We integrate ideas from philosophy, cognitive science, and deep learning to explain the need for concept alignment, not just value alignment, between humans and machines. We summarize existing accounts of how humans and machines currently learn concepts, and we outline opportunities and challenges in the path towards shared concepts. Finally, we explain how we can leverage the tools already being developed in cognitive science and AI research to accelerate progress towards concept alignment.</span>

[A version of this paper appeared at the 37th Annual NeurIPS Conference in the workshop: AI meets Moral Philosophy and Moral Psychology (MP2).](https://aipsychphil.github.io)

---

**What Next? : Leveraging Surprise in a Recurrent Neural Network to (de)Construct Morphological Complexity in Japanese** (Bruna, 2022)

*This work was completed as an undergraduate senior thesis.*

<span style="font-size:0.75em;">Formal language modeling exhibits a bias towards the linguistic features observed in English and related languages, namely the ability to describe language in terms of word-based units. This bias has caused language models to be ill-equipped for success in languages exhibiting a high degree of morphological complexity, such as the agglutinative morphology found in Japanese, and indicates a shortcoming in our understanding of the underlying cognitive processes that allow us to be thinkers, speakers, and listeners. I employ a recurrent neural network (RNN) to explore character-by-character predictability in samples of contemporary Japanese text. I address what properties of agglutinative morphology are salient to neural networks and offer a comparison between meaning construction in Japanese and English. This study further investigates the unique morpho-syntactic role played by orthography in Japanese. I find success in extracting certain key features of the structure of Japanese sentences using an RNN and offer a path for deepening our understanding of the differences in information encoding and processing that we observe across languages and how these differences arise.</span>

---

**Psychophysical Adaptive Procedure: Developing a New, Generalizable Method** (Bruna, 2021)

*This work was completed as an undergraduate research project.*

<span style="font-size:0.75em;">“Staircasing” is a classic experimental procedure used in psychophysics wherein when a subject successfully discriminates between two stimuli that differ on one perceptual dimension, the stimuli become more similar to each other on that dimension, and when the subject fails, the stimuli become more different. The purpose of this procedure is to find the size of the difference that produces a specific level of discrimination success. Traditional staircase procedures require subjects to be run individually for many trials. Our goal was to develop a procedure for crowd-sourced online data collection in which subjects can be tested simultaneously using only a few trials each with every new piece of data altering the stimulus pair shown on the next trial. We do this by continually fitting subject responses to a plausible function that is used to predict the difference that should produce the desired accuracy level. Only presenting differences predicted to yield the desired performance allows us to find the difference corresponding to this accuracy level faster than sampling the whole range of stimulus differences. The stimulus values we determined with this method were used for research on the phenomenon of learned categorical perception. We present this new technique as an efficient way of determining psychophysical values more generally for purposes of controlling stimulus discriminability in experimental research.</span>

[OSF](https://osf.io/6j4sk/)

---

**Words May Jump-Start Meaning More Than Vision: A Non-Replication of Early ERP Effects in Boutonnet and Lupyan (2015)**

de Leeuw, J. R., Andrews, J., Barney, L., Bigler, M., Bruna, P., Chen, Y., Cherry, R., Dowie, D. R., Forbes, 
E., Haffey, B., Hu, X., Jaklitsch, M., Leopold, N., Lewis, C., MacDonald, D., McShaffrey, C., Nakayama, K., Olstad, W., Peng, R., … Zhang, L. (2021)

[*Published in Collabra: Psychology*](https://online.ucpress.edu/collabra/article/7/1/29763/119070/Words-May-Jump-Start-Meaning-More-Than-Vision-A)

<span style="font-size:0.75em;">We report a replication of Boutonnet and Lupyan’s (2015) study of the effects of linguistic labelling on perceptual performance. In addition to a response time advantage of linguistic labels over non-linguistic auditory cues in judging visual objects, Boutonnet and Lupyan found that the two types of cues produced different patterns in the early perceptual ERP components P1 and P2 but not the later, semantics-relevant N4. This study thus adds an important piece of evidence supporting the claim of genuine top-down effects on perception. Given the controversy over this claim and the need for replication of key findings, we attempted to replicate Boutonnet and Lupyan (2015). We replicated their behavioral findings that response times to indicate whether an auditory cue matches a visual image of an object were faster for match than mismatch trials and faster for linguistic than non-linguistic cues. We did not replicate the main ERP effects supporting a positive effect of linguistic labels on the early perceptual ERP components P1 and P2, though we did find a congruence by cue type interaction effect on those components. Unlike Boutonnet and Lupyan, we found a main effect of cue type on the N4 in which non-linguistic cues produced more negative amplitudes. Exploratory analyses of the unpredicted N4 effect suggest that the response time advantage of linguistic labels occurred during semantic rather than early visual processing. This experiment was pre-registered at https://osf.io/cq8g4/ and conducted as part of an undergraduate cognitive science research methods class at Vassar College.</span>

[OSF](https://osf.io/cq8g4/)

---

**Exploring Semantic Relatedness Judgments in the Structure of a Semantic Network** (Bruna, 2020)

*This work was completed as an undergraduate independent study project.*

[*Paper*](https://osf.io/sj7tg)

<span style="font-size:0.75em;">Drawing upon work by De Deyne et al. (2016), I explore a model of spreading activation through a semantic network in regards to how different kinds of semantic relationships are encoded  in  said  network.  In  particular,  I  examine  the contribution  of  indirect  pathways  through  the  network  to explain differences in similarity judgments of sensorimotor and linguistic relationships between pairs of words. I propose that the structure of a semantic network  encodes properties that distinguish these two types of semantic relationships that are not  revealed  by  measures  of  association  strength  that  only examine  direct  connections  within  the  network.  A  cosine similarity measure extracted from a spreading activation model is compared to a measure of association strength in accounting for observed similarity judgments, and a model for examining the differential contributions of various random walk pathways through a semantic network in the encoding of sensorimotor and linguistic semantic relationships is presented.</span>

[OSF](https://osf.io/3e2tq/)

