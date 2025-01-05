
# K-Means ATIS Intent Classification

This repository contains a project that utilizes the **K-Means clustering algorithm** for intent classification on the **ATIS (Airline Travel Information Systems)** dataset. The project includes implementation files, training/testing datasets, and required dependencies.

## Repository Contents

- **`K_MEANS_ATIS.ipynb`**  
  A Jupyter Notebook that demonstrates the step-by-step implementation of the K-Means clustering algorithm for intent classification. Includes detailed explanations, code, and visualizations.

- **`K_MEANS_ATIS.py`**  
  A Python script version of the implementation, designed for direct execution without requiring a notebook interface.

- **`atis_intents_train.csv`**  
  The training dataset containing labeled intents for model training.

- **`atis_intents_test.csv`**  
  The testing dataset used for evaluating the performance of the clustering algorithm.

- **`requirements.txt`**  
  A list of dependencies required to run the project. Use this file to install necessary packages with the following command:
  ```bash
  pip install -r requirements.txt
  ```

## Setup and Usage

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <repository_directory>
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Code
- To explore and run the project interactively, open the Jupyter Notebook:
  ```bash
  jupyter notebook K_MEANS_ATIS.ipynb
  ```
- To execute the project as a standalone script:
  ```bash
  python K_MEANS_ATIS.py
  ```

## Dataset Overview

The ATIS dataset is widely used for intent recognition tasks in natural language processing. It contains various user queries related to airline travel, categorized into different intents such as flight booking, airport information, etc.

### Dataset Structure
- **`atis_intents_train.csv`**: Used for training, includes labeled examples for intent recognition.
- **`atis_intents_test.csv`**: Used for testing the model's clustering performance.


## Contact

For any questions or feedback, feel free to reach out.
