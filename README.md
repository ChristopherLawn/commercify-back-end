# Commercify: Back-End

## Description
A fully built back-end structure that serves as a base for creating an e-commerce site! Commercify provides the built-in functionality to view, create, update, and delete item categories, products, prices, and keyword description tags. Use Commercify as the foundation to build your online shop today!

## **Table of Contents**
* [Programs](#programs)
* [Installation](#installation)
* [Usage](#usage)
* [Demo](#demo)
* [License](#license)
* [Questions](#questions)

## **Programs**
* dotenv package
* Express package
* Inquirer package
* JavaScript
* MySQL2 package
* Node.js
* Sequelize

## **Installation**
1. In order to run the application, download & install [Node.js](https://nodejs.org/en/download/) on your local device.  ***Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.***
2. After installing Node, clone the [Commercify: Back-End repo](https://github.com/ChristopherLawn/commercify-back-end) to a project folder on your local device.
3. Open Bash and navigate to the root directory of the project folder.
4. Install all required dependencies for the project by entering the command:
    * `npm install`

## **Usage**
1. Before using the app:
    * Check the connection settings in the `connection.js` file - located in the `config` folder
    * Create an `.env` file in the main directory of your project folder and include:
        * DB_NAME='ecommerce_db'
        * DB_USER=`*<Your MySQL Username>*`
        * DB_PW=`*<Your MySQL Password>*`
2. Set up the seed files to populate your database:
    * In bash, navigate to the root directory of your project folder
    * Log into MySQL by entering the command `mysql -u *<Your MySQL Username>* -p` then entering your MySQL password
    * Enter the following command to run the SQL schema file to set up the `ecommerce_db` database:
        * `source db/schema.sql;`
    * Once the database is initiated without any error(s), run the command `quit;` to exit MySQL
        * Make sure to include a semicolon(`;`) at the end of all SQL commands
    * To seed the test data for category, product, product-tag, and tag files, enter the following command in Bash:
        * `node seeds/index.js`
        * Check the response in Bash to confirm that all tables were properly seeded without error(s)
3. To initiate the program and start the server, enter the command:
    * `npm start`
4. Use Insomnia to test all CRUD routes for categories, products, and tags
5. Enter `Ctrl`+`c` to exit out of the server
6. Use Commercify as the foundation for your back-end then build your front-end and deploy your site!
7. Click the link below to watch the "Commercify: Back-End Demo" video to see the CRUD routes for categories, products, and tags in action!

## **Demo**
['Commercify: Back-End' Demo Using Insomnia](https://drive.google.com/file/d/1vCPHQcDBZtvNFthniYY8SXJyazUmtkyu/view?usp=sharing)

## **License**
The project is distributed under the [Creative Commons License](https://creativecommons.org/publicdomain/zero/1.0/)

## **Questions**
Please contact me directly with any additional questions:
* [GitHub](https://github.com/ChristopherLawn)
* [Email](mailto:christopher.d.lawn@gmail.com)