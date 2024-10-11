# Design-Pattern-Recognition-using-Large-Language-Models-
  This repository is the replication package for a study about design pattern recognition using large language models (LLMs). 
Replication Instructions for Experiment Results

Overview
This README provides detailed instructions on replicating the experimental results obtained in our study, 
which compares the performance of different large language models (LLMs) for design pattern recognition (DPR).
The replication package containes five ipynb files each for five LLMs (CodeBERT, Code2Vec, CodeGPT, CodeT5, and RoBERTa). 

Experimental Setup
- "Code2vec_word2vec.ipynb: This script produces results for pre-trainig of Code2Vec and fine-tunning using k-NN classification. You can
download our the pre-trained code2vec from https://github.com/sivajeet/DPR-using-code2vec-and-word2vec
This script also includes the findings related with statistical analysis, and different plots. 
- "CodeBERT-knn": This script produce the results for CodeGPT model combined with k-NN classification technique.
This script produce the results for CodeGPT model combined with k-NN classification technique. 
- "CodeGPT-knn": This script produce the results for CodeGPT model combined with k-NN classification technique. 
- "CodeT5-knn": This script produce the results for CodeT5 model combined with k-NN classification technique. 
- "RoBERTa-knn": This script produce the results for RoBERTa model combined with k-NN classification technique. 

Prerequisites
Before replicating the experiments, ensure that the following prerequisites are met:
1. Python installed on your system (version 3.10 or later)
2. Required Python packages installed (NumPy, Matplotlib, scikit-learn, TensorFlow, etc.)
3. See the requirement.txt to install all the necessary packages
4. Access to the datasets folder (design patterns files and non-design patterns files), which includes all the files of five design patterns and files which do not implement any design pattern.
	a). Five folders each for design patterns. Each design pattern folders also have a subfolders, which includes files which donot implement that specific design pattern. 
	b). A file name "non-implemented DP" containes files which donot implement any design pattern. 
	

Replication Steps
Follow these steps to replicate the experiments:

Step 1: Clone the Repository
Clone the repository to your local machine:

Step 2: Navigate to the Scripts Directory
Navigate to the directory containing the five scripts:
cd scripts

Step 3: Install packages from requirement.txt

Step 4: Run Script 1
Execute `CodeBERT-knn.ipynb` to reproduce the results for CodeBERT:
Execute `CodeGPT-knn.ipynb` to reproduce the results for CodeGPT:
Execute `CodeT5-knn.ipynb` to reproduce the results for CodeT5:
Execute `RoBERTa-knn.ipynb` to reproduce the results for RoBERTa:
Execute `Code2vec_word2vec.ipynb` to reproduce the results for Code2Vec:



Step 5: Analyze Results
After running all scripts, analyze the results generated for each models. 
Compare the performance metrics obtained from scripts to evaluate the effectiveness of LLMs.

Contact Information
For any questions or assistance regarding the replication process, feel free to contact:
Sushant Kumar Pandey (sushantk@chalmers.se, s.k.pandey@rug.nl)
Sivajeet Chand (sivajeet@student.chalmers.se)

