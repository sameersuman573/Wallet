
1.npm init
2.Git repo Creation
3.git keep creation in public/temp and git ignore creation 
4.copy the necessary files from git ignore generator 
5.create .env file and src
6.creation of file in src app.js , constants.js , index.js
7.In package.json - in type write module , for server start install nodemon as dev dependency -
npm i -D nodemon
7.Write script as - "scripts": {
    "dev": "nodemon src/index.js"
  },
8.Install dotenv 