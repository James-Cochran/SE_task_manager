# README
## Checks for Understanding

1. Define CRUD.
  Create, Read, Update, Delete.  - These are the 4 elements that every site will have.  Create, the ability to add new data.  Read, the ability to show data. Update, the ability to modify existing data.  Delete, the ability to remove data.

2. Define MVC.
  Model, View, Controller.  The Model is the logic.  It takes in the user request via the controller, gathers all the information, organizes it, and gives it back to the controller.  The view is what the user sees and interacts with.  The controller is the middleman in this.  It interprets user input, and decides what is wanted, and sends that request to the model.  When it gets the request back from the model, it checks that it is what it wanted, then passes it to the view to present to the user.

3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
  If you already have a model, you would then also need a route and a controller.  You need a route to send the GET request to the correct controller action.  The contoller would need to have the appropriate action to be able to facilitate the request.  to just go to /tasks, the route would need a to: #index, and the controller would need an index action.

4. What are params? Where do they come from?
  Params or parameters, are added specifics that come from the user to give added instructions to clarify exactly what is wanted.

5. What is the purpose of a serializer?
  A serializer is kind of like a param for the outgoing information.  It allows you to specify and include return only the data you want through JSON.


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
