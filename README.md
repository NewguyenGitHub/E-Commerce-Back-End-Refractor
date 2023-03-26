# E-Commerce-Back-End-Refractor

## URL
N/A

## Description

This project is an object-relational-mapping file for an E-Commerce store that tests API routes using Insomnia.
The project will connect to a database using Sequelize.
The project will create a database and seed it with test data.
The project will server will sync the Sequelize models to the MySQL database.
The project will allow data for the GET, POST, PUT, & DELETE routes will be displayed using Insomnia.

## Summary

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

npm init -y
npm install mysql12
npm install sequelize
npm install dotnev

mysql -u root -p
source db/schema.sql
npm run seed
npm start

## Usage

This is an object-relational-mapping file for an E-Commerce store that tests API routes using Insomnia.

[E-Commerce-Back-End-Walk-Through]()

[E-Commerce-Back-End-Category-Routes](assets/demo/CategoryRoutes.gif)

[E-Commerce-Back-End-Product-Routes](assets/demo/ProductRoutes.gif)

[E-Commerce-Back-End-Tag-Routes](assets/demo/TagRoutes.gif)

## Credits

N/A

## License

Please refer to the LICENSE in the repo.
