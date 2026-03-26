# Anonymous Supplementary Material for Rebuttal

This page presents **a practical and implementable example for testing model autonomy**.  
Our central claim is that autonomy-oriented evaluation should not rely only on fixed, traditional benchmark tasks written entirely in advance by humans. Instead, evaluation tasks can be generated according to a **task-generation paradigm**, so that the benchmark is extensible, interaction-grounded, and open-ended.

For a concrete description of the proposed generation paradigm, please see:  
**[Autonomous task generation: a concrete experimental paradigm](task_generation_paradigm.md)**

The eight tasks shown below are therefore **not meant as a closed and final task list**, but as **an instantiated example** of how such a paradigm can be operationalized in a household environment.

---

## Benchmark Scope

To illustrate this idea concretely, we construct eight daily embodied task categories in simulated home environments:

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