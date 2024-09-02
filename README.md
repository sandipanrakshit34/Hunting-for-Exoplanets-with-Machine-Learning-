# Hunting-for-Exoplanets-with-Machine-Learning

<center> <img src = "https://c.tenor.com/3zb7e2Hb9f4AAAAC/galaxy-stars.gif" width = 100%>
## Project Overview
The "Hunt for Exoplanets using Machine Learning" project aims to identify potential exoplanets from a large dataset of stellar observations. Using machine learning techniques, this project analyzes light curves—graphs of light intensity over time—to detect the subtle dimming that indicates an exoplanet passing in front of a star. This project employs a Random Forest classifier to distinguish between exoplanet candidates and non-exoplanets (false positives), achieving high accuracy in the predictions.

## Technologies Used
- **Programming Language:** Python
- **Libraries/Frameworks:**
  - TensorFlow
  - Scikit-learn
  - Pandas
  - Numpy
  - Matplotlib
- **Dataset:** [Kepler Labeled Time Series Data](https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data?resource=download&select=exoTest.csv)

## Dataset
The dataset used in this project is sourced from Kaggle and contains time series data from the Kepler Space Telescope. The dataset includes labeled instances indicating the presence of exoplanets. You can download the dataset from [here](https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data?resource=download&select=exoTest.csv).

## Project Structure
- **data/**: Directory containing the dataset files.
- **notebooks/**: Jupyter notebooks used for data exploration, preprocessing, and model development.
- **src/**: Source code for the project, including the implementation of the Random Forest classifier.
- **models/**: Saved models for future use and analysis.
- **README.md**: Project documentation.

## How It Works
1. **Data Preprocessing:** The raw time series data is cleaned and preprocessed using Pandas and Numpy. Features such as mean, variance, and skewness of the light curves are extracted to serve as inputs to the model.
2. **Model Training:** A Random Forest classifier is trained on the preprocessed dataset to classify instances as either exoplanets or non-exoplanets.
3. **Model Evaluation:** The trained model is evaluated using metrics like accuracy, precision, recall, and F1 score to ensure its effectiveness in identifying exoplanets.

## Results
The Random Forest classifier achieved an F1 score of 0.89, indicating a strong ability to balance precision and recall in identifying exoplanet candidates from the dataset.

## Conclusion
The project demonstrates the effectiveness of machine learning techniques, specifically the Random Forest classifier, in identifying exoplanets from stellar observation data with high accuracy.

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/sandipanrakshit34/hunt-for-exoplanets.git
