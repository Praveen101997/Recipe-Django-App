# Recipe App API

## Assets Directory

```
|  
└───Screenshots_Recording
```

## ScreenRecording

## <a href="https://github.com/Praveen101997/Recipe-Django-App/raw/main/Screenshots_Recording/Recording_Demo/screenrecording.wmv" download>Click to Download</a>

## ScrrenShots

<img src="Screenshots_Recording/ScreenShots/Screenshot_1.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_2.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_3.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_4.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_5.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_6.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_6.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_7.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_8.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_9.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_10.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_11.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_12.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_13.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_14.jpg" width="500" />
<img src="Screenshots_Recording/ScreenShots/Screenshot_15.jpg" width="500" />


Build a fully functioning REST API using:

 - Python
 - Django / Django-REST-Framework
 - Docker / Docker-Compose
 - Test Driven Development

## Getting started

To start project, run:

```
docker-compose up
```

The API will then be available at http://127.0.0.1:8000

### Extra Command

```
Test Code 
docker-compose run app sh -c "python manage.py test && flake8

Create SuperUser
docker-compose run app sh -c "python manage.py createsuperuser"

Create a User
http://localhost:8000/api/user/create/

Token Generate
http://localhost:8000/api/user/token/

Home Recipe
http://localhost:8000/api/recipe/

Create Recipe
http://localhost:8000/api/recipe/recipes/

Upload Image to Recipe
http://localhost:8000/api/recipe/recipes/1/upload-image/

Extract By Ingredients
http://localhost:8000/api/recipe/recipes/?ingredients=2
```
