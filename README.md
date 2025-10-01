# DeepReinforcementLearning-ProcGen-Generalization

## Setup
```bash
python3.10 -m venv venv
```
```bash
source venv/bin/activate
```
```bash
git clone https://github.com/Altishofer/deep-reinforcement-learning-uzh.git
```
```bash
cd deep-reinforcement-learning-uzh
```
```bash
pip install -r requirements.txt
```
```bash
python -m procgen.interactive --env-name coinrun
```

## ProcGen Repository
https://github.com/openai/procgen?tab=readme-ov-file

## Original Task

Generalization in Procedurally Generated Environments
Train on subsets of generated levels and test on unseen ones to measure true generalization. Explore data augmentation
and inductive biases that improve transfer.
Tasks:
Familiarize with a procedural environment like Minigrid [1], ProcGen [2], or, if ambitious, Nethack [3].
Train an agent using an RL algorithm like PPO or SAC with an architecture appropriate to the environment (e.g., CNN or
the supposedly especially generalizable Symmetry-Invariant Vision Transformer [4] (~70k params)).
Evaluate the agent’s generalization performance by training on some levels, testing on others.
Experiment with techniques that aim to improve generalization such as data augmentation or regularization methods (e.g.,
dropout, batch normalization) and analyze their impact.

References:
[1] Maxime Chevalier-Boisvert et al.: “Minigrid & Miniworld: Modular & Customizable Reinforcement Learning Environments
for Goal-Oriented Tasks.” NeurIPS (2023). Available at https://minigrid.farama.org/.
[2] Karl Cobbe et al.: “Leveraging Procedural Generation to Benchmark Reinforcement Learning.” ArXiv preprint (2019),
available at arXiv:1912:01588 and https://github.com/openai/procgen.
[3] Heinrich Küttler et al.: “The NetHack Learning Environment” NeurIPS (2020). Available
at https://github.com/facebookresearch/nle.
[4] Matthias Weissenbacher et al.: “SiT: Symmetry-Invariant Transformers for Generalisation in Reinforcement Learning.”
ArXiv preprint (2024), available at arXiv:2406:15025.
