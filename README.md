# 🍷 Wine Quality Analytics Platform

> An end-to-end Machine Learning application that predicts wine quality based on physicochemical properties using Support Vector Machine (SVM) and provides an intuitive web interface for real-time predictions.

---

## 📖 Overview

The **Wine Quality Analytics Platform** is a Machine Learning application designed to predict the quality of wine based on its chemical composition. The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and deployment through an interactive web application.

This project was developed as an individual project to strengthen practical knowledge of Machine Learning, data preprocessing, model deployment, and web application development.

---

## 🎯 Problem Statement

Wine quality assessment is traditionally performed by expert tasters, making the process subjective, expensive, and time-consuming.

By analyzing the physicochemical characteristics of wine, machine learning models can assist in predicting wine quality more consistently and efficiently.

This application aims to provide an easy-to-use prediction platform for educational and research purposes.

---

# ✨ Features

* Predict wine quality using Machine Learning
* Interactive web interface
* Real-time predictions
* Data preprocessing pipeline
* Feature scaling using MinMaxScaler
* Support Vector Machine (SVM) model
* Probability-based prediction
* Simple and user-friendly interface
* Fast prediction performance

---

# 🛠 Tech Stack

### Machine Learning

* Python
* Scikit-learn
* Pandas
* NumPy

### Visualization

* Matplotlib

### Web Application

* Streamlit

### Development Tools

* Jupyter Notebook
* VS Code

### Version Control

* Git
* GitHub

---

# 📂 Project Structure

```text
wine-quality-app/

├── app.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── WineQT.csv
├── notebook.ipynb
├── README.md
└── assets/
```

---

# ⚙ Machine Learning Pipeline

```
Dataset

↓

Data Cleaning

↓

Feature Selection

↓

Train/Test Split

↓

Feature Scaling

↓

Model Training (SVM)

↓

Model Evaluation

↓

Model Serialization

↓

Streamlit Deployment

↓

Prediction
```

---

# 📊 Dataset

The dataset contains various physicochemical properties of wine.

### Example Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

Target:

* Wine Quality

---

# 🤖 Machine Learning Model

Current Model:

* Support Vector Machine (SVM)

Preprocessing:

* MinMaxScaler

Training Workflow:

* Load Dataset
* Clean Data
* Feature Scaling
* Train Model
* Evaluate Performance
* Save Model

---

# 📈 Model Performance

Current Metrics

* Algorithm: Support Vector Machine (SVM)
* Test Accuracy: ~70%
* Feature Scaling: MinMaxScaler

> Performance may vary depending on dataset version and training parameters.

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/praneeth0317/wine-quality-app.git
```

---

## Navigate

```bash
cd wine-quality-app
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app.py
```

---

# 📷 Application Workflow

1. Launch the application.
2. Enter wine chemical properties.
3. Submit the form.
4. Model processes the input.
5. Predicted wine quality is displayed.

---

# 🧪 Testing

The project has been manually tested for:

* Model loading
* Prediction workflow
* Input validation
* UI responsiveness
* Model serialization
* Streamlit execution

Future versions will include automated unit and integration testing.

---

# 📌 Future Roadmap

## Version 1.1

* Improve UI design
* Better input validation
* Enhanced prediction output

## Version 1.5

* Multiple Machine Learning models
* Model comparison dashboard
* Feature importance visualization

## Version 2.0

* FastAPI backend
* REST APIs
* React/Next.js frontend
* Authentication
* PostgreSQL database
* Docker support
* CI/CD pipeline
* Cloud deployment

---

# 📚 Learning Outcomes

This project helped strengthen understanding of:

* Data preprocessing
* Feature engineering
* Machine Learning workflow
* Classification algorithms
* Model deployment
* Streamlit development
* Git & GitHub
* Python development

---

# 🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

# 📄 License

This project is released under the MIT License.

---

# 👨‍💻 Author

**Praneeth Kukkala**

* GitHub: https://github.com/praneeth0317

---

# 🌟 Support

If you found this project useful, consider giving it a ⭐ on GitHub. It helps support the project and encourages future development.
