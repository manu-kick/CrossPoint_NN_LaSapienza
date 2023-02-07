# CrossPoint_NN_LaSapienza
A Pytorch Lightning reimplementation of CrossPoint: Self-Supervised Cross-Modal Contrastive Learning for 3D Point Cloud Understanding (CVPR'22)
Link to the paper -> https://arxiv.org/abs/2203.00680

## Dependencies
Refer to the requirements.txt file


## How to Use
Note: In the following guide we are supposing you would run the code on colab as we did, then it's likely that you will have errors regarding path;
To avoid errors be sure to have this exactly path as soon as you give access Colab to Drive: "content/drive/MyDrive/Cross_Point_Sapienza_NN_23/"

Here you find all the first step to download configure and run the code to train the models or to use our pretrained model

- clone repository from GitHub: git clone https://github.com/manu-kick/CrossPoint_NN_LaSapienza.git
- download the datasets used in our experiment from this link https://drive.google.com/drive/folders/15aYNCSQAiCNuluOJEUUMP3SBalsqrUCL?usp=sharing
- insert the all the folders downloaded in the 'data' folder in the root of the repo have(you should have the following folders: modelnet40_ply_hdf5_2048, ScanObjectNN, ShapeNet, ShapeNetRendering), make sure to unzip the files
- then you can upload everything on drive, you must call the root repo folder with the following name: "Cross_Point_Sapienza_NN_23"


## Train the model you like
You can open the V3_train_custom_lightning.ipynb to train the models, you will find details instrunction inside that file


## Pretrained model
Here you find our pretrained model
//TODO -> tabella con i link delle diverse combinazioni

## Evaluate the models

## Our report
You find at this link the report generated with Wandb in which we discuss some observation about the experiments.

## Acknowledgements
Our code borrows from:
- the crosspoint paper repository https://github.com/MohamedAfham/CrossPoint that borrows from DGCNN
- the PCT implementation repository https://github.com/qinglew/PointCloudTransformer/tree/2212086a6cce42b9652ff25b7e2aaf06f9b2e1a5