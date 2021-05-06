[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  <h2 align="center">E-Commerce</h2>

  <p align="center">
    Back End Development
    <br />
    <a href="https://github.com/anthonyapicella/e-commerce"><strong>Explore the Repo »</strong></a>
    <br />
    <br />
    <a href="https://drive.google.com/file/d/1UDkHNP0ixUJORxL1pV44bhOhSuutHSzH/view">Walkthrough Video</a>
    ·
    <a href="https://github.com/anthonyapicella/e-commerce/issues">Report Bug</a>
    ·
    <a href="https://github.com/anthonyapicella/e-commerce/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

![](/assets/img/backend1.png)
![](/assets/img/backend2.png)

The task was to build the back end for an e-commerce site by modifying starter code. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

>[Repo Link](https://github.com/anthonyapicella/e-commerce) 

>[Walkthrough Video](https://drive.google.com/file/d/1UDkHNP0ixUJORxL1pV44bhOhSuutHSzH/view)

### Built With

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)


## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

![](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white) ![](https://img.shields.io/badge/Insomnia-5849be?style=for-the-badge&logo=Insomnia&logoColor=white)
  ```sh
  npm install npm@latest -g
  ```
* [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

  
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/anthonyapicella/e-commerce.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Seed database:
   ```
   npm run seed
   ```
4. Run application:
   ```
   npm start
   ```

## Usage

When the user adds their database name, MySQL username, and MySQL password to an environment variable file, then the user is able to connect to a database using Sequelize.

When the user enters schema and seed commands then a development database is created and is seeded with test data.

When the user enters the command to invoke the application then the server is started and the Sequelize models are synced to the MySQL database.

When the user opens API GET routes in Insomnia Core for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.

When the user tests API POST, PUT, and DELETE routes in Insomnia Core, then the user is able to successfully create, update, and delete data in the database.

## Contact

Anthony Apicella - anthony.apicella@me.com

[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-apicella-a021301ba/)

[![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anthonyapicella)
