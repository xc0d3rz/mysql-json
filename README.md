# mysql-json
=========

Simple Node.js mysql module

## Installation

  npm install mysql-json

## Usage

  var MysqlJson = require('mysql-json');
  var mysqlJson = new MysqlJson({
    host:'127.0.0.1',
    user:'root',
    password:'root',
    database:'myDatabase'
  });

  // Query method
  mysqlJson.query("SELECT * FROM users WHERE login LIKE '%admin%'", function(err, response) {

  });

  // Insert method
  mysqlJson.insert('myTable', {

  });

  // Update method
  mysqlJson.update('myTable', {

  });

  // Delete method
  mysqlJson.delete('myTable', {

  });


## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release