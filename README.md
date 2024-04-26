 # Space Debris Detection, Tracking, and Impact Analysis 

 # Project Overview

This project aims to develop a comprehensive method for detecting, tracking, and analyzing space debris to improve the safety and sustainability of space activities. We use machine learning algorithms such as LSTM and Gradient Boosting Decision Trees (GDBT) to analyze Two-Line Element (TLE) data from Space-Track.org and the UCS Satellite Database.

# Technologies and Libraries Used

Python: Primary language for data analysis and machine learning.

TensorFlow: For building and training LSTM models.

Scikit-learn: Used for implementing GDBT models and other machine learning algorithms.

PyKalman: Provides implementation of Kalman Filters for state estimation and prediction.

Pandas: Facilitates data manipulation and analysis.

NumPy: Used for numerical computations and data processing.

Matplotlib: For creating visualizations and plots.

Seaborn: Used for creating informative and attractive statistical graphics.

Scipy: Utilized for scientific computing and signal processing.

Skyfield: Used for calculating positions and velocities of celestial objects.


# Installation

Clone the repository to your local machine to get started with the analysis:

git clone https://github.com/KVB02/Space-Debris-Detection-Tracking-and-Impact-Analysis.git

Install the required Python libraries by running:

pip install -r requirements.txt

Open the Jupyter notebook in your preferred environment or Jupyter Notebook for an integrated experience.


# Usage

Begin with data preprocessing to load and clean the dataset. Merge the TLE data from Space-Track.org and the UCS Satellite Database, and extract relevant features such as orbital periods, apogee and perigee distances, and inclination. Clean and preprocess the features by handling missing values and converting data types. Organize the data in chronological order to prepare it for modeling. Implement LSTM and GDBT models to predict space debris trajectories, and review model performance metrics and visualize results to gain insights into space debris behavior. Each step is documented within the notebook for clarity and ease of understanding.



# Notebook Overview

This project consists of Jupyter notebooks that guides you through each analytical phase, from data loading and preprocessing to implementing LSTM and GDBT models for predicting space debris trajectories.

# Note

Please note that you will need to download the TLE datasets from Space-Track.org after creating a valid account. The datasets are not included in this repository due to licensing restrictions.



# Contributing

We welcome contributions to enhance the project's scope or improve its methodology. Please see the contributing guidelines for more details.

# License

This project is licensed under the MIT License. See the LICENSE file in the repository for more information.

