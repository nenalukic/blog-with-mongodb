# Personal Blog Website

Simple Blog application with Node.js and MongoDB as the back end.

<br/>

## Installation
This application requires MongoDB database. 

To install MongoDB on Mac type:
```
brew install mongodb
```
To install MongoDB on Windows - follow instructions n this link:
[Install MongoDB on Windows](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)

<br/>

## Create database objects

Start Mongo shell by typing:
```
mongo
```
Create new database called "blogDB":
```
use blogDB
```
Create collection called "posts" inside "blogDB" database:
```
db.createCollection("posts")
```
<br/>

## Usage

While in application directory, to run the applicatin open a terminal and type:
```
nodemon
```
To see the blog posts go to:
[https://localhost:3000](https://localhost:3000)

To create new blog entries go to:
[https://localhost:3000/compose](https://localhost:3000/compose)

<br/>

## Sample screens of the application

Blog main page:
![image](images/mongo-blog-1.png?raw=true)

Create new blog entry:
![image](images/mongo-blog-2.png?raw=true)

## Acknowledgment

I created this project while studying [Udemy online bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/).
