# ReqBrain 

This GitHub project contains all the necessary documents, files and scripts for replicating **Requirement Brain (ReqBrain)**.<br><br>

## NOTE:
- Loading and using models require a GPU with minimum of 32GB GPU memory to load the model!
- ReqBrain. Our trained models are quite large, each around 35 GB in size. To make accessing these models as easy as possible, we've hosted all five of them on the ReqBrain project's [Hugging Face](https://huggingface.co/REELICIT) page. This allows for seamless downloading and integration into Hugging Face echo system and our scripts provided here.



## Directories Description:
A description of each above listed directories is provided below. For all directories, see directory README for more description.<br>
1. **instruct_datasets:** contains training and evaluation sets in three format. Different LLM models require data in different formats.
2. **training_scripts:** contain three scripts and logs generated during training in ```.ipynb``` format. Five notebooks, one per trained model in the paper.
3. **evaluation_scripts:** contains all scripts for numarical evaluation used for **RQ1** and figures.
4. **inferencing_all_trained_models:** contains all resutls for **RQ 2, 3, 4** for the experiment.  
