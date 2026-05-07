# GPTs in ChatGPT Configurations for Origami Simulator

This repository contains configuration files for GPTs in ChatGPT designed to operate an origami simulator.

The primary function of these configurations is to reliably generate simulator commands based on both origami images and textual entries for the corresponding transitions.

These configurations are intended to make the GPTs setup reproducible by documenting the instructions files, knowledge files, recommended model, and capability settings used in each task.


## Directory Structure

```text
.
├─ README.md
├─ gpt_config_task_1.yaml
├─ gpt_config_task_2.yaml
├─ instructions/
│  ├─ task_1.md
│  └─ task_2.md
└─ knowledge/
   ├─ command_specification.json
   ├─ basic_examples.json
   └─ additional_useful_examples.json
```


## File Descriptions

- `gpt_config_task_1.yaml`  
  GPT configuration for task_1. Refer to `instructions/task_1.md` for details.
- `gpt_config_task_2.yaml`  
  GPT configuration for task_2. Refer to `instructions/task_2.md` for details.
- `instructions/task_1.md`  
  Designed for Task1.
- `instructions/task_2.md`  
  Designed for Task2.
- `knowledge/command_specification.json`  
  Defines the simulator command specifications.
- `knowledge/basic_examples.json`  
  Provides basic usage examples for the commands defined in `command_specification.json`.
- `knowledge/additional_useful_examples.json`  
  Provides additional usage examples for the commands defined in `command_specification.json`.