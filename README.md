# Diabetes_Prediction

Welcome to the Diabetes Prediction project! This project leverages machine learning to predict the likelihood of an individual having diabetes based on various medical parameters. The project uses Streamlit to provide an interactive web application for users to input their medical data and view the prediction results.

#Table of Contents
- Overview
- Features
- Technologies Used
- Installation
- Usage
- Project Structure

# Overview

The Diabetes Prediction project aims to provide a tool that can help in predicting the likelihood of diabetes in individuals based on medical data inputs. Users can input various parameters such as glucose level, blood pressure, BMI, age, and more. The machine learning model then predicts whether the individual is likely to have diabetes.


#Project Structure
```
Diabetes_Prediction/
│
├── diabetes_prediction.py      # Main application script
├── diabetes_model.pkl          # Pre-trained machine learning model
├── requirements.txt            # List of required packages
├── README.md                   # Project README file
└── .gitignore                  # Git ignore file

```
# Features

- User-Friendly Interface: An intuitive web application interface to input medical parameters.
- Real-Time Predictions: Get instant predictions based on the input data.
- Data Visualization: Visual representations of the input data and prediction results.

# Technologies Used

- Python: For data processing and machine learning model development.
- Pandas: For data manipulation and analysis.
- Scikit-learn: For building and training the machine learning model.
- Pickle: To save and load the trained machine learning model.

# Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Diabetes_Prediction.git
    cd Diabetes_Prediction
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Ensure the pre-trained model file (`diabetes_model.pkl`) is in the project directory. If not, you may need to train the model or obtain it from a reliable source.

# Usage

To run the Streamlit app, execute the following command in the project directory:

```bash
streamlit run diabetes_prediction.py
```


# Acknowledgements

A big thank you to the open-source community for the tools and libraries that made this project possible. Special thanks to the medical data providers and machine learning enthusiasts who inspired this project.
