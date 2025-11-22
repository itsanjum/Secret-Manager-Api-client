## Secret Manager API Client

This project is a web application built with Express.js that interfaces with the Secrets API.
It enables users to perform CRUD (Create, Read, Update, Delete) operations on secrets via a simple web interface using forms.

Features
Retrieve secret by ID

Add new secrets

Update existing secrets completely or partially

Delete secrets

Uses Axios for API requests with bearer token authentication

Form-based user interface rendered with EJS

Installation
Clone the repository
git clone https://github.com/your-username/secret-manager-api-client.git

Navigate into the project directory
cd secret-manager-api-client

Install dependencies
npm install

Update the bearer token in index.js with your own Secrets API token

Usage
Start the server:

bash
node index.js
Open your web browser at http://localhost:3000 and use the form to interact with the Secrets API.

File Structure
index.js - Main application file with Express server and routes

views/index.ejs - EJS template for the web interface

public/ - (optional) Folder for static assets like CSS if added

Dependencies
Express.js

Axios

body-parser

EJS

