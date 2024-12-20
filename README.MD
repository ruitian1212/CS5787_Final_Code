# CS 5787 Final Project Code

This repo is the code for our final project for the course CS 5787 Deep Learning. Our topic is to build a multimodal system to answer Medical Visual Question. We are aiming at building a generative system that could be open to open-ended medical questions. The code are put as jupyter notebook format so that you can play with it interactively. In total, there are four notebooks:

1. *data_preprocessing.ipynb*: The notebook is used to pre-process the PMC-VQA dataset and sample data. You don't have to run it. The processed data is stored in train_df_sample.csv, test_df_sampled.csv and sampled_images.zip. The zip file can be downloaded via the link: https://drive.google.com/file/d/1VNuGNLi3LSZ22VgD77NlrUhgh_BWgEEK/view?usp=sharing First unzip the image folder and then you can play with the remaining notebooks.
2. *Graph.ipynb*: The notebook is used to generate some EDA graphs for the dataset.
3. *Pilot_Test_Model.ipynb*: This notebook is used to conduct pilot test of the model on the VQA-RAD dataset. 
4. *BioGPT_Model_on_PMC_VQA.ipynb*: This is the main notebook for the project. You can follow the annotations in the notebook to run it step by step. To change the ablations of the model, just change the parameters under "Ablation Configurations" to the parameters you would like to test on and you can different model results.

Please let us know if you are unclear with any of the codes!