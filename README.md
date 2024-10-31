# Data Mining

## Overview

This Jupyter notebook contains the solution for Programming Assignment 1 of the
Data Mining course. The assignment focuses on data preparation and understanding
using the Stanford Dogs dataset and a tweet dataset.

## Contents

1. Stanford Dogs Dataset Processing

   - Image cropping and resizing
   - Feature extraction (Edge histograms)
   - Histogram of Oriented Gradient (HOG) feature descriptor
   - Dimensionality reduction using PCA

2. Tweet Dataset Processing
   - Text feature extraction using CountVectorizer and TfidfVectorizer
   - Dimensionality reduction and visualization

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, scikit-image, scikit-learn, PIL

## Setup

1. Clone this repository or download the Jupyter notebook.
2. Ensure you have the required Python libraries installed. You can install them
   using pip:

   ```bash
   pip install numpy pandas matplotlib scikit-image scikit-learn pillow
   ```

3. Download the Stanford Dogs dataset and place it in a folder named "Dataset"
   in the same directory as the notebook.
4. Download the assigned tweet dataset (train.json) and place it in the same
   directory as the notebook.

## Usage

1. Open the Jupyter notebook in Jupyter Lab or Jupyter Notebook.
2. Run the cells in order from top to bottom.
3. Observe the output, including visualizations and printed results.

## File Structure

- `Assignment_1.ipynb`: The main Jupyter notebook containing all the code and
  explanations.
- `Dataset/`: Folder containing the Stanford Dogs dataset (not included in the
  repository).
- `train.json`: The tweet dataset file (not included in the repository).

## Notes

- Make sure to update the file paths if your dataset locations differ from the
  default structure.
- Some cells may take a while to run, especially those involving image
  processing and PCA.
