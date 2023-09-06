# Summer Camp 2023

## Installation

You can run the notebook in Google Colab or [locally](#run-locally).

# Run the notebooks in Google Collab

## Day 1

### Technical

Run the notebook in Google Colab:
1. [Exercise 1 Pytorch Introcution](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_1_numpy_to_pytorch.ipynb)
2. [Exercise 2 Optimization](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_2_optimization.ipynb)
3. [Exercise 3 Einops Basics](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_3_einops-basics.ipynb)
4. [Exercise 4 Einops for Deep Learning](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_4_einops-for-deep-learning.ipynb)
5. [Exercise 5 Bonus Hyperparameters](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_5_bonus_hyperparameters.ipynb)

### Conceptual

[Presentation](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/conceptual/1._Introduction_to_AI_Safetyy.pdf)

### Governance

[Presentation](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/governance/1.Introduction_to_AIS_and_AI_Gov.pdf)

## Day 2

1. Theory Reinforcement Learning: [overleaf](https://www.overleaf.com/read/gtbwdmkgkpjq) | [pdf](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/day02/theory_1_RL_Lecture_Swiss_AI_Safety_Camp-2.pdf) | [book reference](https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf)
2. Exercice Deep Q Learning: [google colab](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day02/ex_1_reinforcement_q_learning.ipynb)
3. Exercice Policy Gradient: [google colab](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day02/ex_2_Policy_Gradient_with_Cartpole_and_PyTorch.ipynb)

## Day 3

To be announced

## Run locally

If you want to run them locally, you can clone the repository

```bash
git clone https://github.com/Swiss-AI-Safety/swiss-summer-camp-23.git
cd swiss-summer-camp-23
conda create --name SAIS python=3.9 -y
conda activate SAIS
conda install pytorch torchvision torchaudio cpuonly -c pytorch -y
pip install -r requirements.txt
```