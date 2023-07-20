# ORM E-commerce Back End

## Description
This back end database has been created for e-commerce websites using a functional Express.js API and Sequelize to interact with a MySQL database. The back end application allows users to create the schema, seed the database, and sync Sequelize models to the MySQL database on server start. The application utilizes object-relational mapping for interaction with the database to perform operations such as data manipulation, storage, and retrieval.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Video](#video)
* [License](#license)
* [Questions](#questions)  
  
## Installation
- `Dotenv`: [8.2.0](https://www.npmjs.com/package/dotenv)
- `Node.JS`: [16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- `Express`: [4.17.1](https://www.npmjs.com/package/express)
- `MySQL2`: [2.1.0](https://www.npmjs.com/package/mysql2)
- `Sequelize`: [5.21.7](https://www.npmjs.com/package/sequelize)
- `Insomnia`: [Download](https://insomnia.rest/download)

## Usage
Use the following commands at the root of your project to get started:
1. Run the command `npm i` to install dependencies.
2. Type `mysql -u root -p` and enter password when prompted.
3. Use the `schema.sql` file in the `db` folder to create your database by using MySQL shell command `source db/schema.sql` in terminal.
4. Type `quit` to exit.
5. Run `npm run seed` to seed data to your database.
6. Enter `node server.js` or `npm start` command to start the server.
7. Once connected to localhost, a 'Now Listening' message should appear.
8. Use Insomnia to open http://localhost:3001 and test API `GET` routes for categories, products, or tags to display data. 
9. Test API `POST`, `PUT`, and `DELETE` routes to perform create, update, and delete operations in the database.

## Video
The following walkthrough videos demonstrate the functionality of the e-commerce back end:
1. The first video demonstrates the command line usage on
- how to create the schema from the MySQL shell
- how to seed the database
- how to start the application's server

https://github.com/suzyhan/e-commerce-back-end/assets/129558186/b55221e2-8379-4034-be6c-b353f937f881

<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="path/to/poster_image.png" muted="" loop="" autoplay="">
    <source src="assets/e-commerce-back-end.mp4" type="video/mp4">
  </video>
</figure>

2. The second video demonstrates the API routes in Insomnia:
- `GET` routes for all categories, all products, and all tags being tested
- `GET` routes for a single category, a single product, and a single tag
- `POST`, `PUT`, and `DELETE` routes for categories, products, and tags

https://github.com/suzyhan/e-commerce-back-end/assets/129558186/b35939dc-33ef-46b2-8b8d-d167113ba8c8

<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="path/to/poster_image.png" muted="" loop="" autoplay="">
    <source src="assets/insomnia-tests-routes.mp4" type="video/mp4">
  </video>
</figure>

## License
None

## Questions
Please email me with any questions or visit my GitHub profile using the links provided below.
* GitHub: [suzyhan](https://github.com/suzyhan)
* Email: [suzyahan@gmail.com](mailto:suzyahan@gmail.com)