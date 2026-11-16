# Foundation Model Research Engineering Lab

A structured engineering and research curriculum covering the foundations of modern large language models, training systems, architecture research, reinforcement learning, post-training and evaluation.

## Curriculum

- **00 — Engineering Foundations**
  - [tensor_operations](00_engineering_foundations/tensor_operations/)
  - [autograd](00_engineering_foundations/autograd/)
  - [optimizers](00_engineering_foundations/optimizers/)
- **01 — Transformers**
  - [tokenizer](01_transformers/tokenizer/)
  - [attention](01_transformers/attention/)
  - [transformer](01_transformers/transformer/)
  - [gpt](01_transformers/gpt/)
- **02 — Pretraining**
  - [data_pipeline](02_pretraining/data_pipeline/)
  - [data_filtering](02_pretraining/data_filtering/)
  - [training](02_pretraining/training/)
  - [scaling_laws](02_pretraining/scaling_laws/)
- **03 — Architecture Research**
  - [attention_variants](03_architecture_research/attention_variants/)
  - [moe](03_architecture_research/moe/)
  - [state_space_models](03_architecture_research/state_space_models/)
  - [experiments](03_architecture_research/experiments/)
- **04 — ML Systems**
  - [profiling](04_ml_systems/profiling/)
  - [cuda](04_ml_systems/cuda/)
  - [triton](04_ml_systems/triton/)
  - [distributed_training](04_ml_systems/distributed_training/)
  - [inference](04_ml_systems/inference/)
- **05 — Reinforcement Learning**
  - [bandits](05_reinforcement_learning/bandits/)
  - [policy_gradients](05_reinforcement_learning/policy_gradients/)
  - [ppo](05_reinforcement_learning/ppo/)
  - [environments](05_reinforcement_learning/environments/)
- **06 — Post-training**
  - [sft](06_posttraining/sft/)
  - [reward_models](06_posttraining/reward_models/)
  - [dpo](06_posttraining/dpo/)
  - [grpo](06_posttraining/grpo/)
  - [rlvr](06_posttraining/rlvr/)
- **07 — Evaluation**
  - [benchmarks](07_evaluation/benchmarks/)
  - [ablations](07_evaluation/ablations/)
  - [statistical_analysis](07_evaluation/statistical_analysis/)

## Supporting Workspaces

- `sidecar/`: C, C++ and OS exercises.
- `experiments/`: standalone experiments and benchmarks.
- `research_notes/`: weekly research and engineering notes.
- `hardware.md`: development hardware and compute constraints.

## Environment

Python environment: `~/envs/foundation-model-lab`

Activate it with:

```bash
source ~/envs/foundation-model-lab/bin/activate
```


## Assignment Tracking

Assignment links are provided above. Completion status will be updated as each assignment is completed.
