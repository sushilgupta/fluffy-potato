[![Travis Build](https://img.shields.io/travis/sushilgupta/fluffy-potato/master.svg?style=flat-square)](https://travis-ci.org/sushilgupta/fluffy-potato?branch=master)
[![Scrutinizer CI](https://img.shields.io/scrutinizer/g/sushilgupta/fluffy-potato.svg?style=flat-square)](https://scrutinizer-ci.com/g/sushilgupta/fluffy-potato/?branch=master)

Questions' number mapping with related files.

\#1, \#2. `truck.html`, `assets/truck.css` & `assets/truck.js`

\#3. `truck.php`, `src/Truck.php` & `src/TruckCopy.php`

\#4. `group.php`, `src/GroupNumber.php`

\#5. `productionTime.php`, `src/ProductionTime.php`

\#6. `tableJoin.php`, `src/TableJoin.php` & `src/Database.php`.

Please copy the `.env.sample` file to `.env` and fill the database configuration values (create database if not already existss) and execute `tableJoinSchema.sql` file to populate the database for \#6 to work. 