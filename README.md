# CS465 Full Stack Web Application

## Architecture

This project introduced me to several different approaches to frontend development. Early in the project I used Express with HTML templates to generate pages on the server. Later I developed a single page application (SPA) using Angular, which moved much of the user interface logic to the client side. The SPA created a smoother experience because only the necessary data changed instead of reloading an entire page. JavaScript was used throughout both approaches to provide functionality and connect the application to the backend services.

The backend used MongoDB because the application worked with flexible travel data that could easily be stored as JSON like documents. Since MongoDB does not require a fixed table structure, it was easier to add or modify information as the project continued to grow.

## Functionality

JSON and JavaScript are closely related, but they serve different purposes. JavaScript is a programming language used to build application logic, while JSON is a lightweight format for storing and exchanging data. Throughout this project, JSON allowed information to move between the Angular frontend, the Express server, and the MongoDB database in a consistent format.

As the project progressed, I refactored code by moving repeated functionality into reusable services and components. This reduced duplicate code, made future updates easier, and helped keep the application organized. Reusable UI components also improved consistency across the application because changes only needed to be made in one place.

## Testing

Throughout development I tested API endpoints by sending GET, POST, PUT, and DELETE requests to verify that each route returned the expected results. As authentication was added, testing became more involved because protected endpoints required valid login credentials before data could be accessed or modified. This demonstrated how methods, endpoints, and security all work together to protect application resources while still allowing authorized users to perform their tasks.

## Reflection

This course gave me a much better understanding of how a full stack application is built from beginning to end. Before this course I viewed the frontend, backend, database, and security as separate topics. Completing this project showed me how each layer depends on the others to create a working application. I also gained experience with Angular, Express, Node.js, MongoDB, REST APIs, authentication, and debugging larger applications. These are practical skills that will help me as I continue building software projects and prepare for a career in software engineering.
