# Neighbourhood Application

## Author  
[Ronoh K. Wycliffe](https://github.com/wikky2012/neighbourhood)  
  
# Description  
This is a web application that enables users sign up to it and interact with the various happening in their neighbourhood.
  
It allows users to:
* Sign in with the application to start using it.
* Set up a profile about themselves, enter a general location of where they live.
* Find a list of different businesses in their neighborhood.
* Find Contact Information for the health department and Police authorities near their neighborhood.
* Create Posts that will be visible to everyone in their neighborhood.
* Change one's neighborhood when they decide to move out.
* Only view details of a single neighborhood.

##  Live Link  
click [here]()  to visit the live site

### Prerequisites
The following are needed for the application to run on a local computer:
* python version 3.8
* Django framework
* Bootstrap v.3
* Text editor (Pycharm,Atom, VS code or Sublime )
* Web browser

A crucial point to note: You will need Python version 3 and above installed on your laptop.
If you don't have it installed got to [Python.org](https://www.python.org/downloads/) to install.

  
## Setup and Installation  
* Clone this repository to your local computer 
##### Cloning the repository: 
```bash
 https://github.com/wikky2012/neighbourhood
```
* install all the extensions listed in the ``requirements.txt`` file.
##### Navigate into the project folder and install dependencies  
 ```bash 
 pip install -r requirements.txt 
```
* Ensure you have python3.8 installed in your computer.
* From the terminal navigate to the cloned project folder.
* Switch to the virtual environment by entering  ```source virtual/bin/activate``` from the terminal. 
* Once inside the application, a user will be able to use the application.

 ##### Setup Database  
SetUp your database User and Password, then makemigrations 
 ```bash 
 python manage.py makemigrations 
 ``` 
 Then Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 

##### Testing the application  
 ```bash 
 python manage.py test 
```
 
## Technologies used  
  
* [Python3.8](https://www.python.org/)  
* [Django 2.2](https://www.djangoproject.com/download/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* None, reach out below incase of any.
  
## Contact Information   
In case of any question or complaints, please [email](wicliferono@gmail.com) me
  
## License 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 
 Copyright (c) 2020 **Ronoh K. Wycliffe**
