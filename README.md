# OpencartAPI
This module extends OpenCart’s API functionality by managing API users, providing authentication, and enabling secure interactions with the OpenCart store via REST API.

Requirements
OpenCart Version:3.0 
PHP: >= 7.4
MySQL Database
Apache/Xampp Server
Postman
Newman
Jenkins

{{baseUrl}}http://{{ip}}/opencart/upload/index.php?route=

API Endpoints
Method-->	      Endpoint-->	           Description
POST --> {{baseUrl}}/api/login       -->	Create Token
POST --> {{baseUrl}}api/cart/add     -->Add product to cart
GET  --> {{baseUrl}}api/cart/products-->Cart content
POST --> {{baseUrl}}api/cart/edit    -->Update an order
POST --> {{baseUrl}}api/cart/remove  -->Delete an API user
