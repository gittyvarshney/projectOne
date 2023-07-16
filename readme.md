# Cosmology Forum
## Build Using MERN STACK
![Comology Platform](https://raw.githubusercontent.com/gittyvarshney/projectOne/master/cosmology_bg.png?raw=true)

## Backend:

-   ExpressJS is used for Request control </br>
-   Mongoose is used for Object Relation Model </br>
-   MongoDB is used as Database </br>

### Design

![BE Design](https://raw.githubusercontent.com/gittyvarshney/projectOne/master/backend_design.jpg?raw=true)

### Other Libraries Used:
-   cors
-   bcryptjs
-   body-parser
-   dotenv
-   morgan

## Frontend:

-   ReactJS is used as core framework  </br>
-   Bootstrap 4 is used for styling </br>
-   FontOwesome is used for Icons </br>

### Design
![FE Design](https://raw.githubusercontent.com/gittyvarshney/projectOne/master/frontend.png?raw=true)

### Other Libraries Used:
-   axios
-   styled-components
### Open API
[Solaire](https://api.le-systeme-solaire.net/)

## Steps to SetUp

-   Install [MongoDB](https://www.mongodb.com/try/download/community) server for OS
-   Create a Database named project_db or some other & create a dummy collection
    ```
    > use project_db
    > project_db.dummy.insert({name: "Random", age: 23})
    ```
-   In backend Directory create a file named .env
    ```
    PORT=4000 (or any other port you like)
    DB_URL=mongodb://127.0.0.1:27017/project_db (port on which mongoDB server is running)
    ```
-   In backend directory hit npm start
-   In frontend directory hit npm start




