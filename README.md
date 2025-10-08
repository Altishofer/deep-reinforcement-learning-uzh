# Generalization in Procedurally Generated Environments

This repository contains code and instructions for the project "Generalization in Procedurally Generated Environments" as part of the Deep Reinforcement Learning course at the University of Zurich (UZH).


## GitHub Resources
- [ProcGen Repository](https://github.com/openai/procgen?tab=readme-ov-file)
- [Minigrid Repository](https://github.com/Farama-Foundation/Minigrid)
- [Gym OpenAI](https://github.com/openai/gym)
- [Rotation Equivariant Vision Transformers](https://github.com/matthias-weissenbacher/SiT)

## Original Task Description
Train on subsets of generated levels and test on unseen ones to measure true generalization. Explore data augmentation
and inductive biases that improve transfer.

### Tasks
1) Familiarize with a procedural environment like Minigrid [[1]](https://minigrid.farama.org/), ProcGen [[2]](https://github.com/openai/procgen), or, if ambitious, Nethack [[3]](https://github.com/facebookresearch/nle)
2) Train an agent using an RL algorithm like PPO or SAC with an architecture appropriate to the environment (e.g., CNN or
the supposedly especially generalizable Symmetry-Invariant Vision Transformer [[4]](https://openreview.net/attachment?id=SWrwurHAeq&name=pdf) (~70k params)).
3) Evaluate the agent’s generalization performance by training on some levels, testing on others.
4) Experiment with techniques that aim to improve generalization such as data augmentation or regularization methods (e.g.,
dropout, batch normalization) and analyze their impact.

## References
[[1]](https://minigrid.farama.org/) Maxime Chevalier-Boisvert et al.: “Minigrid & Miniworld: Modular & Customizable Reinforcement Learning Environments
for Goal-Oriented Tasks.” NeurIPS (2023).

[[2]](https://github.com/openai/procgen) Karl Cobbe et al.: “Leveraging Procedural Generation to Benchmark Reinforcement Learning.” ArXiv preprint (2019),
available at arXiv:1912:01588.

[[3](https://github.com/facebookresearch/nle) Heinrich Küttler et al.: “The NetHack Learning Environment” NeurIPS (2020). Available
at .

[[4]](https://openreview.net/attachment?id=SWrwurHAeq&name=pdf) Matthias Weissenbacher et al.: “SiT: Symmetry-Invariant Transformers for Generalisation in Reinforcement Learning.”
ArXiv preprint (2024), available at arXiv:2406:15025.

## Requirements
- We need python 3.10.0 otherwise procgen and gym will not run!

## Setup

```bash
git clone https://github.com/Altishofer/deep-reinforcement-learning-uzh.git
```

```bash
cd deep-reinforcement-learning-uzh
```

```bash
python3.10 -m venv venv
```

```bash
source venv/bin/activate
```

```bash
pip install -r requirements.txt
```




