# rocovi
Webapp to visualise future spread of CoVid-19 in different countries

## See it online

Navigate to https://rocovi.herokuapp.com to see it online. Works best in landscape/on a monitor. Not well optimised for mobile, but it gets the job done

## Install Dependencies 

`pip install -r requirements.txt`

## Start the app:

`env FLASK_APP=app.py flask run`

## Use the app:

- Navigate to `localhost:5000/` for a list of countries 
- Navigate to `localhost:5000/<country>` (not all countries work or have consistent data)
