# Comment_toxicity
This repository contains a machine learning model designed to detect toxic comments. The model is trained on a dataset of comments labeled with various levels of toxicity and can be used to classify new comments as toxic or non-toxic. Additionally, the repository includes a Gradio-based web interface for testing the model.

# Usage
The main component of this repository is:

1. comment_toxicity_model.ipynb: Jupyter notebook for training the comment toxicity model and creating a Gradio web interface to test the model.
2. data/: Directory containing the dataset used for training the model.

# Running the Notebook
1. Open the Notebook:
   Open comment_toxicity_model.ipynb in Jupyter Notebook.

2. Train the Model:
   Follow the instructions in the notebook to train the model on the provided dataset. The notebook will guide you through data preprocessing, model training, and evaluation.

3. Test the Model with Gradio:
   At the end of the notebook, you will find cells to create and run a Gradio web interface for testing the model. Run these cells to start the web interface, which will be accessible via a local URL.

# Model Training
The comment_toxicity_model.ipynb notebook covers the following steps:

Data Loading: Load the dataset containing comments and their toxicity labels.
Data Preprocessing: Clean and preprocess the text data for model training.
Model Definition: Define a neural network architecture for toxicity classification.
Model Training: Train the model using the preprocessed data.
Model Evaluation: Evaluate the model's performance on a validation set.

# Gradio Web Interface
The comment_toxicity_model.ipynb notebook provides a user-friendly web interface for testing the trained toxicity model. Gradio is used to create the interface, which allows users to input a comment and get a toxicity prediction.

To run the Gradio interface:

1. Ensure the model is trained and saved.
2. Run the cells at the end of the notebook.
3. A local URL will be provided. Open this URL in your web browser to use the interface.





This README file provides an overview of the repository, including instructions for installation, usage, model training, and running the Gradio web interface. If you have any questions or need further assistance, feel free to open an issue in the repository.






