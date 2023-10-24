# Prithvi-HLS-Finetuning
This repo acts as an example guide for training the Prithvi HLS Foundation model using sentinel2 imagery and well pad segmentation masks.

The guide consists of three Google Colab Notebooks that walk through the entire process of fine-tuning the model to automatically identify oil well pads. The goal of this project is not to achieve high performance on the well pad task, but to serve as a boiler plate for implementing other segmentation tasks.

## Generating Training and Validation Data
The first notebook walks through data creation phase. It can be accessed here: https://colab.research.google.com/drive/1VEJOpyeTJeYSX8EcINe1m7lA-Bi7YoqU?usp=sharing

## Creating configuration file
The second notebook walks through the process of creating a config file which is essential for fine-tuning. It can be accessed here: https://colab.research.google.com/drive/1cOU_JG73dsLmAx4B9yr3tmTvflx0AJ9I?usp=sharing

## Fine-tuning on the data
The last notebook goes through the process of actually fine-tuning the HLS Prithvi model using the generated dataset and config file. It can be accessed here: https://colab.research.google.com/drive/1pPhGt9x3p6KVXG4oIUc9y-sqPcaevFbq?usp=sharing
