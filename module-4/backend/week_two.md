## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?
>* function keyword in ES5 vs fat arrows in ES6 
2. What's the difference between asynchronous and synchronous JavaScript?
>* asynchronous means that multiple js processes can be executed at different times while synchronous is that they are performed at the same time.  
3. What are the four pillars of Object Oriented programming?
>* APEI => Abstraction, Polymorphism, Encapsulation, Inheritance 
4. What are some tools available in JavaScript to help you write object oriented code?
>* Use class syntax with constructor method like initialize in Ruby and new Object declarations to help write OOP style.
5. What are some key concepts to be aware of when refactoring your JavaScript?
>* the meaning of this is different between ES5 and Es6 so this is something to be aware of. 
6. What's a callback function and what are some reasons when we use/need callback functions?
>* a callback function is when we invoke the function with parenthesis myfuntion() to be executed in the call stack. 
We use it specially with event handlers.
7. What's the scope of variables in Javascript?
>* Variables declared inside a block they are local variables, Variables declare outside of a block are global variables. 
8. What's the difference between `==` and `===` in JavaScript?
>* == it checks for equality 2 == '2' will be true but with the triple equality === will be false. 
9. Why do front end frameworks exist?
>* in order to organize and write faster apps than with just Vanilla js. In ruby we use Rails. 


#### Review  

10. Why do people say "HTTP is stateless"?
>* Servers don't retain the state of your interaction with the page. 
We usually have to store some session or cookie data to tell the server what state we are in.
11. Describe a RESTful API.
>* RESTful APIs follow the 7 HTTP verbs as well as using nouns in the URL to declare what you are accessing.
12. What are some main characteristics of a team following an agile workflow?
>* Having a daily standup. Talk about what you did yesterday, what you are going to do today, 
and if anything is blocking your progress.
13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
>* Advantage - we don't have to store a person's credentials and we don't have to write our own from scratch.
   Disadvantage - we get information from the user that is not relevant to us. 
