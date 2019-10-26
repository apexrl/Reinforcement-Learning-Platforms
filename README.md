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
| [Ray](https://github.com/ray-project/ray) | C++ | Python | - | 20+ | N | RL framework, distributed, hyperparameter tuning, RLlib, accelerate, **able to work for Multi-agent RL**. |
| [Open_Spiel](https://github.com/deepmind/open_spiel) | C++ | Python | 28 | 24 | Y | Game Theory with RL (Multi-agent). |
| [Bsuite(Dopamine)](https://github.com/deepmind/bsuite) | Python | Python | - | - | N | Architecture, architecture research, comprehensive studies, visualization, algorithmic research, instruction |
| [Softlearning](https://github.com/rail-berkeley/softlearning) | Python<br>(TF/Pytorch) | Python | - | 5 | N | Training framework, maximum entropy, continuous, Ray. |
| [Rllab](https://github.com/rll/rllab) | Python | Python | - | 8 | N | Training framework, continuous control tasks, algorithm implementations. |
| [RLkit](https://github.com/vitchyr/rlkit) | Python (Pytorch) | Python | - | 7 | N | Algorithms, PyTorch. |
| [Spriteworld](https://github.com/deepmind/spriteworld) | Python | Python | 3 | - | N | Flexibility, procedurally generating Multi-object scenes, simple interface. |
| [OpenAI Gym](https://github.com/openai/gym) | Python | Python | 22 major class, each keeps several detailed environments | 2+ | N | Toolkit, standardized set of environments and AIP format. Basis for most RL environments. |
| [Golds-rl-gym](https://github.com/cjm715/mgym) | Python | Python | 1 | 2 | Y | Continous control RL algorithms, Multi-agent environments, based on OpenAI Gym API. |
| [Domination-Game](https://github.com/noio/Domination-Game) | Python | Python | 1 | - | Y | Simulation engine, Multi-agent competitive game. |
| [MAS Environment Collection-01](https://github.com/cjm715/mgym) | Python | Python | 8 | - | Y | Collection, Multi-agent OpenAI gym environments. |
| [MAS Environment Collection-02](https://github.com/allentran/golds-rl-gym) | Python | Python | 6 | - | Y | Collection, Multi-agent enviroments. |
| [ROBEL: Robotics Benchmarks for Learning](https://github.com/google-research/robel) | Python | Python | 2 | - | N | Platform, cost-effective robots, associated RL environments, Gym-compliant API. |
| [Model Based Reinforcement Learning Benchmarking Library (MBBL)](https://github.com/WilsonWangTHU/mbbl) | Python | Python | 18 | 18+ | N | Collection of MBRL algorithms, 18 benchmarking environments for MBRL. |
| [PySC2](https://github.com/deepmind/pysc2) | Python | Python | - | 1+ | Y |  StarCraft II Learning Environment (SC2LE). |
| [DeepMind Lab](https://github.com/deepmind/lab) | C/C++ | Python/Lua | - | 1+ | N | Customisable 3D platform. |
| [Project Malmo](https://github.com/Microsoft/malmo) | C/C++ | Python/C++/<br>C#/Java | - | 1+ | N | Minecraft environment. |
| [ViZDoom](https://github.com/Marqt/ViZDoom) | C/C++ | Python/C++/<br>Lua/Java/Julia | - | 1+ | N | Doom-based environment, raw visual information. |
| [retro](https://github.com/openai/retro) | C/C++ | Python | - | 9+ | N | Video game emulators. Supports SNES and Sega Genesis. Compatible with OpenAI gym. |
| [TensorForce](https://github.com/reinforceio/tensorforce) | Python | Python | - | - | N | RL with TensorFlow,  Gitter support, OpenAI Gym/Universe/DeepMind Lab integration. |
| [tf-TRFL](https://github.com/deepmind/trfl/) | Python | Python | - | - | N | TensorFlow, useful building blocks for RL agents. |
| [keras-rl](https://github.com/matthiasplappert/keras-rl) | Python | Python | - | - | N | RL algorithms, Keras, compatibley with OpenAI. |
| [MAgent](https://github.com/geek-ai/MAgent) | Python | Python | - | - | Y | Many-agent RL. 
| [SLM Lab](https://github.com/kengz/SLM-Lab) | Python | Python | - | 16+ | N | Canonical RL algorithms, reusable modular components, reproductivable.
| [Unity ML Agents](https://github.com/Unity-Technologies/ml-agents) | Python | Python | - | 16+ | Y | RL environments, Unity Editor.
| [Intel Coach](https://github.com/NervanaSystems/coach) | Python | Python | - | 9+ | N | Implementations, state-of-the-art algorithms.
| [RL Card](https://github.com/datamllab/rlcard) | Python | Python | - | 8 | Y | Toolkit, card games, environments.
