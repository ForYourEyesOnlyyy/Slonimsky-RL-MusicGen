# Slonimsky-RL-MusicGen
Advanced music generation with transformer-based model under Slonimsky Thesaurus guidence

## Setup
Clone the repo, set up the environment, and intall the requirements: 
```bash
git clone https://github.com/ForYourEyesOnlyyy/Slonimsky-RL-MusicGen
cd Slonimsky-RL-MusicGen

conda create --name slon_gen python=3.12
conda activate slon_gen
pip install -r requirements.txt
```

## Motivation
WIP

## Method
Our approach is multistage:
- Backbone model 
  - We choose an opensource pre-trained finetuning model that would serve as a backbone
- Rule Formulation
- Policy Optimization fine-tuning