Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

I used a few different technologies for the frontend development of the Traveler website. To start, Angular was used as the frontend technology for the admin panel of the website. With Angular, we could easily bind data to the UI components, ensuring real-time updates as changes were made. 
In our comprehensive full-stack project, we employed a combination of frontend technologies to create a dynamic and user-friendly web application. We chose Angular for the administration Single Page Application (SPA), and Handlebars for the public-facing website. These choices were made based on the distinct characteristics and requirements of each part of our application. For the public-facing website, I used Handlebars, a lightweight templating engine. Handlebars allowed us to generate dynamic HTML content with a small amount of JavaScript code.

Why did the backend use a NoSQL MongoDB database?

A noSQL database was the best choice for the traveler website. MongoDB objects closely match the structure of JavaScript objects. This made it easier to integrate with our frontend technologies, as data could be seamlessly serialized and deserialized between the frontend and backend.

Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a data format used for its easy readability and parsability. It has a key-value structure that takes a string as the value’s key and almost any data type as the value. JavaScript, on the other hand, is a programming language that is used to create dynamic content on webpages. It is mostly used on the frontend, but has use cases in backend development as well.
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

During the development process, we abstracted some of the frontend code to pull data from a JSON file (later the database) and display the information using the Handlebars. This shortened the amount of HTML present in some of the files and made it easier to find certain “components” of the page for easier bug-finding and editing.

Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

There are several HTTP methods that define what to do with the requested resources to the API (sent by url). The three that I used in the Traveler web application are GET, POST, and PUT. GET was used to retrieve information, POST was used to create new information, and PUT was used to update existing information. Endpoints are points in the API url that point to specific resources or functions. These points are usually associated with an HTTP method. APIs can handle sensitive information, so it is important to secure the data. This can be done in several ways. In the case of the Traveler website, we used authentication and tokens as well as a predefined encryption method.

Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has helped me develop my skills with JavaScript and teach more about component based frontend frameworks. I believe that this will make me more marketable in the field as full-stack engineers are in high demand (usually) because of the high number of web applications that need to be maintained or are in active development.

