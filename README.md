How to run tripmate-api locally :

1. move to tenan-api folder
$ cd tripmate-api
2. run NPM install
$ npm install
3. Edit the environment variable in .env file
MONGODB_LOKAL = mongodb://127.0.0.1:27017/capstone
MONGODB_ATLAS = mongodb+srv://example.url
PORT = 5000
HOST = smtp.gmail.com
USER = pinastirobiaulia@mail.com
PASS = passs
BASE_URL = http://localhost:5000
SERVICE = gmail
4. Create database and tables from database/database.sql
5. run NPM run start-dev
$ npm run start-dev
