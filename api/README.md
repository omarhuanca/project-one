# school-events-dj


## run project
docker-compose up

## login
POST http://localhost:8000/api-auth/login

## resources
```
{
    "tasks": "http://localhost:8000/tasks/",
}
```
## create new user
- ```docker-compose run app python manage.py createsuperuser ```

## mofify models and run
- ```docker-compose run app python manage.py makemigrations```
- ```docker-compose run app python manage.py migrate```
## 
