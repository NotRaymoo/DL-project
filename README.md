# DL-project

Deep Learning model that classifies patients according to their likelihood of having diabetes based on various features. The selected dataset was sourced from the United States National Institute of Diabetes and Digestive and Kidney Diseases, which can be found online via this link: https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset.

## Recreating the Model

The most important notebook is final_model.ipynb, which contains the final round of hyperparameter testing on the 2-layer neural network as well as the training and testing of the final model itself.

To train the model, first ensure that the "diabetes_clean.csv" file is in the same directory as the "final_model.ipynb" notebook, then run the cells in the "Imports", "Load Dataset", "Setting Up Models", "Setting Up Trainer" and "Training Final Model" section.  

To load and test the trained model, make sure the cells in the "Imports", "Load Dataset" and "Setting Up Models" sections have been run, then run the cells in the "Loading the model" and "Testing the loaded model" sections. 

The final notebook has the following dependencies: matplotlib, numpy, pandas, torch, torchmetrics. Specifically, it was tested with the following versions: matplotlib v3.8.2, numpy v1.23.1, pandas v1.4.3, torch v2.2.0, torchmetrics v1.3.1 and Python 3.10.0. 

## Subdirectories

The remaining subdirectories contain various notebooks with the parts done by each member.
- The notebook in the "chien" folder contains the work done for Chien Shyong's 3-layer and 4-layer neural networks.
- The notebook in the "kh" folder contains the work done for Keng Hoy's 2-layer and 5-layer neural networks.
- For the "miran" folder, layer1.ipynb contains the work done for Mi Ran's 1-layer neural network, layer5.ipynb for her 6-layer neural network, and SOTA_models.ipynb contains the training and testing of the state-of-the-art models. 
