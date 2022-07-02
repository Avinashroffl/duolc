clone repo
git clone https://github.com/karkranikhil/todo-app
npm install
node server/index.js (test db connection is established)
use postman api to get , put, delete , post, update from endpoints such as localhost:5000/todos or localhost:5000/todos/id

https://account.mongodb.com/account/register
POST localhost:5000/todos
Body->raw->JSON
{
"text":"hello avinash",
"status":true
}

PUT localhost:5000/todo/{ID}
BODY->RAW->JSON
SAME AS ABOVE

GET
localhost:5000/todos

DELETE
localhost:5000/todo/60eecba5dd8f6b50db4deb52

repo link: https://github.com/karkranikhil/todo-app
reference link: https://medium.com/@karkranikhil/build-and-deploy-crud-app-using-reactjs-mongodb-expressjs-and-digital-ocean-badb7a7fb59f

changes should be made in config.js after db creation in mongodb online
controller.js, model.js (db schema), routes.js ,index.js are the file needed