# SalesSense - Real-time Interactive Sales Forecasting Web Application 📈📊

SalesSense is an intuitive web app powered by cutting-edge machine learning models that provides real-time sales forecasts, helping businesses optimize inventory, boost profits, and make data-driven decisions effortlessly 💼💰🤖

## Table of Contents 📚

- [Introduction](#introduction) 📝
- [Features](#features) ✨
- [Demo](#demo) 🚀
- [Getting Started](#getting-started) 🏁
  - [Installation](#installation) 🛠️
  - [Running the App](#running-the-app) 🏃
- [App Structure](#app-structure) 🧱
- [Usage](#usage) 📊
  - [Making Predictions](#making-predictions) 📈
  - [Viewing Sales Trends](#viewing-sales-trends) 📉
- [Technologies Used](#technologies-used) 💻🔬
- [Data Preprocessing](#data-preprocessing) 🧹🧮
- [Model Training](#model-training) 🤖📓
- [Contributing](#contributing) 🤝🙌
- [License](#license) 📜

## Introduction 🚀

The SalesSense app leverages machine learning models to provide real-time sales forecasts for businesses. It offers an intuitive and user-friendly interface to input relevant data and instantly receive sales predictions.

## Features ✨

- Real-time sales predictions.
- Interactive user interface.
- Visualize sales trends over time.
- User-friendly design.
- Support for different product families.
- Data preprocessing and model training.

## Demo 🚀

- ### Pictures 📸
  | ![initial_screen](https://github.com/snyamson/P4-SalesSense-Interactive-Sales-Forecasting-Web-Application/assets/58486437/fd9256de-65f6-48e2-860f-82838651c24b) | ![forecast sales screen](https://github.com/snyamson/P4-SalesSense-Interactive-Sales-Forecasting-Web-Application/assets/58486437/c47bd94c-7b4e-43c0-8d66-973eb8943699) |
  | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | ![history](https://github.com/snyamson/P4-SalesSense-Interactive-Sales-Forecasting-Web-Application/assets/58486437/917e77f3-d7e9-4c6c-86ee-004f29819b15)        | ![trend](https://github.com/snyamson/P4-SalesSense-Interactive-Sales-Forecasting-Web-Application/assets/58486437/336c5ea5-5d7e-4cfe-8c7a-d2dd61c9f325)                 |

## Getting Started 🏁

Follow these instructions to get the app up and running on your local machine.

### Installation 🛠️

1. Clone the repository:

   ```bash
   git clone https://github.com/snyamson/P4-SalesSense-Interactive-Sales-Forecasting-Web-Application.git
   cd P4-SalesSense-Interactive-Sales-Forecasting-Web-Application
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the App 🏃

Run the Streamlit app using the following command:

```bash
streamlit run src/app/app.py
```

Access the app through your web browser at `http://localhost:8501`.

## App Structure 🧱

- `src`: The main application directory.
- `app/`: Directory containing app components, utility functions and the main application script `app.py`.
- `model/`: Directory for storing pre-trained model and preprocessing tool.
- `notebook/`: Directory containing the data and the jupyter notebook for model training.

## Usage 📊

### Making Predictions 📈

1. Fill in the required fields such as the family of the store, store type, date, items on promotion, previous sales, and rolling mean.
2. Click the "Submit" button to receive a real-time sales prediction.

### Viewing Sales Trends 📉

1. Click the "View Trends" tab on the app.
2. Explore the historical sales trends using the line chart.
3. Click the "Make Prediction" button to go back to the prediction form.

## Technologies Used 💻🔬

- Streamlit: Python web application framework.
- Pandas: Data manipulation and analysis library.
- Scikit-Learn: Machine learning library.
- XGBoost: Gradient boosting library.
- Joblib: Serialization and deserialization of models.
- HTML/CSS: Styling and layout.

## Data Preprocessing 🧹🧮

The app preprocesses input data to ensure compatibility with the machine learning model. It scales and transforms the data as needed for accurate predictions using the preprocessor exported from the notebook.

## Model Training 🤖📓

The app employs a pre-trained XGBoost machine learning model (Details about training can be found in the notebook). The model was trained on historical sales data to provide accurate forecasts.

## Contributing 🤝🙌

Contributions to the SalesSense app project are welcome. Please follow these guidelines for contributing:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`
3. Make your changes and commit them with clear, concise commit messages.
4. Push your changes to your fork.
5. Create a pull request against the main repository.

## License📜

This project is licensed under the [MIT License](LICENSE).

---

Feel free to star ⭐ this repository if you find it helpful!
