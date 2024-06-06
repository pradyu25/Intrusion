# Intrusion Detection System using Random Forest and Decision Tree Algorithms

## Introduction
This repository contains an implementation of an Intrusion Detection System (IDS) using machine learning algorithms, specifically Random Forest and Decision Tree. An IDS is crucial for detecting malicious activities or policy violations within a computer network. 

The Random Forest and Decision Tree algorithms are chosen for their effectiveness in classification tasks and their ability to handle large datasets with high-dimensional feature spaces. This system is designed to analyze network traffic data and classify it into normal or malicious activities.

## Installation
To run this IDS, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/pradyu25/intrusion-detection-system.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage
After installing the dependencies, you can use the IDS by executing the following command:

```bash
python main.py
```

This will start the IDS and begin analyzing the network traffic data. You can customize the settings and parameters in the `config.py` file according to your requirements.

## Dataset
The dataset used for training and testing the IDS is not provided in this repository due to its large size and potential privacy concerns. However, you can use any publicly available dataset for intrusion detection, such as the NSL-KDD dataset or the UNSW-NB15 dataset.

Please download the dataset of your choice and place it in the `data/` directory. Update the `config.py` file with the appropriate path to the dataset.

## Algorithm Details
### Random Forest
Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### Decision Tree
Decision Tree is a supervised learning algorithm used for classification and regression tasks. It works by partitioning the data into subsets based on the values of input features. Each subset is then recursively processed in the same manner until a stopping criterion is met.

## Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the [Contributing Guidelines](CONTRIBUTING.md).

---

Feel free to customize this README according to your project's specific details and requirements.
