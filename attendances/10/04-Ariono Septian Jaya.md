Ariono Septian Jaya
TI 3H

## Working on the Flutter API using Laravel
The steps for making GET API categories that I did:

1.Creating a flutter_api database on mysql.
2.Create a laravel flutter_api project.
3.Create models and migrations from the categories table.
4.Fill in the categories table with one data
5.Create a controller with the name CategoryController
6.Fill in the index function to get all data from the categories table
7.Create Route get on api.php with url categories
8.Get API test using postman

## Steps to work on api routes:

1.In CategoryController create a function index_v2 to get all data from the categories table, but only the id and name are displayed
2.Create api_v2.php file in routes . folder
3.Create a get route in the api_v2 file and call the index_v2 function from CategoryController
4.On RouteServiceProvider create Route Prefix which points to url api/v2
5.Tried api v2 on postman

## RESTful API Material

RESTful API is an API (Application Program Interface) architecture that employs HTTP queries to access data. The HTTP methods GET, PUT, POST, and DELETE relate to read, update, create, and delete activities on the resource, respectively. RESTful or REST HTTP responses, in addition to HTTP methods, are also used to describe the response data received.
On a RESTful API, authentication is a little different than on the web. There is no known session in the RESTful API. Tokens are typically used to replace sessions. In most cases, this token is included in the HTTP request header. API development and token creation are already supported by the Laravel framework.You can use Laravel Sanctum to make building a RESTful API easier.
