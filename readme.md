# Torso Bounding Box Prediction Project

This project aims to build a model that can identify the torso in images and draw bounding boxes around it to localize the object. The dataset used for this project is the Frames Labeled In Cinema (FLIC) dataset.

## Project Structure

- `images/`: Directory containing the image dataset.
- `bbox.csv`: CSV file containing image filenames and corresponding bounding boxes.
- `torso_prediction.ipynb`: Jupyter Notebook with the Python code for the project.
- `best_model.h5`: The trained model's weights (to be generated during training).
- `README.md`: This README file.

## Usage
Follow the instructions in the Jupyter Notebook to train and evaluate the model on your dataset.

## Results
The trained model will be saved as best_model.h5, and you can use it to make predictions or further fine-tune it if needed.