# Anomaly Segmentation
Project for 'Machine Learning in Computer Vision' about segmentation with anomalous objects

This repository contains a Colab notebook, together with folders needed to run it properly.
The notebook is meant to be run on Google Colab following the next instructions.

## Setup
- Download from the Virtuale submission page the submitted file: main.ipynb, and images folder.
- Download weights from the following link [here](https://liveunibo-my.sharepoint.com/:f:/g/personal/mattia_gualandi2_studio_unibo_it/Elw7eSBUn6lAmBM6KN308mIBiQmbeXD85AHo1OL6YQxZGA?e=nNsc2s).
- Download data from the following links:
   - [Train and validation](https://people.eecs.berkeley.edu/~hendrycks/streethazards_train.tar)
   - [Test set](https://people.eecs.berkeley.edu/~hendrycks/streethazards_test.tar)
     
   Now put them in a folder called "data".

Once all the files and folders have been downloaded, create a folder called "anomaly_segmentation" in your Google Drive and upload the everything inside it.
The final structure of the created folder must be the following:

anomaly_segmentation/

│   main.ipynb

│

├── images/

│   └── (Contains saved images needed for visualization)

│

├── weights/

│   └── (Contains model weights and saved statistics)

│

└── data/

│   └── (Contains the dataset)

NOTE: Note that data are expected to be uploaded in .tar format, as they are downloaded from the link above. The notebook has a cell to manage the extraction (it takes around 7 minutes).

## Running the Notebook

- Once your environment is set up, simply select **Runtime > Run All** in Colab to execute the entire notebook.
- By default, the notebook doesn't perform training and it runs full inference on the test set using the best model in its best configuration (inference takes approximately 1 hour).

## Configuration Options

- The notebook is designed with the possibility of choosing to train, compute validation metrics, and run inference with different configurations in the ablation section. 
You can:
  - Enable training and validation by changing their respective flags.
  - Perform inference with different settings by modifying the respective flags and configuration within the notebook.

