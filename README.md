# IMS
Inventory Management System using MEAN(Mongo DB, ExpressJS, AngularJS, NodeJS) stack

The purpose of the Inventory Management System (IMS) is to provide an efficient and enhanced way to manage a business’s Inventory. 
The following features are within the scope:-
- Define and manage the organization’s warehouse hierarchy.
- Define & configure Items, categories and attributes
- Creation of Vendors
- Upload Inventory procured from the supplier
- Track physical warehouse transfers
- Track the lost & damaged  items found during transfer of stock between warehouses
- Define, track & extend the warranty of Inventory
- Inventory lifecycle management
- Report Generation
- User Management

### Technological aspects
The application I will develop is a basic Inventory management application that supports standard CRUD (Create, Read, Update, Delete) operations. First, I’ll create a RESTful API server to act as an interface for querying and persisting data in a MongoDB database. Then, will leverage the API server to build an Angular-based web application that provides an interface for end users.

The important files/folders that I’ll be directly modifying are listed below-

[package.json](https://github.com/shivangiG/IMS/blob/shivangiG-IMS1/package.json)
A configuration file that contains the metadata for the application. When there is a package.json file in the root directory of the project.

[app.json](https://github.com/shivangiG/IMS/blob/shivangiG-IMS1/app.json)
A manifest format for describing web apps. It declares environment variables, add-ons, and other information required to run an app on Heroku. It is required to create a “Deploy to Heroku” button.

[server.js](https://github.com/shivangiG/IMS/blob/shivangiG-IMS1/server.js)
This file contains all the server-side code used to implement the REST API. The API is written in Node.js, using the Express framework and the MongoDB Node.js driver.

/src directory
This folder contains all of the AngularJS client code for the project.

