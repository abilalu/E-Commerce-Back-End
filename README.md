# E-Commerce-Back-End
## Description
Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

In this activity i am building the back end for an e-commerce site by modifying starter code. I will configure a working Express.js API to use Sequelize to interact with a MySQL database.

## User Story
As a manager at an internet retail company
I want a back end for my e-commerce website that uses the latest technologies
So that my company can compete with other e-commerce companies
## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize.

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data.

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database.

WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON.

WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Packages Used
* Connects to a MySQL database using the [MySQL2](https://www.npmjs.com/package/mysql) and [Sequelize](https://www.npmjs.com/package/sequelize) packages.

 * Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the [dotenv](https://www.npmjs.com/package/dotenv) package.
 
 ## Walkthrough Video
 A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met is attached: https://drive.google.com/file/d/1SHPMry0pobaDNJY6l7rdVGvBoEaL8elc/view