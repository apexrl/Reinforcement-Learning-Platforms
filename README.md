# Reinforcement-Learning-Architectures
Collections of powerful RL architectures with brief introductions, including repositories of environments impletation, algorithm impletation, RL framework and other collections.

Legend:

Base Language: The source language.

API Language: The language to be called.

Environment: The RL environment contatined, "-" means no environment is impletmented, but most can deal with OpenAI gym API.

Algorithm: The RL algorithm contatined, "-" means no algorithm is impletmented, but many of them can deal with self-designed algorithms.

Multi-agent: Is or not this repository can be made for Multi-agent.

Remarks: The target of this repository.

| Name | Base Language | API Language | Environment | Algorithm | Multi-agent | Remarks |
| :-----: | :----: | :----: | :----: | :----: | :----: | :----: |
| [Ray](https://github.com/ray-project/ray) | C++ | Python | - | 20+ | - [x] | RL framework for building and running distributed applications, packaged with \[Tune (Scalable Hyperparameter Tuning) / RLlib (Scalable Reinforcement Learn ) / Distributed Training\] for accelerating machine learning workloads, is able to work for Multi-agent RL. |
| [Open_Spiel](https://github.com/deepmind/open_spiel) | C++ | Python | 28 | 24 | - | Mainly for Game Theory with RL (Multi-agent). |
| [Bsuite(Dopamine)](https://github.com/deepmind/bsuite) | Python | Python | - | - | - | Architecture for RL, for architecture research, comprehensive studies, visualization, algorithmic research, and instruction |
| [Softlearning](https://github.com/rail-berkeley/softlearning) | Python (TF/Pytorch) | Python | - | 5 | - | RL framework for training maximum entropy policies in continuous domains, based on Ray. |
| [Rllab](https://github.com/rll/rllab) | Python | Python | - | 8 | - | A framework for developing and evaluating reinforcement learning algorithms. It includes a wide range of continuous control tasks plus implementations of the following algorithms. |
| [RLkit](https://github.com/vitchyr/rlkit) | Python (Pytorch) | Python | - | 7 | - | RL framework and algorithms implemented in PyTorch. |
| [Spriteworld](https://github.com/deepmind/spriteworld) | Python | Python | 3 | - | $\surd$ | Aims to provide as much flexibility for procedurally generating Multi-object scenes while retaining as simple an interface as possible. |
| [OpenAI Gym](https://github.com/openai/gym) | Python | Python | 22 major class, each keeps several detailed environments | 2+ | - [x] | Contains a standardized set of environments and AIP format. This is the basis for a large number of RL environments. |
| [Golds-rl-gym](https://github.com/cjm715/mgym) | Python | Python | 1 | 2 | - [x] | Continous control RL algorithms and Multi-agent environments, based on OpenAI Gym API. |
| [Domination-Game](https://github.com/noio/Domination-Game) | Python | Python | 1 | - | - [x] | A simulation engine for a Multi-agent competitive game. |
| [MAS Environment Collection-01](https://github.com/cjm715/mgym) | Python | Python | 8 | - | - [x] | A collection of Multi-agent OpenAI gym environments. |
| [MAS Environment Collection-02](https://github.com/allentran/golds-rl-gym) | Python | Python | 6 | - | - [x] | Some Multi-agent enviroment in selected papers. |



