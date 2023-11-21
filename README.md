### This is the code for paper "Interpretable Dual-Branch EMGNet: A Transfer Learning-based Network for Inter-Subject Lower Limb Motion Intention Recognition" (EAAI-23-6594, Under Review). We provide the proposed CNN-EMGNets and IDB--EMGNets, as well as the implementation of machine learning models and deep learning models for comparison.
### Install: 
Install the required dependencies using "pip install requirements.txt".
### Usage:
1. Run the environmentTest.ipynb file to check that the required dependencies are correctly installed.
2. Run the dataPreprocessing.ipynb file to convert the UCI dataset into training and test sample sets in .npz format.
3. Run the modelComplexityVisualization.ipynb file to obtain model parameters and FLOPs, and visualize model.
4. Run the modelTrain_ComparedDLModels.ipynb file and the modelTrain_ComparedMLModels.ipynb file to conduct the training and testing of the comparison models.
5. Run the modelTrain_Intra_Subject.ipynb file and the modelTrain_Inter_Subject.ipynb file to conduct the training and testing of CNN-EMGNets and IDB-EMGNets in Intra-S and Inter-S-TL scenarios.