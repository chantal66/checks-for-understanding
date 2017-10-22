## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
> Node allows us to run JS without a browser. Node is a server side environment that runs JS on Chrome's V8 engine.
2. What is Express? What is Express similar to in the Ruby world?
> Express is pretty much like Sinatra in the ruby world. It's fast, unopinionated, it allows us tons of customizations.  
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
```
const app = require('express');
const Todo = require('./lib/controllers/todos-controller.js')

app.get('/api/v1/todos', (request, response) => {
    TodoController.all(response);
    });
    
module.exports = app;    
```
4. What do we use Knex for?
> Knex is like Active Record is Rails. well not completely I don't think knex is a full ORM, however it allows to connect
to our DB and make queries through our JS code. 

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
> We added controllers and models folders, where the controller makes calls to the model and access DB. We could've gone a step further and create a routes file where
we could've handle our routing. I think! 
 
6. How do you execute raw SQL in node?
> inside our model files 
```
database.raw(
`SELECT * FROM table_name;`
)
```

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
> I'm not sure about this, but my guess will be that the application is faster since the backend
doesn't have to serve HTML all the time. Additionally makes our application more modular and easier to maintain. 
#### Review  

8. Describe DNS.
> to my knowledge is Domain Name System and it allows us to look up websites by the domain name. 
9. What does writing clean code mean to you?
>* Easy to read - clear variables, function & methods. 
>* Easy to understand 
>* It's modular in the OO way which will make it easy to maintain.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
>* Hotel class - A hotel has many rooms, it also contains location info. 
>* Room class - A Room belongs to a a single hotel, and it can be reserved.
>* Customers class - can reserve rooms, and also contains customers info. 
