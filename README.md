# Healthcare Rides

The city of Austin spends nearly $900 per Emergency Service ride, and does well over 120,000 service calls per year. 
However, nearly 80,000 rides are considered non-emergency or "basic life support"; instead often used to get to clinic appointments by the elderly, and by those with chronic illnesses. 

Our team's idea was to leverage our local rideshare service Ride|Austin to work with the City of Austin in providing vouchers for roundtrip transports that could cut the costs down to an average of $40 per trip. To do so, we decided to create a prototype of the app. In charge of this was a pair of developers who worked on creating the infastructure for the front and backend of the healthcare vouchers app. Meanwhile the data scientists worked on visualizing the business case through colleting and aggregating datasets, creating models to reveal important features, and mapping the case in ArcGIS. 

To view our Healthcare rides presentation click on the URL: 
https://docs.google.com/presentation/d/1cXxUhq2JyHX_tkW0XXnps7vmmY_zVxLwTt89jSHOj4g/edit?usp=sharing

To view a few sample maps:

<p align="center"> 
  (1) High Blood Pressure 
<img src="Images/Screen Shot 2018-01-16 at 12.10.47 PM.png">
</p>

<p align="center"> 
  (2) Elderly Living Alone:
<img src="Images/Screen Shot 2018-01-16 at 12.12.01 PM.png">
</p>

<p align="center"> 
  (3) Diabetes Rates 
<img src="Images/Screen Shot 2018-01-16 at 12.13.41 PM.png">
</p>


To run the application: 

virtualenv venv

. venv/bin/activate

pip install Flask

FLASK_APP=index.py flask run
