# Training Scripts

This directory contains the training scripts used to train our models.

- Running and loading models require GPU with a minimum of 32GB GPU memory.
- Links to open on google colab are provided at top of each notebook.
- One training script per model; total of five, is provided and each script is named after the model it tunes.
- The training scripts are built using Jupyter Notebooks with guides for understanding and training logs are included.
- Rerunning the notebooks will clear the previous logs.

# Resulting Models

The trained models are pushed to **Hugging Face** API.

| Training Script | Corresponding Trained Model on Hugging Face Hub |
|-----------------|-----------------------------|
| [train_falcone-base.ipynb](https://github.com/REELICIT/reqbrain_rep_package/blob/main/training_scripts/train_falcone-base.ipynb)               | [falcon-7b-ReqBrain](https://huggingface.co/REELICIT/falcon-7b-ReqBrain)                           |
| [train_falcone-instruct.ipynb](https://github.com/REELICIT/reqbrain_rep_package/blob/main/training_scripts/train_falcone-instruct.ipynb)               | [falcon-7b-instruct-ReqBrain](https://huggingface.co/REELICIT/falcon-7b-instruct-ReqBrain)                           |
| [train_llama2.ipynb](https://github.com/REELICIT/reqbrain_rep_package/blob/main/training_scripts/train_llama2.ipynb)               | [Llama-2-7b-chat-hf-ReqBrain](https://huggingface.co/REELICIT/Llama-2-7b-chat-hf-ReqBrain)                           |
| [train_mistralai.ipynb](https://github.com/REELICIT/reqbrain_rep_package/blob/main/training_scripts/train_mistralai.ipynb)               | [Mistral-7B-Instruct-v0.2-ReqBrain](https://huggingface.co/REELICIT/Mistral-7B-Instruct-v0.2-ReqBrain)                           |
| [train_zephyr.ipynb](https://github.com/REELICIT/reqbrain_rep_package/blob/main/training_scripts/train_zephyr.ipynb)               | [zephyr-7b-beta-ReqBrain](https://huggingface.co/REELICIT/zephyr-7b-beta-ReqBrain) |
