# Dang Thats Delicious
Here, you can find resources for installing and using the project

## Resources
* Make sure to have [Node](https://nodejs.org/en/) installed. Make sure to have Version 7.6 or above.
* ```node -v``` in your terminal to check what version of Node you have installed on your computer.
* Make sure to have [NPM](https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm) installed to install all of the dependencies needed for the project.

## Installation
Clone the GitHub repository and use NPM to install the dependencies.
```
git clone https://github.com/paulcarrillo/dangthatsdelicious.git dangthatsdelicious
cd dangthatsdelicious
npm install

```

## mongodb DATABASE
You will need a database for the project. The application is set up to use [mongodb](https://mlab.com/)
* Create a mLab account
* Select Sandbox in would like a free storage
* Select MongoDb Version 3.2x(MMAPv1)
* Name your Database
* Intall mongodb compass on your computer to manage data within your application.

## Start application
* use ```npm start``` on terminal to start the application

## Loading Sample Data

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100% clean with:

```bash
npm run blowitallaway
```
