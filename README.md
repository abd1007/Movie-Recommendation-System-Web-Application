# Movie-Recommendation-System-Web-Application
Building a Movie Recommendation System web application using Django framework and Recommendation technique called Collaborative Filtering 
- Matrix Factorization Algorithm

### Screenshot

###### Home page
![home](https://user-images.githubusercontent.com/20842692/45380125-941d7500-b61f-11e8-852d-c09e9586b35b.png)

###### Recommendation page
![recom](https://user-images.githubusercontent.com/20842692/45380167-b57e6100-b61f-11e8-8ec0-e07c26daa4a3.jpg)

###### Rating page
![rate](https://user-images.githubusercontent.com/20842692/45380186-be6f3280-b61f-11e8-8ad6-8b967d1cba1a.png)

### Technologies Used
#### Web Technologies
- Python
- HTML 
- CSS
- JavaScript
- Bootstrap 

#### Python Packages 
- Django
- Numpy
- Pandas 
- Scipy

#### Database
SQLite

##### Requirements
```
python 3.6
pip3
virtualenv
```

##### Setup to run

- Download zip file to your local machine
- Extract the zip file
- Open terminal/cmd promt
- Goto that Path

Example

```
cd ~/Destop/Movie-Recommender-System-Web-Application-master
```

Create a new virtual environment in that directory
```
python3.6 -m pip install virtualenv
virtualenv venv -p python3.6
```

Activate virtual environment
```
source venv/bin/activate
```

Command line to install all dependencies
```
pip install -r requirements.txt
```

Then
```
cd ../Movie-Recommender-System/MovieRecommendationApp
```

Command line to run your program
```
python manage.py runserver
```

Now open your browser and go to this address
```
http://127.0.0.1:8000
```
