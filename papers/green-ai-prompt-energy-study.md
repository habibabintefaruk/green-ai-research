# Green AI: Prompt Design and Energy Consumption

## 1. Research Overview

This research explores how changing instruction verbs in Large Language Model (LLM) prompts affects energy consumption during inference.

## 2. Research Objective

The main objective is to investigate whether using energy-conscious prompt instructions can reduce computational energy consumption without significantly affecting output quality.

## 3. Key Findings

- Token count has a very strong relationship with energy consumption.
- Shorter outputs generally require less energy.
- Explicit output-length instructions can help reduce energy consumption.
- Energy efficiency should be considered alongside output quality.

## 4. Models Used

The study evaluated three language models:

- Qwen 2.5 7B
- Llama 3.1 8B
- Mistral 7B

## 5. Connection to Green AI

This research demonstrates how prompt design can contribute to more energy-efficient AI systems.

Green AI encourages reducing computational resource consumption while maintaining useful model performance.

## 6. Personal Learning

From this research, I learned that small changes in prompt design may influence the energy consumption of Large Language Models.

I also understood the importance of balancing AI performance with computational efficiency.

## 7. Keywords

Green AI, Large Language Models, Energy Consumption, Prompt Engineering, Inference Efficiency


## 8. Quantitative Research Findings

The study conducted 21,600 inferences across three open-weight language models.

Key findings:

- A strong correlation (r ≥ 0.998) was observed between output token count and energy consumption.
- Explicit short-answer instructions performed better than verb swapping in 7 out of 9 model-task settings.
- Reducing output length can help improve energy efficiency.
- Verb swapping alone does not guarantee energy savings.

## 9. Research Reference

Farabi, A., Khandaker, I., Minhaz, M. A. A., Meem, Z. Z., Shanto, I. K., & Mahmud, S. (2026).

GreenSwap: Verb Choice or Output Length? A Controlled Decomposition of Prompt-Level Energy Savings in LLM Inference.

Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing, pages 53711–53724.

Publisher: Association for Computational Linguistics.

Original Paper: https://aclanthology.org/2026.emnlp-main.2366/
