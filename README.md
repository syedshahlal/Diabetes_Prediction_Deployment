# Diabetes Prediction Web App using Flask

This is a web application built with Flask that allows users to predict whether a person is diabetic or not based on various input attributes. The application uses a pre-trained machine learning model to make predictions.

## Getting Started

These instructions will help you set up and run the web application on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your machine:

- Python 3
- Flask
- Flask-CORS
- scikit-learn
- pandas
- numpy

You can install the required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
## Running the App
1. Clone this repository to your local machine.
```bash
git clone https://github.com/syedshahlal/Diabetes_Prediction_Deployment.git
```

3. Navigate to the project directory:
  ```bash
  cd Diabetes_Prediction_Deployment
  ```
3. Run the Flask app:

```bash
python app.py
```

The Flask development server will start running. By default, the app will be accessible at http://127.0.0.1:5000/ in your web browser.

4. Use the web form to input the attributes for the individual you want to predict.

5. Click on the "Predict" button to get the prediction result.

## Project Structure
The project structure is as follows:

```arduino
diabetes-prediction-app/
    ├── app.py
    ├── Model/
    │   ├── standardScalar.pkl
    │   └── modelForPrediction.pkl
    ├── Dataset/
    │   └── diabetes.csv
    ├── Notebook/
    │   └── Logistic_Regression.ipynb
    └── templates/
        ├── home.html
        ├── single_prediction.html
        └── index.html
```
* app.py: The main Flask application file containing the web app routes and logic.
* Model/: Directory containing the pre-trained model and standard scalar pickled files.
* Dataset/: Directory containing the dataset in csv format.
* Notebook/: Directory containing the worked ipynb file.
* templates/: Directory containing HTML templates for rendering web pages.
  
## Model and Data
The machine learning model used for prediction is saved in pickled format (modelForPrediction.pkl) along with the standard scalar (standardScalar.pkl) used for feature scaling.

Please note that the model and data used in this app are for demonstration purposes only and may not be suitable for production use.

## Acknowledgments
* The model used in this app is trained on a diabetes dataset, and the sample data is for demonstration purposes only.
* Flask: https://flask.palletsprojects.com/
* scikit-learn: https://scikit-learn.org/
## License
This project is licensed under the MIT License - see the LICENSE file for details.
