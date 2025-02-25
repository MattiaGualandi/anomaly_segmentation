# Open-World-Semantic-Segmentation-
Project for 'Machine Learning in Computer Vision' about segmentation with anomalous objects
# Anomaly Segmentation

This repository contains a Colab notebook designed to perform anomaly segmentation using a pre-trained model. It is optimized for ease of use, allowing you to quickly set up, run inference, and evaluate performance on test data.

---

## Folder Structure

To get started, organize your Google Drive as follows:

anomaly_segmentation/ │ main.ipynb │ ├── images/ │ └── (Contains input images for inference and visualization) │ ├── weights/ │ └── (Contains pre-trained model weights) │ └── data/ └── (Contains the dataset for testing and validation)


---

## Setup Instructions

1. **Clone the Repository:**  
   Download the Colab notebook (`main.ipynb`) and place it in your Google Drive under the folder `anomaly_segmentation`.

2. **Download Required Files:**  
   - Place all necessary images in the `images` folder.
   - Place the pre-trained model weights in the `weights` folder.
   - Download the dataset and store it in the `data` folder. If the dataset is in `.tar` format, the extraction process will be handled by the notebook (this may take some time). If the data is already extracted, you can safely comment out the extraction cell.

3. **Connect to Colab:**  
   - Open `main.ipynb` on Colab.
   - Mount your Google Drive when prompted, ensuring the directory structure is maintained as shown above.

---

## Running the Notebook

- Once your environment is set up, simply select **Runtime > Run All** in Colab to execute the entire notebook.
- By default, the notebook performs full inference on the test set using the best model.

---

## Configuration Options

- The notebook is designed to allow flexible validation and inference with different configurations. You can:
  - Enable validation by changing the validation flag.
  - Perform inference with different settings by modifying the respective flags within the notebook.

These options are clearly marked in the notebook, allowing you to experiment with different configurations easily.

---

## Notes

- If your dataset is in a compressed `.tar` format, be aware that the extraction process may take some time depending on the size of the data.
- If the data is already extracted, you can **comment out** the extraction cell to save time during execution.

---

## Dependencies

The notebook automatically installs all required dependencies. However, ensure that you are running it on a GPU runtime for optimal performance. To do this:
- Go to **Runtime > Change runtime type** and select **GPU** under hardware accelerator.

---

## Acknowledgments

This project utilizes pre-trained models and datasets for anomaly segmentation. Credits go to the authors of the datasets and models used in this implementation.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the terms of the license.
