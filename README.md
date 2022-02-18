# E-Commerce-Back-End

<!-- ABOUT THE PROJECT -->
## About The Project

This is a E-commerce backend project, by creating different model and RESTful api routes that interactive with each other, users can use this app to perform CRUD (Create, Read, Update, Delete) operations using your Sequelize models.  



### Built With

* express.js 
* mysql2 
* Sequelize



<!-- GETTING STARTED -->
## Getting Started

Before start, you will need to use the MySQL2 and Sequelize packages to connect your Express.js API to a MySQL database and the dotenv package to use environment variables to store sensitive data.

Once you add your database user name and password in the .env file, run the following command
  ```
  npm install dotenv --save
  npm install mysql2
  npm install
  ```
 
 ### Installation
After the dependencies are installed, use the schema.sql file in the db folder to create your database with MySQL shell commands (Workbench is recomanded).
Of course, you can create your own database as well.
  ```
npm run seed
  ```
Once the data is seeded, you can run 'node server.js' to start the server, then use the insomia to test the route. 

<!-- USAGE EXAMPLES -->
## Demo Video


[![Watch the video](https://img.youtube.com/vi/tMLScCHLedo/maxresdefault.jpg)](https://youtu.be/tMLScCHLedo)

<!-- CONTACT -->
## Contact

Yudong Lu - Linkedin: https://www.linkedin.com/in/yudong-lu/

<p align="right">(<a href="#top">back to top</a>)</p>
