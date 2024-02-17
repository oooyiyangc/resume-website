---
title: "Generative Agents and its Applications"
date: 2024-01-23T00:37:01.137Z
draft: false
private: true
featured: false
image:
  focal_point: Smart
  preview_only: true
  caption: "Image credit: [Park et. al](https://arxiv.org/abs/2304.03442)"
# tags:
#   - research
#   - macroeconomics
#   - theory
#   - inflation
# categories:
#   - research ideas
---

At the dynamic interface between economics and artificial intelligence, a fascinating development is attracting the attention of researchers and practitioners alike: the use of Large Language Models (LLMs) to simulate economic agents. This intersection represents not just a technological leap, but a conceptual revolution in understanding economic behavior and systems.

Agent-based modeling, a staple of economic analysis, traditionally involves creating algorithms that represent individual agents - entities that embody consumers, firms, or even entire institutions. These agents interact in a simulated environment, allowing economists to observe the complex phenomena that emerge from these interactions. The introduction of LLMs, such as those developed by OpenAI, into this field is changing the landscape.

LLMs, known for their ability to generate human-like text and process natural language, offer a new dimension of realism in modeling economic agents. By giving these agents the ability to "think" and "communicate" in ways that closely mimic human reasoning and negotiation, researchers can explore economic dynamics with unprecedented depth and nuance.

The potential applications are vast and varied. From simulating market negotiations and consumer behavior to predicting macroeconomic trends and policy impacts, LLM-driven agents open new avenues for understanding and predicting economic outcomes. This approach also offers a novel way to test economic theories, providing a virtual environment in which hypotheses can be explored and refined.

However, this exciting frontier is not without its challenges and considerations. Chief among these is the quality of the data that feeds these models - the classic "garbage in, garbage out" problem. The design and training of LLMs requires careful consideration to ensure that the economic simulations they power are realistic and free from biases inherent in their training data.

In addition, the use of LLMs in economics raises interesting philosophical and methodological questions. How well can these simulated agents replicate human decision making in economic contexts? What are the limitations in terms of complexity and ethical considerations? These questions are central to the ongoing dialog in the field.

As we continue to explore this fascinating confluence of economics and AI, we stand on the brink of a new era in economic analysis. The promise of AI to enrich our understanding of economic phenomena is immense, and the journey ahead is as exciting as it is uncertain.

Here I will present some exciting papers that explore this field. 

## Survey works

### Wei et. al (2023)
A Survey on Large Language Model based Autonomous Agents, https://arxiv.org/abs/2308.11432

{{< figure src="LLM-Agent-Survey.png" title="https://github.com/Paitesanshi/LLM-Agent-Survey" >}}

This paper surveys both the framework of LLM-based agents and its applications. 

#### Framework

> "We propose a unified framework to summarize these modules. In specific, the
overall structure of our framework is illustrated Figure 2, which is composed of a profiling module, a
memory module, a planning module, and an action module. The purpose of the profiling module is
to identify the role of the agent. The memory and planning modules place the agent into a dynamic
environment, enabling it to recall past behaviors and plan future actions. The action module is
responsible for translating the agent’s decisions into specific outputs. Within these modules, the
profiling module impacts the memory and planning modules, and collectively, these three modules
influence the action module. In the following, we detail these modules." (Section 2.1)

{{< figure src="LLM-Agent-Survey-figure-2.png" >}}

#### Applications

{{< figure src="LLM-Agent-Survey-table-2.png" >}}

Many papers fall into natural science and engineering, which is not our focus. 

### Wang et al. (2023)
Aligning Large Language Models with Human: A Survey, https://arxiv.org/pdf/2307.12966.pdf


### Mialon et al. (2023)
Augmented Language Models: a Survey, https://arxiv.org/abs/2302.07842

Augmented language models are essentially language models "augmented" with reasoning skills and abilities to use tools. For example, it may be very hard for a language model to learn to do algebra, but it will be a reasonably simple task if the language model has access to a code interpreter. In this case, the language model needs to interpret the question, break it down into smaller components, generate code, and call the external code interpret to get the final answer.  

Section 4 of the survey paper discusses reasoning. Two methods are presented: supervised learning through few-shot prompting and reinforcement learning. 


### Gao et. al (2023)
Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives, https://arxiv.org/abs/2312.11970



<br>

## Evaluating LLM-agents




<br>

## Applications in Economics

### Horton (2023)
Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?, https://www.nber.org/papers/w31122

### Bybee (2023)
Surveying Generative AI's Economic Expectations, https://arxiv.org/abs/2305.02823

### Li (2023)
Large Language Model-Empowered Agents for Simulating Macroeconomic Activities, https://arxiv.org/abs/2310.10436

### Shapira (2024)
Can Large Language Models Replace Economic Choice Prediction Labs?, https://arxiv.org/abs/2401.17435






<br>




