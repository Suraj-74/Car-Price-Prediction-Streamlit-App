# Car Price Prediction -- Streamlit App
Welcome to the GitHub repository for the Car Price Prediction Streamlit App! This project aims to provide a user-friendly web application that predicts the price of a car based on various parameters. The app is built using Streamlit, a most popular Python library for creating interactive web applications.
## Features
1. Explore the dataset and visualize the data.
2. Predict the price of a car based on its features.
3. Input various car parameters, such as mileage, brand, km_driven, seller_type, year, and more , to get an estimated price.
4. The app uses a best trained machine learning model to make predictions.
## Model Deployment
We are pleased to announce that the project has been successfully deployed using Streamlit. You can access the live deployment of the Car Price Prediction model by following this link:[Car Price prediction Deployment](https://data-science-capstone-project-p2sjspktlwk.streamlit.app/)
## Usage 
Once you access the Streamlit app, you will be able to interact with the model's user-friendly interface. Simply input the relevant features of the car you want to predict the price for, and the model will provide you with an estimated price based on the trained data. Feel free to experiment with different combinations of features and explore the model's performance.
## Feedback and Contributions
Your feedback and contributions are highly appreciated. If you encounter any issues, have suggestions for improvement, or would like to contribute to the project, please don't hesitate to create an issue or submit a pull request in this repository.

> Let's start predicting car prices! Enjoy using the Car Price Prediction model deployed on Streamlit.

## Installation
To run the Car Price Prediction Streamlit App on your local machine, follow these steps:

1. Clone this repository to your local machine using the following command:`git clone https://github.com/06Neel/Data-Science-Capstone-Project.git`

2. Navigate to the project directory:`cd car-price-prediction-streamlit`

3. Create a virtual environment (optional but recommended) and activate it:`python -m venv venv`
       For Windows:`venv\Scripts\activate`
       For Unix or Linux:`source venv/bin/activate`
4. Install the required dependencies: `pip install -r requirements.txt`

5. Run the Streamlit app:`streamlit run app.py`

6.Open your web browser and go to `http://localhost:8501` to access the Car Price Prediction app.
## Dataset
The dataset used for this project is included in this repository.
Please download the dataset and place it in this repository before running the app.
## Project Structure
The repository has the following structure:

car-price-prediction-streamlit/ ├── app.py ├── CAR DETAILS.csv ├── car_predic.pkl ├── README.md └── requirements.txt

1. `app.py`: The main Python script that contains the Streamlit app code.
2. `Car Details.csv`: It has the Dataset of Car Price.
3. `car_predict/`: It has saved the best model to trained the data.
4. `README.md`: This readme file.
5. `requirements.txt`: List of Python packages required to run the app.
## Model Training
The machine learning model used in the app is trained separately and saved as a serialized file (`car_predict.pkl`). If you want to train your own model, you can refer to the Jupyter Notebook provided in the repository.
## Contribution
Contributions to this project are welcome! If you find any issues or have suggestions for improvements in my code, please open an issue or submit a pull request. Let's make this project even better together.
## Acknowledgements
We would like to express our gratitude to those resources for their valuable contributions:

1. [Streamlit](https://streamlit.io/)
2. [Scikit-learn](https://scikit-learn.org/stable/)
3. [Pandas](https://pandas.pydata.org/)
4. [Numpy](https://numpy.org/)
Thank you for visiting this repository. We hope you find the Car Price Prediction Streamlit App useful and enjoy using it!
