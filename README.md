# Text-Summarization-using-RNN-T5-Transformer-and-BART-using-CNN-Dataset


This project explores various deep learning approaches for automated text summarization, implementing and comparing different neural architectures including RNNs and Transformers. Our goal is to generate concise, meaningful summaries while preserving the core message of longer texts.
# Project Components
# Transformer-Based Models

Transformer/Custom_Transformer_Model.ipynb: Implementation of a purpose-built Transformer architecture
Transformer/T5_implementation.ipynb: Fine-tuning and evaluation of T5 for summarization
Transformer/Bart_Implementation.ipynb: Fine-tuning and evaluation of BART
Transformer/BART_T5_GRAPH.ipynb: Performance visualization and comparative analysis

# RNN-Based Models

RNN/RNN_Model.ipynb: GRU-based sequence processing implementation
RNN/RL_RNN_Implementation.ipynb: Enhanced RNN with reinforcement learning optimization

# Architecture Details
#Custom Transformer
Our custom implementation leverages multi-head attention mechanisms to capture contextual relationships within the text, offering improved performance over traditional sequential models.
#Pre-trained Models
We utilize transfer learning through T5 and BART models, adapting their pre-trained knowledge to our summarization task. This approach significantly reduces training time while maintaining high-quality output.
#RNN Variants
The project includes both standard GRU-based implementations and an innovative hybrid approach combining RNNs with reinforcement learning to optimize summary generation through feedback-driven improvement.


#Clone the repository

#Dataset Setup:


Download the CNN/DailyMail dataset from Kaggle
Place the dataset in DLProject/ within your Google Drive


# Access Model Checkpoints:


Transformer Checkpoints
RNN Checkpoints

# Running the Models
Transformer Models
# Navigate to the Transformer directory and run the desired implementation:

Custom_Transformer_Model.ipynb: Custom architecture
T5_implementation.ipynb: T5-based implementation
Bart_Implementation.ipynb: BART-based implementation
BART_T5_GRAPH.ipynb: Performance analysis

# RNN Models
Access the RNN implementations in the RNN directory:

RNN_Model.ipynb: Base GRU implementation
RL_RNN_Implementation.ipynb: Reinforcement learning enhanced version

# Note
Model checkpoints are stored separately due to size constraints.
