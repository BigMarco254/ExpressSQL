# 📚 ExpressSQL | Basic guide

Very basic ExpressJS project showing the relationship between client and server. The client uses JQuery to get and post data view AJAX requests.

## 💻 Install
**Note**: Make sure your MySQL and Node installed.


In the command terminal, run the following commands:

    $ git clone https://github.com/BigMarco254/ExpressSQL.git express_sql
    $ cd express_sql/
    $ npm install
    $ mysql -u root -p < server/schema.sql
    $ npm start
After running ```npm start``` navigate to http://127.0.0.1:3000/


## ❌ Troubleshooting Errors:
* ```OperationalError: connect ECONNREFUSED 127.0.0.1:3306```
  * MySQL server is not running
* ```OperationalError: ER_BAD_DB_ERROR: Unknown database 'simple'```
  * Need to run ```mysql -u root -p < server/schema.sql```