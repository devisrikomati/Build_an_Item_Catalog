# Build_an_Item_Catalog
##This project is completely based on developing an application with usage of framework known as Flask environment OAuth2 provides authentication for further CRUD functionality on the application. Currently OAuth2 is implemented for Google Accounts.
##This is project is for performing a modern applications, variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data.
##Needs of this project
--HTML
--CSS
--Vargrant
--VirtualBox
--flask 
--python
--Oauth
--sqlalchemy
##Process for doing this project
--sudo apt-get install vagrant
--sudo apt-get install virtualbox ' 
--vagrant init ubuntu/trusty64
--vagrant ssh
--cd /vagrant
--Activate flask: flask-env/Scripts/activate
--For deactivate flask: just enter deactivate
##For Google Login
--For API client ID:
 we generate the client ID for the project by using Google Dev Console
    After generating API client ID for project then use that ID in login.html file
    Then after download the JSON file and use that file in our mainproject.py file.
##way of running 
--python database_setup.py to get the database.
--python clothes.py to get the data file.
--python mainproject.py to final output. 
