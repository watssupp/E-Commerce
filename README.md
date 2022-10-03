# E-Commerce

## Walk thru
https://drive.google.com/file/d/1mReox-myQYXj74Uo4Vt6JYLqPHcDvYe3/view

## Description
This is the back end for an E-Commerce site using Express.js API, Sequelize and interacting with MySQL

## Usage
Using a Cross-Platform Desktop Framework for testing RESTful applications (Insomnia, Postman) you will be able to do the following
- With Categories
    - View all categories
    - View categories by id
    - Add categories
    - Update categories
    - Delete categories 
- With Product
    - View all product
    - View product by id
    - Add product
    - Update product
    - Delete product 
- With Tags
    - View all tags
    - View tags by id
    - Add tags
    - Update tags
    - Delete tags 

## ScreenShots
![Alt](/img/e_commerce%20pic%201.png)
![Alt](/img/e_commerce%20pic%202.png)

## Istructions to run application
Create an .env file with the following 
```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'
```
Open the terminal and install your dependencies with
```
npm i
```
run mysql in the terminal with 
```
mysql -u root -p
```
with in mysql you will input the follow steps
```
- source db/schema.sql;
- show databases;
- quit; 
```
Once your out of mysql in the terminal youll need to run the seeds with the next comand
```
npm run seed
```
Now your ready to run the appliaction in this final step
```
npm start
```
Have fun and enjoy!