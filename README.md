# Mongo-DB


## How to set up a Database and Web Server for a SwiftUI App


The actual database is not core data which is what you will usually expect for an App.



The XCode/Iphone app sending and retrieval configuration diagram: 

![](./Mongo-Configuration/configurationdiagram.jpeg)



## Definition


- [Homebrew](https://brew.sh/) - a free and open-source package management system that simplifies the installation of software on macOs operating system and Linux) in your terminal. 
- [MongoDB](https://www.mongodb.com/docs/manual/installation/) - is a document database used to build highly available and scalable internet applications. With its flexible schema approach.
- [Node.js](https://nodejs.org/en) - to create server-side web applications, and it is perfect for data-intensive applications since it uses an asynchronous, event-driven model.
- [Express.js](https://expressjs.com/en/starter/installing.html) - is a node js web application framework that provides broad features for building web and mobile applications. It is used to build a single page, multipage, and hybrid web application. It's a layer built on the top of the Node js that helps manage servers and routes.
- [Postman](https://www.postman.com/downloads/) - Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.
- [Mongoose](https://www.npmjs.com/package/mongoose) - Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more. Mongoose supports Node.js and Deno (alpha).

## Installation 

Homebrew
````
- /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
````
MongoDB
````
- brew tap mongodb/brew
- brew install mongodb-community@6.0
````
Node.js
````
- brew install node 
- node -v 
````


