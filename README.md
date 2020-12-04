# covid-alert-tracker
This is a project done for the University of Exeter to make a Covid-19 alert tracking app.
It creates a webapp where alarms can be set which give Covid-19 information. There are also passive notifications.

In terms of project structure, the root directory **.** contains all code for running the program with the most important
file being **app.py** which runs the program when it is run. The other Python files in the root directory deal with secondary functionality.
Next the **./tests/** directory holds Python files defining unit tests for the program files. The **./data/** directory holds data downloaded from the APIs.
The **./static/** directory holds static files such as images and the **./templates/** directory holds HTML files for the web app.

In order to run the project first set your API keys for the project by opening **config.py**
and replacing **<weather_api_key>** with your openweathermap.org API key.
Then replace **<news_api_key>** with your newsapi.org API key.

Next make sure that you have the following modules installed:
**Flask, pyttsx3, pandas, requests, uk-covid19**

To run the testing make sure that you have the following modules installed:
**mock**

Finally to run the app run the **app.py** module in the root directory using Python.

In order to run the tests for the modules please run the file **test.py** in the root directory.

The news data in the program is from newsapi.org, the weather data is from openweathermap.org and the
Covid-19 data is from Public Health England. The HTML file index.html was provided by the university.

Author of the Python code: Jasmine S. Thompson

Date: 04/12/2020
