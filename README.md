ChemBERTa and ML for NSP15 Inhibition Prediction:

This repository provides a full pipeline for predicting the inhibition of the NSP15 protein through the use of machine learning models, ChemBERTa embeddings, and ChatGPT-based prompt engineering

Key Features


Dataset:
The dataset (SMILES-DATA.csv) includes SMILES strings labeled with binary values:
0: Non-inhibitory compounds
1: Inhibitory compounds 

How to Use:

Dataset

1-Utilize the SMILES-DATA.csv file for training and evaluating the model.
Fine-Tuning ChemBERTa
2-Execute Finetuning_ChemBERTa.ipynb to fine-tune the ChemBERTa model on the dataset.
Model Training and Embedding
3- Use ChemBERTa_and_ML.ipynb to create embeddings and train the models.
Pre-Trained Checkpoints
4- Load the pre-trained checkpoints from the ml-checkpoints/ folder using ML_models_playground.ipynb.
Prompt Engineering with ChatGPT

Requirements:

Python 3.8+
Libraries:
PyTorch
Transformers (for ChemBERTa)
scikit-learn
pandas
Jupyter Notebook
OpenAI API (for ChatGPT prompt engineering)




