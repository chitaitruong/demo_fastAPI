# Backend clone  of social media app by using FastAPI

#### This API  has 4 routes

## 1) Post route

#### This route is reponsible for creating post, deleting post and updating post

## 2) Users route

#### This route is about creating users and searching user by id

## 3) Auth route

#### This route is about login system

## 4) Vote route

 #### This route is about likes or vote system and this route contain code for upvote or back vote there is not logic about down vote

 # how to run locally
 ## download and run
 ````

git clone https://github.com/chitaitruong/demo_fastAPI.git
cd demo_fastAPI
pip install -r requirements.txt
uvicorn app.main:app --reload

````
## add .env file
````

DATABASE_HOSTNAME=localhost
DATABASE_USERNAME=your_database_username
DATABASE_PASSWORD=your_database_passowrd
DATABASE_PORT=5432
DATABASE_NAME=your_database_name
SECRET_KEY=b3106187fb60857d81632892b304b292f5ea8f21ddd24ad1b5a41b27d1b18460
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30

````
## following link to use the  API
````

http://127.0.0.1:8000/docs 

````
