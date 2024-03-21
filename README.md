# ReqBrain 

This GitHub project contains all the necessary documents, files and scripts for replicating **Requirement Brain (ReqBrain)**.<br><br>
***NOTE:*** 
- Notebooks runing the models require a GPU with minimum of 32GB GPU memory to load the model!
- The sizes of the trained models are big. Therefore, the five trained models are provided on the [Hugging Face](https://huggingface.co/REELICIT) project of ReqBrain. For training scripts and the **direct link to each trained model visit** **training_scripts**<br><br>
A description of each above listed directories is provided below. For all directories, see directory README for more description.<br>


1. **instruct_datasets:** contains training and evaluation sets in three format. Different LLM models require data in different formats.
2. **training_scripts:** contain three scripts and logs generated during training in ```.ipynb``` format. Five notebooks, one per trained model in the paper.
3. **evaluation_scripts:** contains all scripts for numarical evaluation used for **RQ1** and figures.
4. **inferencing_all_trained_models:** contains all resutls for **RQ 2, 3, 4** for the experiment.  
