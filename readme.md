# Anonymous Supplementary Material for Rebuttal

This supplementary material contains two complementary components:

1. **Autonomous task generation and evaluation** – a concrete instantiation of how open-ended tasks can be automatically generated and used for in‑situ evaluation of embodied agents. See [task_generation_results.md](task_generation_results.md) for details, quantitative results, and evaluation statistics.

2. **A worked household benchmark** – a fixed set of eight household tasks as an example of how generated tasks can be organized into a structured evaluation suite. The following sections present this benchmark.

---

## Benchmark Scope

To illustrate the idea concretely, we construct eight daily embodied task categories in simulated home environments:

- Counting Objects  
- Building Blocks  
- Jigsaw Puzzle  
- Understanding Buttons  
- Setting Tables  
- Tidying Up Rooms  
- Preparing Baggage  
- Selecting Gifts  

These task categories are intended to cover a broad range of embodied capabilities required in household environments, including object understanding, spatial reasoning, and activity completion.

![Benchmark overview](figures/fig2_task_overview.png)

**Figure 1.** Overview of the eight household task categories and representative subtasks.  
These tasks are presented here as a concrete instantiation of an autonomy-oriented task-generation framework, rather than as a fixed and exhaustive benchmark list.

---

## Evaluation Framework

The evaluation is conducted in a simulated home arena through a perception–decision–action loop. The system connects multimodal LLMs with the embodied environment through a perception module and an action module, enabling task-oriented interaction and performance assessment.

![System framework](figures/fig3_framework.png)

**Figure 2.** System framework for evaluating MLLM-based embodied agents.

---

## Task-Level Performance

The following figure presents model performance across the eight task categories. It illustrates substantial variation across tasks and highlights the difficulty of complex embodied activities in home environments.

![Performance on eight tasks](figures/fig4_results_8_tasks.png)

**Figure 3.** Performance of evaluated MLLM agents across the eight task categories.

---

## Model Family Distribution

To further illustrate benchmark behavior at the model-family level, the following figure summarizes the ability distributions of major model series across task categories.

![Model family ability distribution](figures/fig6_model_family_distribution.png)

**Figure 4.** Ability distributions of major model families across the benchmark.

---

## Interpretation

This supplementary page is intended to show that autonomy-oriented evaluation can be made concrete in a practical embodied setting.  
The household benchmark presented here should be read as:

1. a **worked example** of how autonomous task generation can be instantiated in a realistic environment;  
2. a **structured task family**, rather than a single frozen benchmark; and  
3. a demonstration that autonomy evaluation can move from abstract discussion to reproducible experimental design.

---

## Note

This page is intentionally limited to a compact visual supplement for peer review. It is provided to facilitate direct inspection of the benchmark design and representative evaluation figures in a single location.

## Anonymity Statement

This repository is provided in anonymized form for review purposes only.