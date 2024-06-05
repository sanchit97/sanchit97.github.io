---
title: "MAML-en-LLM: Model Agnostic Meta-Training of LLMs for Improved In-Context Learning"
collection: publications
permalink: /publication/
excerpt: 
date: 2024-01-01
venue: 'KDD-2024'
paperurl: 'https://arxiv.org/abs/2405.11446'
# citation: 'Sanchit Sinha'
---
 
Adapting large language models (LLMs) to unseen tasks with in- context training samples without fine-tuning remains an important research problem. To learn a robust LLM that adapts well to unseen tasks, multiple meta-training approaches have been proposed such as MetaICL and MetaICT, which involve meta-training pre-trained LLMs on a wide variety of diverse tasks. These meta-training ap- proaches essentially perform in-context multi-task fine-tuning and evaluate on a disjointed test set of tasks. Even though they achieve impressive performance, their goal is never to compute a truly gen- eral set of parameters. In this paper, we propose MAML-en-LLM, a novel method for meta-training LLMs, which can learn truly gen- eralizable parameters that not only performs well on disjointed tasks but also adapts to unseen tasks. We see an average increase of 2% on unseen domains in the performance while a massive 4% improvement on adaptation performance. Furthermore, we demon- strate that MAML-en-LLM outperforms baselines in settings with limited amount of training data on both seen and unseen domains by an average of 2%. Finally, we discuss the effects of type of tasks, optimizers and task complexity, an avenue barely explored in meta- training literature. Exhaustive experiments across 7 task settings along with two data settings demonstrate that models trained with MAML-en-LLM outperform SOTA meta-training approaches.

[Download paper here](https://arxiv.org/abs/2405.11446)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->