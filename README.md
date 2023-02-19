# ORM-eCommerceBackend

## Description

This app was created as an exploration of ORMs, focusing on data relationships to create a backend product management system for an ecommerce system. It
allows users to operate CRUD functions on products, tags, and categories. The most difficult part was getting routes to work as intended and stop returning
errors as I learned the syntax better.

## Installation

This App requires the installation of the MySQL Shell and Node.js. Instructions on their installation can be found on their respective websites.

In the command line, run 'npm install' Then open the MySQL shell and run: 'SOURCE ./db/schema.sql;' 
Exit the MySQL shell.
If you wish to load the sample data, run 'npm run seed'.
From here, the app can be initialized thorugh 'node server.js'

## Usage
Routes can be found in the ./routes/api folder. Usage of Insomnia is reccommended for interacting with the database.

## Credits

N/A

## License

refer to LICENSE.md
