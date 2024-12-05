
# Bicyclist Detection

## Overview
The `main.ipynb` notebook processes and visualizes a dataset of cyclist images. It includes exploratory data analysis and model training using YOLO for object detection. Sample images can be uploaded and will be outputted with a box around the cyclist.

## Contents
1. **Dataset Gathering**: 
   - Utilizes Kaggle to download the cyclist dataset from https://www.kaggle.com/datasets/semiemptyglass/cyclist-dataset.
   - Organizes image and label files.

2. **Exploratory Data Analysis (EDA)**:
   - Counts and analyzes the distribution of image and label files.
   - Visualizes sample images and dataset statistics.

3. **Model Training**:
   - Implements YOLO for object detection.
   - Processes and prepares data for training.

4. **Visualization**:
   - Displays model predictions on test images.
   - Compares ground truth with model results.

5. **Video Test**:
   - Converts a video into individual frames
   - Runs the model on each frame
   - Creates a version of each frame with a bounding box that the user can convert to a video using a video processing program such as iMovie.

## Prerequisites
- Python 3.x
- Required libraries: `cv2`, `kagglehub`, `ultralytics`, and `matplotlib`

## Usage
1. Clone this repository or download the notebook.
2. Install the required dependencies.
3. Run the notebook step-by-step to process the dataset and train the YOLO model. 

## Notes
- The best.pt file is from 37 epochs of the model running. Greater accuracy can be achieved with more runs.

## Implementation Video
- A video of the model interacting with a video can be found [here](https://drive.google.com/file/d/126zKxap-N844K6GeLGoprixmJ5ZqybRC/view?usp=sharing)
