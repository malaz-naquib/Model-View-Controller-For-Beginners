# Model View Controllers For Beginners

![Base Map](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/e05e1679-8939-401c-a1a4-1c9c4e553b9f)

#### By Malaz Naquib

## Before we Begin:

The Model View Controller can be a daunting subject to cover in your Software Engineering career. Fear no more! This lecture explains the MVC (Model View Controller) in a beginner-friendly manner. Additionally, we'll be using some analogies to ease our minds into thinking of the MVC in a clear, fun way!

## What is the MVC?

Created in 1979, The Model View Controller (MVC) is an architectural paradigm that allows us to split the complexity of our applications into 3 structural elements, Model, View, and Controller. Keep in mind, the MVC is **NOT** a framework. 

Like a three-legged stool, each of the 3 structural elements, Model, View, and Controller, are vital in that they are responsible for different parts of how our application processes data. Structurally, the MVC allows us to build our applications while thinking about and controlling how information is being processed.

## Why is the MVC Pattern Popular?

The MVC pattern is used by a host of popular frameworks! Here's a quick list of popular frameworks that utilize the MVC pattern:

- Ruby on Rails
- IOS
- Objective C
- CakePHP
- Django
- Laravel
- Zend Framework
- CodeIgniter

**To reiterate, frameworks implement an MVC structure, but MVC is NOT a framework.**

## Why Should We Use the MVC?

The MVC is a way for us to organize the requests/returns between our users, servers, and databases. To explain further, the MVC pattern allows us to separate out our application's files so that everything has a specific place and is easy to locate. For instance, we're able to change an element of our application in one, specific file instead of having to make multiple, tedious changes across our application's files.

By separating out our application's files, system processes can be completed in an organized and streamlined manner; preventing us from repeating ourselves and helping to create a solid structure around our web applications. Additional benefits include code reusability and test-driven development.

In a large project with multiple developers, the MVC allows code to be worked on by multiple developers without losing sleep over changes being made to the codebase.

**While there are other approaches similar to MVC such as MVVM, HMVC, and MVP, MVC is the most common pattern we'll come across.**

Moving forward in our understanding of the MVC, let's begin diving into what each of the structural elements actually do!

## Model (Our Data)

Let's go ahead and start with dissecting the "M" in MVC, Model. 

Anything having to do with interacting with data such as adding and retrieving items from the database falls under the Model's functions. In our diagram, the Model is identified as the database. 

The Model performs the following functions:
- Retrieves and manipulates data.
- Identifies the request sent from the controller and interacts directly with the database to search, retrieve, and return requested data.
- Only communicates with the database and controller, never the view.
- Only element to interact with the database.


## View (Our Visuals)

Next up, we have our "V". In the MVC, V stands for View. 

Anything having to do with the output of front-end visible code that is going to be viewed in the client's web browser falls under the View's functions. In our diagram, the View is identified as the client. 

The View performs the following functions:
- Takes in the request and relevant data from the controller and renders the page; returning the page with the requested information.
- Typically, View is in the form of HTML/CSS.
- Only speaks with the controller.

## Controller (Our Director)

Perhaps the centerpiece of our MVC structure is the "C" in MVC, our Controller.

Our Controller is in charge of processing GET/POST/PUT/DELETE requests and handling all server-side logic. It is the middle man of our MVC structure, taking in requests from our users and deciding where that information should go. In our diagram, the Controller is identified by, well, the Controller.

The Controller performs the following functions:
- Processes GET/POST/PUT/DELETE requests from the user.
- Acts as the middle man between the View, Model, and User; deciding where requests must go.
- While it does not interact with the database, it will request data from the Model.
- Invokes the View to render the visual presentation of the page once all data is in hand.

## The Router (Traffic Control)

Aside from Model, View, and Controller, it's important that we cover the Router as well. Essentially, the Router is what allows us to handle the routing and directing of requests to the appropriate Controller. The reason is, our application may have multiple Controllers that handle different pages.

In addition to directing requests to the appropriate Controller, the Router also ensures that each request is routed to the correct Controller based on predefined routes and URLs.

## How Does this Process Work in Real-time?

![Step 1](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/a2213862-7965-408f-9707-fe441ae4e823)

![Step 2](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/b80e9ff2-5462-4c44-b705-043710d3fd20)

![Step 3](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/f373bd85-e06a-4b53-b791-4871772246ad)

![Step 4](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/73543148-730b-427a-967a-e402db89ce2b)

![Step 5](https://github.com/malaz-naquib/Model-View-Controller-For-Beginners/assets/113329798/67f3df7c-ed21-46bf-bbb9-c3580adfc47e)

________________________________________________________________________________________________________________________________________________

Thank you for taking the time to go through this lecture and learn about the wonderful world of MVC! Hopefully, this has provided insight into how we can use the MVC to abstract the complexity of our applications into more organized structures of code. Happy coding!
