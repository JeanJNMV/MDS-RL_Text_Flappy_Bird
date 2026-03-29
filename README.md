# RL for Text Flappy Bird environment

This repository's primary deliverable is the Jupyter notebook that implements and evaluates simple reinforcement learning agents for a text-based Flappy Bird environment.

**Quick links:**
- Notebook: [TFB_MCSarsa_MARTINI.ipynb](TFB_MCSarsa_MARTINI.ipynb)
- Report: [report/report.pdf](report/report.pdf)
- Dependencies: [requirements.txt](requirements.txt)

## Overview

- `TFB_MCSarsa_MARTINI.ipynb`: the main notebook with implementations and experiments for Monte Carlo Control and SARSA.
- `report/`: LaTeX source and output files for the accompanying report.

>Note: the text-based Gym environments used for experiments are available at: https://gitlab-research.centralesupelec.fr/stergios.christodoulidis/text-flappy-bird-gym.

## Getting started

```bash
python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

git clone https://gitlab-research.centralesupelec.fr/stergios.christodoulidis/text-flappy-bird-gym.git
cd text-flappy-bird-gym
pip install -e .
```

## Author

- **Jean-Vincent Martini** - CentraleSupélec