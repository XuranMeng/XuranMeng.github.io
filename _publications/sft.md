---
title: "Temporal Self-Rewarding Language Models: Decoupling Chosen-Rejected via Past-Future."
collection: publications
category: preprints
permalink: /publication/sft
date: 2025-8-8
#excerpt: 'Submitted to JMLR'
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2508.06026'
citation: 'Yidong Wang et. al., &quot;Temporal Self-Rewarding Language Models: Decoupling Chosen-Rejected via Past-Future.&quot; <i>arxiv: 2508.06026</i>, 2025.'
---
Self-Rewarding Language Models propose an architecture in which the Large Language Models(LLMs) both generates responses and evaluates its own outputs via LLM-as-a-Judge prompting, dynamically improving its generative capabilities through iterative Direct Preference Optimization (DPO). However, our analysis reveals a critical limitation in existing Self-Rewarding paradigms: the synchronized improvement of chosen and rejected responses progressively narrows the representational difference between contrasting samples, undermining effective preference learning. We propose \textbf{Temporal Self-Rewarding Language Models} that strategically coordinate past, present, and future model generations to sustain learning signals. Our dual-phase framework introduces: (1) \textit{Anchored Rejection} - fixing rejected responses using the past initial model's outputs and (2) \textit{Future-Guided Chosen} - dynamically curating chosen samples using next-generation model predictions. Extensive experiments across three model families (Llama, Qwen, Mistral) and different model sizes (Llama3B/8B/70B) demonstrate significant improvements when trained with our method compared to Self-Rewarding using same computation resources. For example, Llama3.1-8B reaches a 29.44 win rate on AlpacaEval 2.0 with our method, outperforming the Self-Rewarding baseline (19.69) by 9.75. Notably, our method also demonstrates superior out-of-distribution generalization across mathematical reasoning (GSM8K), knowledge-based QA (ARC, TruthfulQA), and code generation (HumanEval) tasks, even though we do not specifically collect such training data.
