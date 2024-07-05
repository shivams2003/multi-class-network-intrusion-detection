

---

# Multi-Class Network Intrusion Detection on CICIDS2017 Dataset

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Project Overview
This project focuses on implementing multi-class network intrusion detection using the CICIDS2017 dataset. The aim is to preprocess the data, explore various machine learning models, and evaluate their performance in detecting different types of network intrusions. The models used include Random Forest, ID3, AdaBoost, Multilayer Perceptron (MLP), Naive Bayes, and Quadratic Discriminant Analysis (QDA).

## Dataset
The CICIDS2017 dataset is used for this project. It includes various types of network traffic data collected over multiple days, providing a comprehensive set of features for training and evaluating intrusion detection models.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shivams2003/multi-class-network-intrusion-detection.git
   cd multi-class-network-intrusion-detection
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook network-intrusion-detection.ipynb
   ```

2. Run the cells in the notebook to preprocess the data, train the models, and evaluate their performance.

## Results
The models were evaluated using metrics such as accuracy, F1 score, precision, recall, and confusion matrices. Here are the performance metrics for the best models:

- **Random Forest**: Accuracy: 99.87%, F1 Score: 99.86%
- **ID3**: Accuracy: 99.85%, F1 Score: 99.85%
- **MLP**: Accuracy: 99.53%, F1 Score: 99.50%

## Contributions
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## Acknowledgments
- Special thanks to Prof. Anjaneyulu for supervising this research internship.
- This project was conducted as part of a research internship at NIT Warangal.

---
