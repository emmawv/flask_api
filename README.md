# API Connection with Flask Project

## Project Objective

The objective of this project is to program an API that allows us to obtain data used to train a machine learning model, as well as the predictions of sai model.

The API will be set up using Flask and will consist of the following endpoints:

* All data 

* Just the train data

* Just the test data

* A sepcific observation __n__ from the data

* A query with specific filters

* Predictions

## Running the project

Install required dependencies: ```pip install -r requirements.txt```

* First the server must be started by running the notebook ```api_connection.ipynb```

* Then the calls are made from the notebook ```api_interaction.ipynb```

* The secondstep can be avoided if you test by introducing the sepcified endpoints in your browser with the URL created by the Flask app (http://127.0.0.1:5001)