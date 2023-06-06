# Movie-Recommendation-Application

Client Side : https://mern-movieflix-app.netlify.app

https://user-images.githubusercontent.com/68987772/243558064-f060a977-705a-40d3-a9bf-20b7ec1763b1.mp4


API 👍

User Registration :
The user registration API creates a user account in your application. A registration request must provide a user object as a collection of key/value properties.

Method : POST

Endpoint URL : https://movies-api-bd5r.onrender.com/api/auth/register/

Request Body
{
"username" : value,
"email" : value,
"password" : value
}

Response Body
{
"username": value,
"email": value,
"password": value, <<< THIS VALUE IS ENCRYPTED
"isAdmin": Boolean value,
"_id": value,
"createdAt": created timestamp value,
"updatedAt": updated timestamp value
}
