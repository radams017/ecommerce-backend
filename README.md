# Ecommerce Backend

## Description
- This application allows for the updating of an ecommerce backend database
- Through RESTful CRUD operations, you are able to create, read, update, and delete various portions of the database.
- There is no front-end to this application, functionality is carried out purely through Insomnia.

## How To Use
- Prior to utilziing this application, make sure that you have all of the dependencies correctly installed by running 
```bash
npm i
OR
npm install
```
- Additionally, make sure that you have MySQL installed on your device.
    - Make sure to create the database on your device correctly by utilizing the schema included in the DB folder.
- Make sure you set up a .env file as well, including DB_NAME, DB_USER, and DB_PASS (if applicable)
- Once the schema has been run, run the below to seed the database.
```bash
npm run seed
```
- To intialize the application, run 
```bash
node server.js
OR
nodemon server.js
OR 
npm run start 
```
- The above will initalize the server and allow for GET/PUT/POST/DELETE functionality, all of which is illustrated in the demo video below.

## Demo Video
[Click To Open Demo Video](https://drive.google.com/drive/folders/1sDfDqKQLjNtqEEpdJFJa_TZAft93Z8Ce?usp=sharing)

## License
MIT