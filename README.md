# Postman Weather Collection #

This project is for testing Weather API with postman.

* **Tool** : Postman
* **Test ScriptLanguage** : JavaScript

### How to setup project ###

* Download and install [Postman](https://www.postman.com/downloads/)
* Download and install [Git](https://git-scm.com/downloads)
* Open command prompt and enter command **git clone https://stephenshinde12@bitbucket.org/stephenshinde12/postmanweathercollection.git**


### How to run project ###

* Open **Postman** and Import **Weather.postman_collection.json**
* Click on collection name **Weather** and click on Run button

### Project Structure ###
* Method - Get
* Endpoint (By CityName) - {{url}}/data/2.5/forecast?q=New York&appid={{appId}}&units=metric
* url - https://api.openweathermap.org
* appId - 10596cea5f4d17dc9dde106c6f3718e8
* url and appId set in collection variables
* Test is written in Tests section.
