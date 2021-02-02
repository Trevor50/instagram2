# INSTRAGAM
## Author  
 Trevor Nyagah
# Description  
Is application that enables users to post their post and can be followed by other users.Their post can be shared ,commented and liked others
##  Live Link  

  
## Setup and Installation  
To get the project .......  

```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* [Python3.8](https://www.python.org/)  
* [Heroku](https://heroku.com) 


## License 

* Copyright (c) 2021 @Trevor Nyagah