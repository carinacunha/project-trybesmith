# :crossed_swords: TrybeSmith #
![alt Medieval store](store.jpeg "Medieval store")

In this project, a store of medieval items was created, in the form of an API, using Typescript.

The application was developed following the MSC model (Models, Service and Controllers) and through created endpoints it is possible to perform basic operations such as Create, Read, Update and Delete (CRUD) in a database.

## 🎲 ER and Entity Diagram ##
The relational database, represented in the figure below. Endpoints were developed to connect to the database following REST principles.

![alt Relational database](db.png "Relational database of Blog API")

## :bulb: Guidelines to runnig API ##
This project can be run locally or using docker. Whichever resource you choose, both use environment variables. To runnig this API, follow these steps below:

### :whale: Docker ###
1. Clone the repository 
  - https://github.com/carinacunha/project-trybesmith
  - Go into the repository folder you just cloned
2. make sure you have installed docker version 1.29 or higher
3. Run the node and db services with the command docker-compose up -d --build
4. Create an interactive terminal from the container: docker exec -it blogs_api bash
5. Install the dependencies: npm install

### :computer: Local ###
1. Clone the repository 
  - https://github.com/carinacunha/project-trybesmith
  - Go into the repository folder you just cloned
2. Make sure you have installed node version 16
3. Install the dependencies: npm install
4. Rename the file .env.example to .env and set the environment variables

**:point_right: This project was developed during the Full Stack Web Development course at Trybe.**