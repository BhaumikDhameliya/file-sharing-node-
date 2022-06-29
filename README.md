# File Sharing
## _share file smoothly_

## Features
- upload any file
- set password to the file
- download file anytime

## Tech

File sharing uses a number of open source library to work properly:

- [node.js] - back-end JavaScript runtime environment, used to build scalable network applications.
- [Express] - back end web application framework for Node.js
- [mongodb] - document-oriented datbase, used to store data in documents
- [mongoose] - connection between MongoDB and the Express, used to model application data
- [multer] - node.js middleware for handling multipart/form-data, used for uploading files
- [ejs] - simple templating language that helps to generate HTML markup with plain JavaScript.
- [bcrypt] - password-hashing function, used to store password data in database
- [dotenv] - Loads environment variables from .env file.

## Installation

To run File sharing project, requires [node.js] and [mongodb] installed to local system.

- clone git repository

create .env file to the root of the project
- define following in the .env file
```
DATABASE_URL=mongodb://127.0.0.1/fileSharing
PORT=3000
```


- run the following commands in terminal

```sh
npm install
```
For development environments...

```sh
npm run devStart
```

For production environments...

```sh
npm run start
```

   [node.js]: <https://nodejs.org>
   [express]: <https://expressjs.com>
   [mongodb]: <https://www.mongodb.com>
   [mongoose]: <https://mongoosejs.com>
   [bcrypt]: <https://www.npmjs.com/package/bcrypt>
   [multer]: <https://www.npmjs.com/package/multer>
   [dotenv]: <https://www.npmjs.com/package/dotenv>
   [ejs]: <https://ejs.co/>
   
