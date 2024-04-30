# salary_prediction_front_end

 ## the html section of the salary_api
 This section of the assignment is the html site created for the survey launch. This html was created using a base and an index html file. Various objectives were met to create the survey on the website. Creating multiple questions, short answers, and data collection of the survey results. 

 # css file
 css file is used to make website more visually appealing and easier to navigate. 

# flask
This application uses flask to initialize the application and define the route. This is done using the app.py file that outlines the specific launching instuctions for the application. 

### To Run This Application

Clone this repository to local computer

Create a new virtual environment

Windows: python -m venv ./venv
Mac: python3 -m venv ./venv
Activate the new virtual environment

Windows: .\venv\Scripts\activate
Mac: source ./venv/bin/activate
Install the dependencies pip install -r requirements.txt

Run the application with flask run a. To run a specific app: flask --app app run
b. To change the port: flask run --port 8080
c. To listen on all public IP addresses: flask run --host 0.0.0.0 d. To run in debug mode: flask run --debug

Example: flask --app app run --port 8080 --debug 
