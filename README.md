# 💻 Laptop Price Prediction

A Machine Learning web application that predicts the price of a laptop based on its specifications such as company, processor, RAM, storage, GPU, operating system, and display features.

## 📌 Project Overview

Laptop prices vary depending on hardware and software configurations. This project uses a trained Machine Learning model to estimate the price of a laptop based on user inputs.

The application is built using Flask and deployed as a web application.

## 🚀 Features

- Predict laptop prices instantly
- User-friendly web interface
- Machine Learning based prediction
- Supports multiple laptop brands and configurations
- Fast and accurate results

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-Learn
- Pickle
- HTML/CSS

## 📂 Project Structure

```
Laptop-Price-Prediction/
│
├── app.py
├── requirements.txt
├── pipe.pkl
├── dt.pkl
├── .gitignore
├── setup.sh
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Nagasree05/Laptop-Price-Prediction.git
```

### 2. Navigate to Project Folder

```bash
cd Laptop-Price-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

## 🎯 How It Works

1. User enters laptop specifications.
2. The trained Machine Learning model processes the input.
3. The model predicts the laptop price.
4. Predicted price is displayed on the screen.

## 📊 Machine Learning Model

The project uses a trained regression model saved as:

- `pipe.pkl`
- `dt.pkl`

These files are loaded by the Flask application to make predictions.

## 🔮 Future Enhancements

- Improved prediction accuracy
- Modern responsive UI
- Deployment on Render/Streamlit
- Comparison of multiple laptop configurations
- Advanced analytics dashboard

## 👩‍💻 Author

**Nagasree**

GitHub: https://github.com/Nagasree05
