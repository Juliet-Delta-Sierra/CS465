# Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database?

Travlr Getaways is a web application that enables secure booking of trips by travelers. The user interface is designed to use a backend database and logic to ensure the requests are processed as expected. 

The MEAN stack framework was sued for the development of this web application. The MEAN stack is named after MONGODB (NoSQL document database), Express (Node.js web framework), Angular (a client-side JavaScript framework), and Node (.js web server). Each one is the key component in the MEAN stack.

The customer-facing side was created with HTML documents using JavaScript to display the data (served through Express). The MVC architecture was used to load multiple pages at a time as the user was requesting the data. A single-page application (SPA) is a website that doesn't fully refresh the page based on user interactions like an HTML page would. This is particularly useful in giving the website a local/native application feel when interacting with the application itself.

The backend used a NoSQL MongoDB database because of the interent ease to modify schema based functionality and scale changes because of its non-relational nature of the database.


# Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

JSON is a industry standard method to arrange data from objects that can be interpreted by Javascript and then be developed into a Javascript object. This allows Javascript to gather the data and interpret it into an object using the buildin functionality of Javascript. The benefits of this allow the data from the front end and back end to communicated between the two with Javascript. The data can be stored and used in various ways thoughout the application.

Looking throughout the project history, an example where code was refactored is displayed in the trip card and trip list componenets. When each of the componeents reneder the same infomraiton does not lead to code that is efficient or has long-term robustness. When the trips are rendered by same componenet/yet still being apart of the same framework, the efficiceny and robustness of the code/functionality improves. It reduces the size of the application and the possibilities for error and also imporves troubleshoots due to reduced redundencies. 

# Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

# Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

# TravlrAdmin

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.9.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
