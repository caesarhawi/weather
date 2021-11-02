# weather

Some issues I faced while training and testing RASA:

For some reason, I always got an error that unit_imperial was given a sort "country"

With overanswering, RASA has a problem with cities that contain white spaces, such as Saint Petersburg, so it interpreted Saint as the city name and Peterburg as the country.
