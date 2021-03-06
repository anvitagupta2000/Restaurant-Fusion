# Fusion
Fusion is a single-page [AngularJS](https://angularjs.org/)/[Node.js](https://nodejs.org/en/) web application for an indian-based restaurant called Fusion that aims to show restaurant's aviable dishes and make users able to favorite and comment them. The application is built on the [MEAN Stack](https://en.wikipedia.org/wiki/MEAN_(software_bundle)) of technologies and using RESTful web services architecture.

The application was built using [Node.js](https://nodejs.org/en/) runtime. It used [MongoDB](https://www.mongodb.com/) as the underlying database system. It uses [Express](https://expressjs.com/) framework and [Mongoose ODM](http://mongoosejs.com/) toolkit. And in the front-end side, it uses [AngularJS](https://angularjs.org/) to make it [SPA](https://en.wikipedia.org/wiki/Single-page_application).

### Features:
- [Single page application (SPA)](https://en.wikipedia.org/wiki/Single-page_application).
- User registration system.
- Authentication using [JSON Web Token (JWT)](https://tools.ietf.org/html/rfc7519).
- CRUD dishes operations for users with an admin privilege.
- CRUD leaders operations for users with an admin privilege.
- CRUD promotions operations for users with an admin privilege.
- Review (rate and comment) to restaurant's dishes.
- JSON API endpoints for all dishes, reviews, promotions, leaders, and favorites.
- Elegant and responsive UI.

### Prerequisites:
You have to install the following to be able to run and test the application:
- [Node.js](https://nodejs.org/en/).
- [npm](https://www.npmjs.com/).
- [MongoDB](https://www.mongodb.com/).

### Usage:
1. Clone this repository to your desktop, go to its root directory and run:
    ```bash
    npm install
    ```
    ```
2. Create a new folder with the name ```data``` anywhere in your machine and run:
    ```bash
    mongod --dbpath=data
    use fusion
    ```
4. Run the application and go to [localhost:3000] to see the application running.
    ```bash
    npm start
    ```
5. If you want to populate the database with some dummy data go to the ```db``` folder.

### Technologies Used:
- [Node.js](https://nodejs.org/en/): Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.
- [AngularJS](https://angularjs.org/): AngularJS is a JavaScript-based open-source front-end web application framework.
- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [MongoDB](https://www.mongodb.com/): MongoDB is a free and open-source cross-platform document-oriented database program.
- [Mongoose ODM](http://mongoosejs.com/): Mongoose provides a straight-forward, schema-based solution to model data.
- [Passport](http://passportjs.org/): Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken): An implementation of [JSON Web Tokens](https://tools.ietf.org/html/rfc7519).
