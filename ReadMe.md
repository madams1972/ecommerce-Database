![MIT license badge](https://img.shields.io/badge/license-MIT-blue)

## Description

This project is the back end for an e-commerce website. It includes a database of sample items and the api endpoints to perform CRUD operations on that data.

## Table of Contents

[Installation](#installation)

[Usage](#usage)



## Installation
You will need to run the **schema.sql** file from the mysql shell. Then use **npm run seed** to seed the database with some sample data. Once you've got your credentials set up in a **.env** file you can run **npm start** to sync the database and start the server.

## Usage
This application is only the back end. Once the server is running use **/api/products**, **/api/categories**, and **/api/tags** with different HTTP requests to interact with the database.

A walk-through video can be found [here]