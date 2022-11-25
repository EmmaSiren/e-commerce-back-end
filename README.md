# <e-commerce-back-end>
# **E-Commerce Back End**

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-5849be?style=for-the-badge&logo=Insomnia&logoColor=white)


## **Description**

This application serves as an example of an e-commerce company’s back end database. It will be used to keep track of a company’s categories, products, tags, prices, stock quantity, etc. It uses the MySQL database along with Express, Sequalize, DotEnv, and Node. This application will also be able to run seed commands from a javascript file rather than manually seed information through the MySQL shell. Insomnia can be used to easily view the CRUD operations for Categories, Products, and Tags. 

I started with setting up the requirements for each model then wrote association methods on them to create relationships between the models using their foreign keys. Once exported, they are imported into each api route file where I filled out methods for the Create, Read, Update, Delete operations for each. As this was an assignment with starter code, the Product’s Create and Update operations were already filled out so I implemented similar strategies for the Category and Tag operations. Finally, I added the code to sync Sequelize models to the database on server start. 


## **Installation & Usage**
Initiate Node by running ‘npm i’ in the GitBash terminal. Make sure to run the MySQL shell, enter your credentials, then run the Schema commands for the database. Once all packages have been installed run ‘npm run seed’ command to seed your database then ‘npm run start’ to start up the server. Now go to Insomnia and test out the various GET, POST, PUT, and DELETE routes for Categories, Products, and Tags. See below for walkthrough video. 

[Walkthrough Video](https://drive.google.com/file/d/1Df3_5y4zt4fHChV8VjdbnnP_yRaIRjse/view?usp=sharing)
