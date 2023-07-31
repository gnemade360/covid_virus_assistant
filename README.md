# covid_virus_assistant

Coronavirus Voice Assistant
This app makes use of ParseHub which is a powerful web-scraping tool.

The data is extracted from the very popular website Worldometers that provides the accurate information about the COVID19 disease worldwide.

Steps to be followed:

Download ParseHub.
1.Start a New Project and paste the link 'https://www.worldometers.info/coronavirus/'.
2.Select the items that you would like to scrape from the page and assign unique tags to each one of them. Get the data.
3.Copy the api key, project token and run token to config file and import them to your main.py file.
4.Install the requirements for this project: requests, certifi, chardet, comtypes, idna, pyttsx3, pywin32, SpeechRecognition, urllib3.
5.Run the main.py file.
6.Steps to run the application:

7.Execute the command "python covid.py".
8.Ask the assistant for "number of total cases", "total cases in India", etc.
9.For updating the information, say "update" and wait for a while.
10.Say "stop" to exit the application.
