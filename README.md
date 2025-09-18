# Low-Resource MT Bias

This repository contains the code and resources for my MSc dissertation project: **Bias in AI Translation Models for Low-Resource Languages**.  
The project evaluates how machine translation models handle underrepresented languages (e.g., Bemba, Swahili) and explores techniques such as LoRA adaptation and data augmentation.

## Features
- Preprocessing scripts for low-resource parallel data  
- Training configurations for baseline and adapted NLLB models  
- Evaluation scripts using BLEU, chrF, ROUGE-L, and TER  
- Example notebooks for analysis and reproducibility  

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/ninesowngoal/low-resource-mt-bias.git
cd low-resource-mt-bias
pip install -r requirements.txt
