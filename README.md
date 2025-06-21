# Chest X-Ray Classification

This project aims to classify chest X-ray images into different categories. It uses a deep learning model to perform the classification.

## Project Structure

- `chest_Xray/`: Contains the dataset of chest X-ray images.
- `experiments/`: Contains experiment-related files, such as notebooks or scripts for trying out different models and techniques.
- `results/`: Contains the results of the experiments, such as trained models, logs, and plots.
- `final.ipynb`: The main Jupyter notebook for the project, containing the final model and analysis.
- `requirements.txt`: A list of the Python packages required to run the project.
- `README.md`: This file.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd chestXray
    ```
2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate 
    ```
3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Open the Jupyter notebook:**
    ```bash
    jupyter notebook final.ipynb
    ```
2.  **Run the cells in the notebook to train the model and see the results.**