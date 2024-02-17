# RESTful-API-using-the-Slim-4-framework

composer require --with-all-dependencies \
    slim/slim:"4.*" \
    slim/psr7 \
    selective/basepath


POSTMAN

Create 
in Postman, create a new POST request, then:

Set the URL to http://localhost:8888/customers-data/add.
And under the Body tab:

Set the encoding-type to "raw"
Set the Content-Type to JSON
Paste the JSON below into the request's body field.

{
   "name" : Name",
   "email" : "myemail@mail.com",
   "phone" : "123449988383"
}


Update
create a PUT request with the following details:
URL

http://localhost:8888/customers-data/update/3

Body

{
     "name" : "First Name Last name",

     "email" : "myemail@mail.com",

     "phone" : "123449988383"

}

Encoding-Type

raw

Content-Type

JSON

Delete
make a DELETE request in Postman with the URL http://localhost:8888/customers-data/delete/3. No other settings need to be set.
