# Heart Disease Prediction

Welcome to the Heart Disease Prediction project! This repository contains a machine learning project built from scratch to predict the likelihood of heart disease using various sampling techniques to balance the dataset. The project is implemented using Django and Flask frameworks.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Sampling Techniques](#sampling-techniques)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Heart disease is a leading cause of death worldwide, and early detection is crucial for effective treatment. This project aims to predict heart disease using machine learning algorithms. We have used various sampling techniques to balance the dataset, ensuring better model performance.

## Features
- Predict the likelihood of heart disease using machine learning models.
- Implemented using Django and Flask frameworks.
- Uses various sampling techniques to balance the dataset.
- User-friendly web interface for making predictions.
- Detailed documentation and clean code structure.

## Installation
To get started with this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the Django development server:**
   ```bash
   python manage.py runserver
   ```

6. **Run the Flask API server:**
   ```bash
   cd flask_api
   flask run
   ```

## Usage
Once the servers are up and running, you can access the web interface to make predictions. Simply input the required medical parameters, and the model will predict the likelihood of heart disease.

## Dataset
The dataset used for this project is sourced from the UCI Machine Learning Repository. It contains various medical attributes related to heart disease. The dataset is preprocessed and balanced using sampling techniques before being fed into the machine learning models.

## Model Training
The model training process involves the following steps:
1. Data Preprocessing
2. Balancing the dataset using sampling techniques (e.g., SMOTE, Random Under-sampling)
3. Feature Selection
4. Model Training using various machine learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forest)
5. Model Evaluation

## Sampling Techniques
Balancing the dataset is crucial for improving model performance. In this project, we have implemented several sampling techniques:
- **SMOTE (Synthetic Minority Over-sampling Technique)**
- **Random Over-sampling**
- **Random Under-sampling**

These techniques help in creating a balanced dataset, which reduces bias and improves the accuracy of the models.

## Contributing
We welcome contributions from the community! If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Screenshot
![Screenshot 2024-06-01 at 22-19-28 Heart Disease Prediction](https://github.com/figo2001/Heart-Disease-Prediction-using-Flask/assets/78696850/bae6036e-fdf9-4739-a2c6-fd40db9dda35)



---

Thank you for visiting our project! We hope you find it useful and informative. Happy coding!
