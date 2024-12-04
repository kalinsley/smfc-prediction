# Data
Datasets can be found on [Hugging Face](https://huggingface.co/datasets/adunlop621/Soil_MFC/tree/main).

Both the Stanford MFC and UCSC MFC datasets, along with the trained_models.zip, must be in the same directory must be in the same directory as .ipynb to run the file. Please download the datasets and open the .ipynb file with the files in the same directory. 

trained_models.zip contains multiple types of pretrained models from the original paper, **Towards Deep Learning for Predicting Microbial Fuel Cell Energy Output** It is required to skip the trianing process for the teacher model in our implementation

# Running the Code
The cells can be run in order, one after another, until completion. After ensuring that all download prerequisites have been met, process the trianing dataset. The next section details the model architecture, used by both the Student and Teacher models. The model is a spiking nerural network with na LSTM layer and a linear output layer to readout the outputsfor power, voltage, and current. In the unfrtunate and **very** unlikely case (cough) that you run into an error, rerunning cells from the top of the notebok, after the imports and data preprocessing, will most likely get you back on track. 

Let me know if there are any other issues. 
