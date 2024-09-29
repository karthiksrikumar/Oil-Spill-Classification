# Oil Spill Detection from Satellite Images

## About the Dataset
Source: https://www.kaggle.com/datasets/sudhanshu2198/oil-spill-detection/data
The dataset used in this project is derived from satellite images of the ocean, specifically designed to identify oil spills. The dataset comprises images that either contain oil spills or do not, making it essential for training models to detect such environmental hazards.

### Dataset Details
- **Source**: Satellite images of the ocean.
- **Classes**:
  - **Non-Spill**: Represents the negative case, or the majority class.
  - **Oil Spill**: Represents the positive case, or the minority class.

### Data Processing
The images were split into sections, and each section was processed using computer vision algorithms. These algorithms helped extract features that describe the contents of each image section or patch. The outcome of this image processing is a fixed-length feature vector for each suspicious region, which serves as the input for classification tasks.

### Objective
The primary goal of this project is to predict whether a given patch of a satellite image contains an oil spill based on the feature vectors derived from image processing. This task is crucial for addressing illegal or accidental oil dumping in oceans, aiding in environmental protection efforts.

## Features
- Each image patch is transformed into a feature vector that captures relevant characteristics for classification.
- The model aims to distinguish between spill and non-spill regions effectively.

## Methodology
1. **Image Processing**: Techniques are applied to derive feature vectors from satellite images.
2. **Classification Model**: Machine learning algorithms are trained on the feature vectors to classify the regions into spill or non-spill categories.

## Usage
To utilize this dataset and the corresponding classification models, follow the steps below:

1. **Installation**: Ensure you have the required libraries installed. Use the following command to install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. **Running the Model**: After setting up the environment, you can run the model training and evaluation scripts. Adjust any parameters as necessary in the configuration files.
