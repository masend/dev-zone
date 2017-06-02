# Getting MEAN application code

This is the code for the sample 'Loc8r' application that is built through the course of my book [Getting MEAN](https://www.manning.com/books/getting-mean-with-mongo-express-angular-and-node).

Getting MEAN is published by Manning, and teaches readers how to develop web applications end-to-end using the MEAN stack.

## The application at various stages

There are named branches for the various states of the code throughout the book:

* `master` **Chapter 3 start**: A blank Express 4.9.0 project
* `chapter-03` **Chapter 3 end**: Creating and setting up a MEAN project
* `chapter-04-views` **Chapter 4 mid-point**: The data is hard coded into views
* `chapter-04` **Chapter 4 end**: Building a static site with Node.js and Express
* `chapter-05` **Chapter 5**: Building a data model with MongoDB and Mongoose
* `chapter-06` **Chapter 6**: Writing a REST API: Exposing your MongoDB database to the application
* `chapter-07` **Chapter 7**: Consuming a REST API: Using an API from inside Express
* `chapter-08` **Chapter 8**: Adding Angular components to an Express application
* `chapter-09` **Chapter 9**: Building a Single Page Application with Angular: Foundations
* `chapter-10` **Chapter 10**: Building a Single Page Application with Angular: The next level
* `chapter-11` **Chapter 11**: Authenticating users, managing sessions and securing APIs

## Get the code

To get the code for a specific branch:

`$ git clone -b branch-name https://github.com/simonholmes/getting-MEAN.git`

Then change into the folder the git clone command will create:

`$ cd getting-MEAN`

And finally install the dependencies:

`npm install`

Mean Stack Notes

Update brew:
$ brew update
$ brew doctor

Install Node:
$ brew install node
$ npm install -g grunt-cli

Install Express:
$ npm install -g express-generator

If $ express results in express command not found use the output of the install to locate the bin path of express and export that to the $PATH. e.g. export PATH=/usr/local/share/npm/bin:$PATH

Install Mongo DB:
$ brew install mongodb
mongod --config /usr/local/etc/mongod.conf
/usr/local/Cellar/mongodb/3.4.4

Create a directory which mongod will use to write data:
$ sudo mkdir -p /data/db

Run mongo:
$ sudo mongod

Install AngularJS
$ npm install angular@1.6.4

$ git clone -b chapter-03 https://github.com/simonholmes/getting-MEAN.git 
npm install

Npm start

bson = require('../build/Release/bson');

P@ssword123
Password!@#

P@ssword1234

devlogger
localsocket

$ touch .gitignore

git push heroku master


$ npm install --save mongoose


Mongo
use Loc8r;
show dbs;
show collections;
db.locations.find();

db.locations.save({
name: 'Starcups',
address: '125 High Street, Reading, RG6 1PS', rating: 3,
facilities: ['Hot drinks', 'Food', 'Premium wifi'], coords: [-0.9690884, 51.455041],
openingTimes: [{
    days: 'Monday - Friday',
    opening: '7:00am',
    closing: '7:00pm',
    closed: false
  }, {
    days: 'Saturday',
    opening: '8:00am',
    closing: '5:00pm',
    closed: false
  }, {
    days: 'Sunday',
    closed: true
  }]
});
