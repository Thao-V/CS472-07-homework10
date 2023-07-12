# CS472-07-homework10
# Express
## Continue the previous homework
* Create an server from scratch using `npm`
* Setup the server to run with `npm start` and `nodemon`
* Use `express` and `express.Router` to implement the routes
## Implement APIs to support followings requests. Assume that the server is running on the port 3000. And the POST method should contain the data in the body as JSON object.
* `GET http://localhost:3000/tasks`: Return all tasks
* `POST http://localhost:3000/tasks/add-task`: Add the task into the backend and return the added task with status of 200 if success. Otherwise, return an error message `Cannot add this task`;
* `POST http://localhost:3000/tasks/delete-task`: Delete the task in the backend and return the deleted task with status of 200 if success. Otherwise, return an error message `Cannot delete this task`;
* `POST http://localhost:3000/tasks/update-task`: Update the task in the backend and return the updated task with status of 200 if success. Otherwise, return an error message `Cannot update this task`;


