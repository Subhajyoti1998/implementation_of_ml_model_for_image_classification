# Implementation of ML Model for Image Classification

This project is an interactive Image Classification Dashboard built using Streamlit, leveraging the power of a pre-trained ResNet-50 model. The dashboard enables users to upload images, view classification predictions, and understand the reasoning behind the predictions with interpretability tools.

## Features

Image Upload: Users can upload images in .jpg, .jpeg, or .png formats.

Top Predictions: Displays the top 5 predicted categories along with their probabilities using a horizontal bar chart.

Model Interpretability: Utilizes Captum's IntegratedGradients to highlight regions of the image contributing to the predictions.

Interactive Interface: Built with Streamlit for ease of use and real-time interaction.

## Technologies Used

Streamlit: For creating the interactive web-based dashboard.

PyTorch: For leveraging the pre-trained ResNet-50 model.

Captum: For model interpretability and feature importance visualization.

Matplotlib: For visualizing the top predictions.

## Installation

Follow these steps to set up and run the project locally:

Clone the Repository:

git clone https://github.com/your-repo/image-classification-dashboard.git
cd implementation_of_ml_model_for_image_classification-main

## Install Dependencies:
Create a virtual environment and install the required packages.

pip install -r requirements.txt

## Run the Application:
Launch the Streamlit app.

streamlit run image_classif_dash.py

## Access the Dashboard:
Open your browser and navigate to the local server URL (e.g., http://localhost:8501).

## Usage
Launch the application and upload an image using the "Upload Image" button.
View the top 5 predictions for the uploaded image displayed in a bar chart.
Explore the feature importance visualization to understand the model's decision-making process.

Snapshots

## Dashboard Interface

The main interface where users can upload images and view results.

## Top Predictions Visualization

A bar chart displaying the top 5 predictions for the uploaded image.

## Feature Importance Visualization

A heatmap overlay showing regions of the image most influential in classification.

## Future Work

Expand model support to include advanced architectures like Vision Transformers.

Enhance the UI with batch processing and video classification capabilities.

Deploy on cloud platforms for real-time applications.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

PyTorch: For providing the ResNet-50 model and associated tools.

Captum: For feature importance and model interpretability.

Streamlit: For making the development of interactive dashboards seamless.
