# API_express-tsc
POST /users/register headers Content-Type application/json
{ "email" , "password", "name"}

POST /users/login headers Content-Type application/json
{ "email" , "password"}

GET /users/info headers Authorization Bearer /*JWT token*/


.env
SALT = /*Password hashing salt*/
SECRET = /*Secret or public key for JWT*/
PORT = /*Port*/