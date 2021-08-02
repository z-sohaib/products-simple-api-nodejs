# ProductsSimpleAPI

## Routes 
Different routes you can use in this API

###### `GET` /products/all 
Get all products in database 

###### `POST` /products/create
Create a new product in database with this model : 
```
productschema = {
name : String,
description : String,
image: String,
price: Number,
}
```
###### `PUT` /products/update/id
Edit an existing product identified in database with its id
according to this model : 
```
productschema = {
name : String,
description : String,
image: String,
price: Number,
}
```
###### `DELETE` /products/delete/id
Delete an existing product identified in database with its id
