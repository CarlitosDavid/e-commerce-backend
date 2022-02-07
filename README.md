# E-commerce-backend

    Object-Relational Mapping (ORM): E-Commerce Back End.
    A mysql database and application for a online retail store or E-commerce site.
    applaction connects using Sequelize.
    E-commerce is the largest sector of electronic industy, having generated an estimated US$29 trillion in 2017. (Source: United Nations Conference on Trade and Development).
    Homework 13 challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

# Application:

    when enter schema and seed commands.
    development database is created and is seeded with test data when enter
    command to invoke the application.  My server started and the Sequelize
    models are synced to the MySQL database. When the API GET routes in
    Insomnia for categories, products, or tags. The data for each of these
    routes is displayed in a formatted JSON. When test API POST, PUT and
    DELETE routes in Insomnia then you would be able to create, update, and
    delete data in your database.

# Installation

    npm init
    npm intall mysql2
    npm install sequelize
    npm intall dotenv.
    Once you have all installation run mysql -u root -p in your terminal in your root directory.
    next enter in mysql>
    source db/schema.sql
    quit
    next in terminal in root directory
    npm run seed
    npm start.
