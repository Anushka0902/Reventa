<h1 align="center">
    <b>Reventa in<br> Node.js using MongoDB </b> 
<br>
</h1>


<p align="center">



## What is this for?
This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.

## Getting Started

this is a prototype

## Running the tests

### •Registration Form:
Allows the user to register their account by filling their Email, Username, Password.


### •Login Form:
If the user has been registered on the app, can login by passing the credentials.

<img src="./docs/login.PNG" height="220" width="390" style="border: 1px solid black;">

### •User's Profile:
After the user logged in, a simple profile with the user's username and password <br>displayed with a session Logout button.

### •Shop portal:
for resellng items one stop shop and which is economcal and affordable way
### •Rent portal:
for short span needs of user and required items are charged accordngly 




### DataBase:
Here we use **[MongoDB Atlas(Cloud)](** as the database. Here we have two collection created, named as:
- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.



A Collection(**session**) is created which stores the users Logged session.


<br>
<br>

## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***

## Installing
```
npm install
```
## Connection to DataBase Access
At line 11 on ```./server.js``` change ***```<DB_USERNAME>```*** with your DataBase UserName & ***```<DB_PASSWORD>```*** with your DataBase Password.

## To Run the App
```
node server.js
```

The server will start Running on
+ http://localhost:3000/



  Made with ❤️ by <a href="https://github.com/guruhariharaun">Guru Roxz</a>
</p>
