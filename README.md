# Reinforcement-Learning-Platforms
Collections of powerful RL platforms with brief introductions, including repositories of environments impletations, algorithm impletations, RL frameworks and other collections. Old platforms are not listed because of out of fashion. [Reference](https://github.com/aikorea/awesome-rl/blob/master/README.md).

Legend:

* Base Language: The source language.

* API Language: The language to be called.

* Environment: The RL environment contatined, "-" means no environment is impletmented, but most can deal with OpenAI gym API.

* Algorithm: The RL algorithm contatined, "-" means no algorithm is impletmented, but many of them can deal with self-designed algorithms.

* Multi-agent: Is or not this repository made particularly for Multi-agent.

* Remarks: The target of this repository.

| Name | Base Language | API Language | Environment | Algorithm | Multi-agent | Remarks |
| :-----: | :----: | :----: | :----: | :----: | :----: | :----: |
| [Ray](https://github.com/ray-project/ray) | C++ | Python | - | 20+ | N | RL framework for building and running distributed applications, packaged with \[Tune (Scalable Hyperparameter Tuning) / RLlib (Scalable Reinforcement Learn ) / Distributed Training\] for accelerating machine learning workloads, is **able to work for Multi-agent RL**. |
| [Open_Spiel](https://github.com/deepmind/open_spiel) | C++ | Python | 28 | 24 | Y | Mainly for Game Theory with RL (Multi-agent). |
| [Bsuite(Dopamine)](https://github.com/deepmind/bsuite) | Python | Python | - | - | N | Architecture for RL, for architecture research, comprehensive studies, visualization, algorithmic research, and instruction |
| [Softlearning](https://github.com/rail-berkeley/softlearning) | Python<br>(TF/Pytorch) | Python | - | 5 | N | RL framework for training maximum entropy policies in continuous domains, based on Ray. |
| [Rllab](https://github.com/rll/rllab) | Python | Python | - | 8 | N | A framework for developing and evaluating reinforcement learning algorithms. It includes a wide range of continuous control tasks plus implementations of the following algorithms. |
| [RLkit](https://github.com/vitchyr/rlkit) | Python (Pytorch) | Python | - | 7 | N | RL framework and algorithms implemented in PyTorch. |
| [Spriteworld](https://github.com/deepmind/spriteworld) | Python | Python | 3 | - | N | Aims to provide as much flexibility for procedurally generating Multi-object scenes while retaining as simple an interface as possible. |
| [OpenAI Gym](https://github.com/openai/gym) | Python | Python | 22 major class, each keeps several detailed environments | 2+ | N | A toolkit for developing and comparing reinforcement learning algorithms which also contains a standardized set of environments and AIP format. This is the basis for a large number of RL environments. |
| [Golds-rl-gym](https://github.com/cjm715/mgym) | Python | Python | 1 | 2 | Y | Continous control RL algorithms and Multi-agent environments, based on OpenAI Gym API. |
| [Domination-Game](https://github.com/noio/Domination-Game) | Python | Python | 1 | - | Y | A simulation engine for a Multi-agent competitive game. |
| [MAS Environment Collection-01](https://github.com/cjm715/mgym) | Python | Python | 8 | - | Y | A collection of Multi-agent OpenAI gym environments. |
| [MAS Environment Collection-02](https://github.com/allentran/golds-rl-gym) | Python | Python | 6 | - | Y | Some Multi-agent enviroment in selected papers. |
| [ROBEL: Robotics Benchmarks for Learning](https://github.com/google-research/robel) | Python | Python | 2 | - | N | An open-source platform of cost-effective robots and associated RL environments which provides Gym-compliant API. |
| [Model Based Reinforcement Learning Benchmarking Library (MBBL)](https://github.com/WilsonWangTHU/mbbl) | Python | Python | 18 | 18+ | N | A wide collection of MBRL algorithms and propose over 18 benchmarking environments specially designed for MBRL. |
| [PySC2](https://github.com/deepmind/pysc2) | Python | Python | - | 1+ | Y |  DeepMind's Python component of the StarCraft II Learning Environment (SC2LE). It exposes Blizzard Entertainment's StarCraft II Machine Learning API as a Python RL Environment. |
| [DeepMind Lab](https://github.com/deepmind/lab) | C/C++ | Python/Lua | - | 1+ | N | A customisable 3D platform for agent-based AI research. |
| [Project Malmo](https://github.com/Microsoft/malmo) | C/C++ | Python/C++/<br>C#/Java | - | 1+ | N | A platform for Artificial Intelligence experimentation and research built on top of Minecraft by Microsoft. |
| [ViZDoom](https://github.com/Marqt/ViZDoom) | C/C++ | Python/C++/<br>Lua/Java/Julia | - | 1+ | N | Doom-based AI research platform for reinforcement learning from raw visual information. |
| [retro](https://github.com/openai/retro) | C/C++ | Python | - | 9+ | N | An AI platform for reinforcement learning based on video game emulators. Currently supports SNES and Sega Genesis. Compatible with OpenAI gym. |
| [TensorForce](https://github.com/reinforceio/tensorforce) | Python | Python | - | - | N | Practical deep reinforcement learning on TensorFlow with Gitter support and OpenAI Gym/Universe/DeepMind Lab integration. |
| [tf-TRFL](https://github.com/deepmind/trfl/) | Python | Python | - | - | N | A library built on top of TensorFlow that exposes several useful building blocks for implementing Reinforcement Learning agents. |
| [keras-rl](https://github.com/matthiasplappert/keras-rl) | Python | Python | - | - | N | Lots of deep reinforcement learning algorithms in Keras designed for compatibility with OpenAI. |
| [MAgent](https://github.com/geek-ai/MAgent) | Python | Python | - | - | Y | A Platform for Many-agent Reinforcement Learning. 
| [SLM Lab](https://github.com/kengz/SLM-Lab) | Python | Python | - | 16+ | N | A research framework for Deep Reinforcement Learning using Unity, OpenAI Gym, PyTorch, Tensorflow.
| [Unity ML Agents](https://github.com/Unity-Technologies/ml-agents) | Python | Python | - | 16+ | Y | Create reinforcement learning environments using the Unity Editor
| [Intel Coach](https://github.com/NervanaSystems/coach) | Python | Python | - | 9+ | N | Coach is a python reinforcement learning research framework containing implementation of many state-of-the-art algorithms.
