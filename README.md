
## Flight-Fare-Prediction

A Machine Learning Web App that can predict the flight prices. The app is created with the help of ```Flask``` and ```Python.```

## A glimpse of the web app:

https://user-images.githubusercontent.com/117584271/234536483-0c67686a-7e2d-4524-b552-120f76e4fd99.mp4

## Directory Tree
--> Here are some details of the subdirectories and files that the repository contains. 
```
├───.idea
│   └───inspectionProfiles
├───Flight Price Dataset
├───static
└───templates
```

## Description

* Static Folder contains the favicon as well as the css file which describes the HTML elements of the web app.
* Template folder contains the html file which depicts the format of the web page.
* Flight Price Dataset is the dataset file which is the excel format.
* Flight_Fare_Prediction.ipynb contains all the notebook code, the execution results as well as the codes that has helped in generating the model
  for the web app.
* Procfile includes the code '''web: gunicorn app:app'''which depicts that gunicorn commands are run by the application's containers on the platform. 
  To create a procfile run the following command on command prompt. ``` echo web: gunicorn app:app --preload > Procfile ```
* README.md includes the stucture that provides a detailed description of my GitHub project.
* app.py includes the all the routes and functions to perform the actions of web app. 
  This file is the root of our Flask application which we will run in the command line prompt.
* flight_rf.pkl is the random forest regression model that is the core of my web application.
* Requirements.txt file includes all the libraries that has been used to create the web app. After installing all the required packages,
'''pip freeze > requirements.txt''' command was run on the command prompt to create the requirements.txt file

## Libraries Used
--> This section contains the list of the libraries that have been used to create the web app. 
```
altair==4.2.2
attrs==22.2.0
bcrypt==4.0.1
blinker==1.6.1
cachetools==5.3.0
certifi==2022.12.7
charset-normalizer==3.1.0
click==8.1.3
colorama==0.4.6
decorator==5.1.1
dnspython==2.3.0
docopt==0.6.2
email-validator==1.3.1
entrypoints==0.4
Flask==2.2.3
Flask-Bcrypt==1.0.1
Flask-Cors==3.0.10
Flask-Login==0.6.2
Flask-Mail==0.9.1
Flask-SQLAlchemy==3.0.3
Flask-WTF==1.1.1
gitdb==4.0.10
GitPython==3.1.31
greenlet==2.0.2
idna==3.4
importlib-metadata==6.3.0
itsdangerous==2.0.1
Jinja2==3.1.2
joblib==1.2.0
jsonschema==4.17.3
markdown-it-py==2.2.0
MarkupSafe==2.1.2
mdurl==0.1.2
mysqlclient==2.1.1
numpy==1.24.2
packaging==23.1
pandas==1.5.3
Pillow==9.5.0
pipreqs==0.4.13
protobuf==3.20.3
pyarrow==11.0.0
pydeck==0.8.1b0
Pygments==2.15.0
Pympler==1.0.1
pyrsistent==0.19.3
python-dateutil==2.8.2
pytz==2023.3
pytz-deprecation-shim==0.1.0.post0
requests==2.28.2
rich==13.3.4
scikit-learn==1.2.2
scipy==1.10.1
six==1.16.0
smmap==5.0.0
SQLAlchemy==2.0.7
streamlit==1.21.0
threadpoolctl==3.1.0
toml==0.10.2
toolz==0.12.0
tornado==6.2
typing_extensions==4.5.0
tzdata==2023.3
tzlocal==4.3
urllib3==1.26.15
validators==0.20.0
watchdog==3.0.0
Werkzeug==2.2.3
WTForms==3.0.1
yarg==0.1.9
zipp==3.15.0
```
