# Languages and Such
What distinguishes JavaScript from other languages that fill a similar role (like Ruby, Python, Java, etc)?
> Javascript is more versatile than many languages.  It started out as a browser based language used for adding interactivity to websites.  Nowadays though, you can use Node.js to allow JS programs to run outside of a browser.  I don't know much about Ruby, but I have heard that it too has a general purpose nature.  I have programmed in Python enough to know that it tends to have more back-end popularity.  Java on the other hand, like C++ needs to be compiled and executed while JS does not.  It is a so called 'scripting language.'  


Define HTML. Where/how is it used?
> HTML stands for *Hyper Text Markup Language*.  It was first developped in 1990 and is the backbone of the internet. Internet pages are written in HTML. Pages usually have 'hyperlinks' to other pages, hence the name.


Define CSS/SCSS. Where/how is it used?
> CSS stands for *Cascading Style Sheets* and is a declartive language for styling webpages.  SCSS stands for *Sassy CSS*.  Sassy CSS is a form of CSS that allows for more functionality via variables, loops, and mix-ins (i.e. functions). If HTML provides the actual content of a webpage while CSS/SCSS provides the formatting. Cascading refers to the fact that style rules, or even whole stylesheets can be overlayed on top of one another, and that the effects cascade down.  There are several rules about which conflicting rule wins but there are general heuristics for what trumps what:

> Later stylesheet > Earlier stylesheet
> Important tag > Inline > Cascade order 
> Author > User > Browser 
> Specific > generic
> Inline style > Ids > Class > Tag > Order

Define SQL. Where/how is it used?
> SQL stands for *Structured Query Language*. Like CSS, it is declarative. That is, it declares what it wants. I've heard people say both 'ESS-QUE-EL' and 'Sequel' outloud and I'm not sure which is correct.  It is the standard language for relational database management systems -- in other words, it is the language that allows you to communicate with a database.

Define Regex. Where/how is it used?
> Regex stands for Regular Expression, and it the most mystifying of these language for me.  I got turned on to a great [Regex Crossword](https://regexcrossword.com/) to help me learn Regex, but I have yet to use it extensively.  I even made flashcards when I first got interested in it.  A regular expression is a special text string for describing a search pattern within a string.

# Common Libraries
Where does express belong in the 'stack' of web technologies? What problem does it solve and how?

Where does mocha belong in the 'stack' of web technologies? What problem does it solve and how?

Where does fs belong in the 'stack' of web technologies? What problem does it solve and how?

Where does passport belong in the 'stack' of web technologies? What problem does it solve and how?

Where does socket.io belong in the 'stack' of web technologies? What problem does it solve and how?

Where does jQuery belong in the 'stack' of web technologies? What problem does it solve and how?

Where does bootstrap belong in the 'stack' of web technologies? What problem does it solve and how?

Where does sequelize belong in the 'stack' of web technologies? What problem does it solve and how?

Where does nunjucks belong in the 'stack' of web technologies? What problem does it solve and how?

Where does the Google Maps APi belong in the 'stack' of web technologies? What problem does it solve and how?

Where does async.js belong in the 'stack' of web technologies? What problem does it solve and how?

Where does bluebird belong in the 'stack' of web technologies? What problem does it solve and how?

Where does react belong in the 'stack' of web technologies? What problem does it solve and how?

Where does react-router belong in the 'stack' of web technologies? What problem does it solve and how?

Where does redux belong in the 'stack' of web technologies? What problem does it solve and how?

Where does react-redux belong in the 'stack' of web technologies? What problem does it solve and how?

Where does crypto belong in the 'stack' of web technologies? What problem does it solve and how?

Where does https belong in the 'stack' of web technologies? What problem does it solve and how?

# Code Design
Define CRUD. How does it help guide or improve your code or coding process?
> CRUD stands for **create, read, update, and delete**.  These are the four basic functions of persistent storage.  The acornym CRUD is sometimes used to describe UI conventions that facilitate viewiwng and changing information.  There are many variations of CRUD (BREAD, MADS, DAVE, CRAP) that describe the same thing, i.e. the major functions in relational database applications.  There is a nice table comparing CRUD to SQL statements and HTTP verbs on the [Wikipedia Article](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete).

Define MVC. How does it help guide or improve your code or coding process?
> MVC stands for **model-view-controller**.  In OOP, MVC is a design pattern which breaks down apps/programs into those three components.  The model is the underlying logical structure of the data.  The view is the classes/elements associated with the UI, and the controller represents the classes that connect the model to the view.

Define DRY. How does it help guide or improve your code or coding process?
> DRY stands for **"Don't Repeat Yourself"** One of the perks of programming, is that you can automate and streamline things. If you find yourself copying and pasting the same code over and over, you're doing it wrong.  Find a way to create functionality without repition.

Define SOLID (we haven't told you about this). How does it help guide or improve your code or coding process?
> From [Wikipedia](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)
> **Single responsibility principle** - a class should have only a single responsibility (i.e. only one potential change in the software's specification should be able to affect the specification of the class)
> **Open/closed principle** - “software entities … should be open for extension, but closed for modification.”
> **Liskov substitution principle** - “objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.” 
> **Interface segregation principle** - “many client-specific interfaces are better than one general-purpose interface."
> **Dependency inversion principle** - one should “depend upon abstractions, [not] concretions.”

Define dependency injection. How does it help guide or improve your code or coding process?
> I hadn't heard of this before, so I found [this article](https://www.devbridge.com/articles/dependency-injection-in-javascript/) to clarify.  I still need to summarize it though.

Define REST. How does it help guide or improve your code or coding process?
> REST stands for **Representational State Transfer**.  RESTful design ensures that we do not transfer an actual object, but a representation of it.  RESTful design uses a single consistent interface to handle CRUD operations. 

# Misc Terms
Define library. What differentiates it from a framework, an API, or a protocol?

Define framework. What differentiates it from a libary, an API, or a protocol?

Define API. What differentiates it from a library, a framework, or a protocol?

Define protocol. What differentiates it from a library, a framework, or an API?

Define operating system. What differentiates it from a runtime environment or an intepreter/engine/VM?

Define runtime environement. What differentiates it from an operating system or an interpreter/engine/VM?

Define interpreter/engine/VM. What differentiates it from an operating system or a runtime envrionment?

# Programming Fundamentals
Define modularity. Provide what you believe to be a quintessential example.

Define object-oriented programming. Provide what you believe to be a quintessential example.

Define functional programming. Provide what you believe to be a quintessential example.

Define recursion. Provide what you believe to be a quintessential example.

Define closure. Provide what you believe to be a quintessential example.

Define inheritance. Provide what you believe to be a quintessential example.

Define first-class functions. Provide what you believe to be a quintessential example.

Define higher-order functions. Provide what you believe to be a quintessential example.

# CS Fundamentals
Name at least two sorting algorithms you know and detail the differences between/among them.

What are the two types of computational complexity? How does big O notation represent differences between algorithms?

Define a linked list and give an example use case. Describe the runtime complexity of 'set' and 'get' operations on it.

Define a hash table and give an example use case. Describe the runtime complexity of 'set' and 'get' operations on it.

Define a binary search tree and give an example use case. Describe the runtime complexity of 'set' and 'get' operations on it.

What cellular automaton is a famous 'game'? How have cellular automata factored into the history and development of computer science?

# JavaScript Fundamentals
What are prototypes? How do you assign behavior to them? How do they differ from other inheritance systems in computer science?

What are the five primitive JavaScript types? What is the sixth 'universal' type?

What is the difference between == and === forms of equality?

What is this? Provide examples of how it differs in different contexts.

Define chaining. Provide what you believe to be a quintessential example.

# Dev Tools
What role does the console serve? Provide examples.

What role does the inspector serve? Provide examples.

What role does the style panel serve? Provide examples.

What role does the network tab serve? Provide examples.

What role does the debugger statement serve? Provide examples.

# Basic Node Usage
What are node modules? How do you export and import data in a node file? What is the difference between module.exports and exports?

What problem does npm solve and how?

What purpose does your package.json serve?

Server-side v. Client-side
Describe how dependencies are different in backend vs frontent JS.

Describe how persistence are different in backend vs frontent JS.

Describe how environment APIs are different in backend vs frontent JS.

What other things are different in backend vs frontent JS?

# Asynchronous Programming
Compare blocking and non-blocking. Give a real-world metaphorical example. Which one describes JavaScript?

Describe event handlers by providing an example use case (pseudo-code encouraged).

Describe asynchronous callbacks by providing an example use case (pseudo-code encouraged).

Describe promises by providing an example use case (pseudo-code encouraged).

Describe middleware by providing an example use case (pseudo-code encouraged).

# Promises
What are some advantages of promises over callbacks?

What is the purpose of the then method?

What happens when you:

Return a value from a then handler?
Return a promise from a then handler?
Throw an error from a then handler?
How do success and error bubbling work?

# V8 Asynchronous Interals
Explain the role of the event loop in the V8 ecosystem.

Explain the role of the function call stack in the V8 ecosystem.

Explain the role of the callback queue in the V8 ecosystem.

Explain the role of the environment APIs in the V8 ecosystem.

# The Internet
Describe, broadly, how DNSs resolve IP addresses.

Define an internet node (not node.js).

Define client.

Define server.

# Network
Explain TCP/IP and its realtionship to other subjects in this topic.

Explain HTTP and its realtionship to other subjects in this topic.

Explain Web Socket and its realtionship to other subjects in this topic.

Describe WebRTC, comparing it to other subjects in this topic.

Describe AJAX, comparing it to browser-level HTTP.

# HTTP 
Define request.
Define response.
Define request-response cycle.
Describe HTTP verbs/methods and list the common ones.
Describe HTTP headers and list the common ones.
Describe HTTP status response codes and list the common ones.
What are cookies and what purpose do they serve?

# Express Usage
How do routes and filepaths differ?

What's the difference between app.use and app.all?

Compare and contrast the request query, params, and body—provide examples.

What are express routers? How and why would you implement one?

What is the standard approach to error handling in an express app? Provide code.

# Common middleware
Describe the role of morgan in the middleware stack.

Describe the role of body-parser in the middleware stack.

Describe the role of express-session in the middleware stack.

Describe the role of express.static in the middleware stack.

Describe the role of node-sass-middleware in the middleware stack.

# Database Persistence
Define database.

What does ACID stand for? What does each mean?

Define relational v non-relational.

What is the CAP thereom? What are its implications?

Define and describe SQL.

Define and describe PostgreSQL.

What is a schema?

Define ORM.

What is database indexing and why is it useful?

# SQL 
Describe SQL tables.

Describe SQL rows.

Describe SQL columns.

Describe SQL primary keys.

What types of joins exist in SQL? How do they differ?

# Sequelize
Define models and provide a code example. How do sequelize models differ from SQL schemas?

Describe sequelize validations and provide a code example.

Describe how sequelize enables relationships between tables and models. Provide a code example.

Define eager loading in sequelize and provide a code example.

Define sequelize virtuals and provide a code example.

Define sequelize hooks and provide a code example.

Compare sequelize class methods and instance methods.

# Automated Testing
Describe test driven development and detail its benefits.

Compare and contrast unit, service, and end-to-end testing.

Define assertions.

Define spies.

Should tests focus on behavior or implementation (or both)?

What would you say makes for 'good' tests? Why?

# Browser
What is the meaning of style in the context of frontend development? What language does it correspond to?

What is the meaning of layout in the context of frontend development? What language does it correspond to?

What is the meaning of behavior in the context of frontend development? What language does it correspond to?

What is the DOM? Where does it exist? How is it different from a web page's HTML? How is it different from the global window object?

What is event bubbling? What is event delegation?

What problem does bower solve and how?

What are iframes? Why are they useful?

# HTML
Define tag in terms of HTML. Compare it with the others in this topic.

Define attribute in terms of HTML. Compare it with the others in this topic.

Define class in terms of HTML. Compare it with the others in this topic.

Define id in terms of HTML. Compare it with the others in this topic.

How do forms work and how can they be configured to send HTTP requests?

# (S)CSS
What are the four 'areas' in the box model?

How do inline and block elements differ?

When an element is styled by more than one rule, how does the browser determine specificity give precedence?

What is grid layout and how do you use it?

What is 'float'? Give an example of where it would be useful.

What problem do media queries solve and how?

What tools/features does SCSS add to CSS?

# jQuery
Provide an example of DOM manipulation with jQuery code.

Provide an example of DOM traversal with jQuery code.

Provide an example of event handling with jQuery code.

Provide an example of an AJAX request with jQuery code.

What are the four roles $() can perform given different inputs?

# React/Redux
What is a React component?

What is JSX?

What’s the difference between state and props? How do we change state? How do we pass props?

Describe a component's lifecycle methods. When should you fetch data?

What is a stateless component?

What is a Redux store? How do you create one?

Describe an action creator versus an asynchronous action creator.

What is a reducer? How do you use combineReducers?

What does it mean to "dispatch an action”?

What does the connect method do, and how do we use it?

# Auth
What's the difference between authentication and authorization?

How is HTTPS different from HTTP? What are SSL certificates?

What's the difference between hashing and encryption? Provide contrasting use cases.

How do cookies enable sever-side sessions, and how do sessions enable persistent login?

How does access control differ between the frontend and the backend?

Describe, broadly, the OAuth protocol. Separately, what problems does it solve?
