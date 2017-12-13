# Healthcare Rides

The city of Austin spends nearly $900 per Emergency Service ride, and does well over 110,000 service calls per year. 
However, nearly 60,000 rides are considered "non-emergency;" instead often used to get a clinic appointment by the elderly, and by those with chronic illnesses. 

In this team, a pair of developers worked on creating the infastructure for the front and backend of the healthcare vouchers app, while the data scientists worked on visualizing the business case through colleting and aggregating datasets, creating models to reveal important features, and mapping the case in ArcGIS. 

To view our Healthcare rides presentation click on the URL: 
https://docs.google.com/presentation/d/1cXxUhq2JyHX_tkW0XXnps7vmmY_zVxLwTt89jSHOj4g/edit?usp=sharing

To view a few sample maps: 
(1) High Blood Pressure: https://arcg.is/1D9jfW 
(2) Elderly Living Alone: https://arcg.is/109myj
(3) Diabetes Rates: https://arcg.is/49beC

To run the application: 

virtualenv venv

. venv/bin/activate

pip install Flask

FLASK_APP=index.py flask run
