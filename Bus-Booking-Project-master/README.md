# Bus-Booking-Project

A Bus ticket booking application made using MERN Stack (MongoDB, Express js, React js, Node js)

The ticket Booking system is a web-based application that allows users to book Tickets for a bus. It provides a platform where users can easily book a ticket for the bus. The system aims to streamline the process of ticket booking.


<p align = "center">
<img src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" alt="js" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/nodejs.png" alt="nodejs" width="50" height="50"/>
<img src="https://res.cloudinary.com/kc-cloud/images/f_auto,q_auto/v1651772163/expressjslogo/expressjslogo.webp?_i=AA" alt="express" width="50" height="50"/>
 <img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/mongodb-leaf.png" alt="mongo" width="50" height="50"/> 
<img src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" width="50" height="50"/>
  
</p>

[Here](http://booktic.pinterest.com/) is the link of Bus-Booking-Site.

[Here](https://businessbus.pinterest.com/) is the link of Business portal of this site for adding buses.


## Deployment

* [Visual Studio Code](https://code.visualstudio.com/) - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [SCSS](http://sass-lang.com/) - A css metalanguage
* [Bootstrap 4](https://getbootstrap.com/) - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
* [Express js](http://expressjs.com/) - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
* [MongoDB atlas](https://www.mongodb.com/cloud/atlas) - MongoDB Atlas is the global cloud database service for modern applications.
* [Passport Js](http://www.passportjs.org/) - Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application.
---


The Bus ticket application is composed of the following Features:

### Front-End

* Sign-In & Sign-Up Pages.

* Uses Token based system, so only registered users can access the website  passport js.

* Password hashing using passport js.

* Has a profile page, which will display all information about the signed in user.

* List of cities for users to choose from (starting city & destination city). 

* Getting list of bus's of different companies with various details.

* Seat selection page has a very user friendly environment, which also generates dynamic forms for storing data's of passengers.

* Has a Confirmation page, which gets a debit card data using react-credit-cards. This version of the application does not include handling the payment process. 

* Final page has a ticket displaying component, it displays all passenger data and also generates a random number as a transaction ID.

### Back-End

* Uses Express js based application for the backend process.

* Uses MongoDB atlas for storing the collections.

* Uses passport js for authenticating user and token based system.

* Uses passport js for hashing the password before sending the data to the cloud.

* This version does not support dynamic seat data being stored from cloud.



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Install

Follow the following steps to get development environment running.

* Clone _'Bus-Booking-Project.git'_ repository from GitHub

  ```bash
  git rep https://github.com/2000030390/Bus-Booking-Project.git
  ```

   _OR USING SSH_

  ```bash
  git rep git@github.com:2000030390/Bus-Booking-Project.git
  ```
 #### Search list of Buses from one city to another city
```javascript
POST http://localhost:3000/api/bustic/search
```

  #### Book the ticket
```javascript
POST  http://localhost:3000/api/bustic/book/id
```

  #### Delete ticket from cart 
```javascript
DELETE http://localhost:3000/api/bustic/cart/${id}
```

 #### To get all booked ticket
```javascript
POST http://localhost:3000/api/bustic/book
```

  #### Cancel the booked ticket 
```javascript
DELETE `http://localhost:3000/api/bustic/book/${id}
```

* Install node modules

   ```bash
   cd MERN-BUS-APP
   cd client
   npm install
   cd..
   npm install
   ```


### Starting both front end and back end servers

* Build application

  This command will start the mongodb and the front end part.

  ```bash
  
  npm run dev

  ```

 ### USERS DATA/ LOGIN DATA

```javascript
{
  email:divyajetti08@gmail.com
  password:123456
}


```


