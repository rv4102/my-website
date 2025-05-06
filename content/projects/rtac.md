---
title: "Inter IIT Tech Meet 12.0 – Gold Winning Solution"
date: 2023-12-05
draft: false
---

## [Reimagining Tooling as Coding (RTaC) Framework](https://github.com/rv4102/tooling-as-coding)
### Objective: Create a low-latency tool-use LLM which matches closed-source LLMs in performance while being cost-effective
1. Created RTaC framework to convert tools to python functions, promoting docstring-reading capabilities in coding-base LLMs
2. Utilized PEFT to finetune Code Llama 7B & DeepSeek 1.3B on 2500 examples of manually cleaned GPT generated synthetic data
3. Achieved a competitive performance to GPT-4 at 20% of the cost, supporting dynamic tool addition & mathematical/iterative logic