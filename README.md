# PyTorch Image Classification Project 

Project Overview 🌐
This project classifies architectural styles from images using a pre-trained ResNet-18 model. Built on PyTorch, it provides a complete pipeline from data downloading to classification.

## How to Run the Code 🛠️
1. Input Kaggle Credentials: To download the dataset, you need to input your Kaggle username and API key.

2. Download & Unzip Dataset: The dataset is downloaded and unzipped automatically.
   
3. Data Preparation: Dataset is loaded, resized, and transformed. Data is then divided into training, validation, and testing sets.
   
4. Model Training & Validation: ResNet-18 is used for transfer learning. The model is fine-tuned on the architectural dataset.
   
5. Model Testing: After training, the model is tested on a separate dataset.
   
6. Model Deployment: An interface is provided to upload and classify custom images.
   
7. Extra Features: Fetches architectural style info from Wikipedia.
   
## Code Structure 🗂️
Data Loading: Utilizes PyTorch's ImageFolder and DataLoader.

Model: Uses a pre-trained ResNet-18 model.

Training: Fine-tunes the model.

Testing: Evaluates the model's performance.

Saving & Loading: Model's state is saved and can be re-loaded.

Deployment: Uses ipywidgets for a simple GUI.

