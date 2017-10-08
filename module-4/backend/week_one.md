## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
> Array prototype methods have been very useful so far.

2. What are some tools to help debug JavaScript code?
> Debugger in code and console, pryjs and console.log 
3. What are some tools you need in order to unit test your JavaScript?
> We need mocha and chai testing frameworks in order to test individual parts of our code. 
4. What is the syntax for invoking a function?
> myFunction();
5. What's `this` in JavaScript?
> `this` refers to the DOM object we are in or trying to manipulate. it's like self in ruby.  
6. What is Webpack and why is it useful?
> webpack is a tool that takes all your files CSS, images and JS compiles them into a single file made out 
of vanilla javascript, so it's very easy for the browser to read. with Webpack also comes webpack dev server, 
and its best feature is that it listens for any changes in our code so we don't need to restart the server every
time.  
7. When/why do you want to use event delegation?
> event delegation is when we let other elements than the target to handle the actions we want to perform.
like letting the ul handle the events for all of the li or when we are injecting some html in the DOM through js and 
we want to do something by the click of the button since this code doesn't exist until an action happens that button 
action needs to be bind to something that is already exists on the page.  

8. What's `npm` and what do we use it for?
> npm is package manager tool for node js or modules.  

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
> It refers to Model-View-Controller pattern. 
>* Model - contains data for the application usually linked to DB. it also contains the state of the application, 
like what orders or how many orders a user has. 
>* View - generates the user interface and presents data. 
>* The Controller - receives information from the outside world through the views, interacts with the model, 
and displays the right view to the user.
10. What are a few ways to optimize a Rails application?
> we can optimize through:
>* caching
>* faster queries
>* minifying our css, scss and js files.
   
11. What's a background worker? When would we want to use a background worker?
> Background workers are tasks that we can program to run at certain time after an action has been performed, 
it can also be setup to perform immediately after an action. 
We can set them up anytime we have a repetitive or common tasks in our app.