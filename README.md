# technical test

## Instructions

### 1. Clone or download this repo

### 2. Install Node.js

https://nodejs.org/en/download/

### 3. Install and run MySQL Community Server

https://dev.mysql.com/downloads/mysql/  
https://dev.mysql.com/doc/refman/8.0/en/installing.html

### 4. Add root password to \\node-mysql-api\\config.json

Fill in password, as well as put your own secret string for JWT token authentication

### 5. Run installations and node server

In command line / shell (was made and tested on Windows with standard CMD):

```
cd "(project location)\\technical test\\node-mysql-api"
npm install
npm start
```

Open new command line window.

```
cd "(project location)\\technical test\\react-redux-login"
npm install
npm start
```

Above should start the browser. If not, open the browser and go to http://localhost:8080  
There you can register, and if you did, then log in and either delete user data or log out.

## Other mentions

Two separate projects are combined in one to create working system.  
This was done using code found online as a starting point and a template, especially noting the fact that as I said I am new to react.  
I would say "googling stuff" is one of my strengths. Whatever I cannot do, I can google how to do it.
