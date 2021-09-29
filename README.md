# 13-ObjectRelationalMapping-eCommerceBackEnd_usingExpress.jsMySQLAndSequelize


## Task
Build the back end for an e-commerce site by modifying starter code to configure a working Express.js API to use Sequelize to interact with a MySQL database.

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit any full-stack web developer.


## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
✓ WHEN I add my database name, MySQL username, and MySQL password to an environment variable file THEN I am able to connect to a database using Sequelize
✓ WHEN I enter schema and seed commands THEN a development database is created and is seeded with test data
✓ WHEN I enter the command to invoke the application THEN my server is started and the Sequelize models are synced to the MySQL database
✓ WHEN I open API GET routes in Insomnia Core for categories, products, or tags THEN the data for each of these routes is displayed in a formatted JSON
✓ WHEN I test API POST, PUT, and DELETE routes in Insomnia Core THEN I am able to successfully create, update, and delete data in my database
```

## SOLUTION:

🎥 [Demonstration Video Link - Demonstration](https://drive.google.com/file/d/1sb-64L05qkHnmef4r63L3pS5Fher6w-9/view?usp=sharing) 
🎞️ [Gif Demonstartion](./Assets/13-ObjectRelationalMapping-eCommerceBackEnd_usingExpress.jsMySQLAndSequelize.gif)
🎞️ [Gif Demo1](./Assets/13-orm-homework-demo-01.gif)
🎞️ [Gif Demo2](./Assets/13-orm-homework-demo-02.gif)
🎞️ [Gif Demo3](./Assets/13-orm-homework-demo-03.gif)

## Usage Instructions

Use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create a database with MySQL shell commands & use environment variables to store sensitive data like MySQL username, password, and database name.
