# cs465-fullstack
CS-465 Full Stack Development with MEAN

- End Module Questions -
  
- Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
For this project, I originally started with a single-page application (SPA) but then switched to an Angular platform. Express and Angular are both frameworks for web application development. Express’s project structure primarily deals with a back end and is simpler due to not requiring a front end. Angular’s project structure is a little more in-depth, as Angular includes a front end and is structured into modules, services, and components. Two key advantages of an SPA or Single Page Application are that it loads only once, and updates the content as needed. This reduces the loading time for the page. Additionally, SPAs can be accessed offline as there is no need to send the HTML over a request. On the contrary, two disadvantages of SPAs is that while content can update in “real-time,” the initial loading time for an SPA could be quite long. The JavaScript needed to render the page needs to be downloaded first before the site can even run. Additionally, SPAs require JavaScript, so any browser that is not JavaScript compatible or has issues running JavaScript will have issues running the SPA, making the compatible browsers limited.

- Why did the backend use a NoSQL MongoDB database?
The NoSQL MongoDB database allows developers to build a powerful tool for scalable, flexible, and high-performance applications in a dynamic environment.

- How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON (JavaScript Object Notation) is a data format that is independent of programming languages. JavaScript is a programming language commonly used for web development. JSON is used between the front end and the back end of a web application. JSON sends data from the back end to the front end, and JavaScript interprets this data for use.

- Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.
I had to refactor the code from a SPA into an Angular application. This required creating reusable interfaces for trip cards, trip components, and add/edit trip buttons.

- Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full-stack application.
Methods refer to the HTTP commands of GET, POST, PUT, DELETE, etc. These methods are used to perform operations on resources, such as retrieve, create, update, and delete data. Endpoints are specific URLs on the server. Each endpoint typically corresponds to a method. Security is critical in a full-stack development project to protect data. This involves implementing encryption, input validation, and user authentication.

- How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
At the beginning of this course, I hadn't even heard of an Angular application. I was somewhat familiar with GET, POST, PUT, and DELETE methods but didn't fully know how they worked in an application setting. While I don't think I can make a standalone application from scratch, I'm confident in my newfound ability to understand the ins and outs of how they work if I were to work with them again in the future.
