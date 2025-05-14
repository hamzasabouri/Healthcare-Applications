# Healthcare Applications - Recommender System

## Description
This project explores the use of artificial intelligence in healthcare, specifically focusing on building a symptom-disease recommender system. The goal is to predict potential diseases based on a set of symptoms. The project uses a dataset that maps symptoms to diseases and applies machine learning techniques for modeling and analysis.

## Repository Files
- **`BigData.ipynb`**: A Jupyter notebook containing the main code for data preprocessing, model training, and evaluation of the recommender system.
- **`symptoms_diseases_modified.csv`**: A dataset that maps various symptoms to corresponding diseases, serving as the core data for the recommendation model.

## Instructions for Running the Code on Google Colab

### Step 1: Open the Notebook
Click the following link to open the notebook directly on Google Colab:

[Open BigData.ipynb on Google Colab](https://colab.research.google.com/github/hamzasabouri/Healthcare-Applications/blob/main/BigData.ipynb)

### Step 2: Prepare Your Environment
The notebook is already set up to run on Google Colab. Once the notebook is open, the necessary libraries should be installed automatically in Colab’s environment. If any dependencies are missing, you can install them by running the following command in a new code cell:
```python
!pip install -r requirements.txt
```

### Step 3: Load the Dataset
The symptoms_diseases_modified.csv file is available directly from GitHub. You can load it into your Colab environment by running the following command:

```python
!wget https://github.com/hamzasabouri/Healthcare-Applications/raw/main/symptoms_diseases_modified.csv
```
This will download the dataset into the current working directory.

### Step 4: Run the Notebook
Now you can run each cell of the notebook (BigData.ipynb). To execute the code in each cell:

- Click on the cell, then press Shift + Enter, or Use the play button next to each cell.

The notebook will guide you through:

- Loading and preprocessing the data.

- Building the recommendation model.

- Evaluating the model's performance.

### Step 5: Visualize Results
The notebook includes various data visualizations to help you understand the model’s performance. These visualizations will be displayed automatically in the output sections of the notebook.
