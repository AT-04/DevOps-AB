# Laravel PHP VueJs

This is a basic CRUD Application. Which utilizes frontend of VueJS and backend of Laravel PHP.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Requirements
* Lamp or Xamp Server
* Composer
* A Sql Database: Sqlite, MySql, PostgreSql
* NodeJs

### Follow the steps

1) Clone the repository
2) Type the following command in your project root directory

```
$ composer install
```
3) Rename **.env.example** file to **.env** and setup the configuration
Using Sqlite:
4) Create a file in database/database.sqlite
5) The configuration for the database should look like in **.env** file:
```
DB_CONNECTION=sqlite
```
6) Migrate the database initial setup:
```
$ php artisan migrate
```
7) Generate the application key:
```
$ php artisan key:generate
```
