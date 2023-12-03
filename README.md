# Enhanced EMG Signal-Based Classification Framework for Robot-Assisted Rehabilitation Therapy

## Overview

This repository contains an enhanced classification framework utilizing Electromyography (EMG) signals for the classification of physical actions in the context of robot-assisted rehabilitation therapy. The framework incorporates an improved methodology, leveraging the K-Nearest Neighbors (KNN) algorithm, to classify EMG signals and aid in the control of supportive robotics for rehabilitation purposes.

## Project Structure

The project is structured as follows:

- `EMGPhysicalActionDataSet`: Contains sample EMG signal datasets used for training and testing.
    - `readme.txt`: Additional documentation, including research papers, references, and guides.
- `main.ipynb`: Holds the source code for the classification framework.
    - `Preprocessing (Task 1 -4)`: Code for data preprocessing and feature extraction from EMG signals.
    - `Analysis`: Implementation of the KNN algorithm for classification; Scripts for evaluating model performance and generating metrics.
- `README.md`: This file providing an overview of the project.

## Setup Instructions

### Requirements

- Python 3.x
- NumPy, Pandas, SciPy: Python libraries for data manipulation and analysis.
- Scikit-learn: Machine learning library providing implementations of the KNN algorithm.
- Jupyter Notebook (optional): For exploring data and running code interactively.

### Installation

1. Clone the repository: `git clone https://github.com/username/repo.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage

1. Preprocess EMG signal data to extract relevant features.
2. Train the KNN classification model using the provided datasets or your custom data.
3. Evaluate the model's performance using evaluation scripts and metrics.
4. Utilize the trained model for classifying new EMG signals in robot-assisted rehabilitation scenarios.

## Contributing

Contributions to enhance the classification framework or improve documentation are welcome. Please fork the repository, make changes in a new branch, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

For detailed usage instructions, examples, and additional information, refer to the documentation in the `docs/` directory.
