## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development?
Application Programming Interface. Facilitate various pieces of software to exchange data.

2. Provide an example of how you have used or encountered an API in a project or a practical scenario.
   

The significance of API is that it serves as a middleman, allowing developers to create software that makes use of the functionality and data offered by another application or service. 

Unbeknownst I have been encountering API's in my day-to-day life. Examples include Spotify, a Weather application, an online payment portal (Takealot), remote controls and IOT devices at home.    

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API?

An API is for software-to-software use with no human consumption. "mainstream media as a technology that allows applications (software programs) to talk to one another"  On the other hand the user interface is for human use and it's what we interact with.  (AP(I) Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses. Interface: A broader term encompassing all interaction points between two systems, devices, or users. It can be tangible (like a user interface) or conceptual. A type of interface between software entities that define interactions through rules and protocols. It's more about software-to-software interaction.

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

Types of APIs:

Web APIs:
Definition: Web APIs, commonly called web services, are interfaces that operate over the internet and facilitate interactions between systems or devices and the web servers hosting them.
Public vs. Private:
Public APIs: Also known as open APIs, they are available to developers and other users with minimal restrictions. They are meant to be publicly accessible and can be freely accessed by anyone.
Private APIs: These are restricted and often used internally within companies. Access might be limited to specific developers or teams.
Examples: Social media platforms like Twitter provide APIs for developers to fetch user data, post tweets, or gather analytics. Another prime example is Google Maps API, which allows for the embedding of Google Maps on web pages.
Usage: They are commonly used for mobile and web applications to provide dynamic content, integrate with third-party services, or enable functionalities like push notifications.
Operating System APIs:
Definition: These APIs provide a bridge for software applications to request and carry out basic operations within an operating system.
Functions: Tasks like reading/writing a file, managing memory, or interacting with peripheral devices.
Examples: The Windows API on Microsoft Windows OS or POSIX (Portable Operating System Interface) for UNIX-based systems.
Usage: Any software application running on a computer, from word processors to games, interacts with the operating system using these APIs.
Library and Framework APIs:
Definition: These are sets of routines, protocols, and tools bundled together in software libraries or frameworks, providing predefined functions to aid application development.
Purpose: They help accelerate development by eliminating the need to write code for basic, repetitive tasks.
Examples: jQuery, a fast and concise JavaScript Library that simplifies HTML document traversing, event handling, and animating.
Usage: Developers use them to tap into rich features and functionalities without "reinventing the wheel."
Database APIs:
Definition: These interfaces enable communication between an application and a database, allowing for data retrieval, storage, modification, and deletion.
Types: Most database management systems (DBMS) offer a specific API that defines how queries and commands should be formulated.
SQL-based: For relational databases like MySQL or PostgreSQL.
NoSQL-based: For databases like MongoDB or Cassandra.
Examples: JDBC (Java Database Connectivity) for Java-based applications to connect with databases.
Usage: E-commerce websites utilise database APIs to fetch product data, manage user accounts, and process orders.
Hardware APIs:
Definition: These interfaces allow software to interact, control, and retrieve data from hardware devices.
Scope: From controlling internal components like CPU or GPU to external peripherals like printers, cameras, or VR headsets.
Examples: OpenGL for rendering 2D and 3D graphics in computer hardware or TWAIN API for interacting with imaging devices like scanners.
Usage: Photo editing software might use a hardware API to get images directly from a scanner, or a video game might tap into specific graphics hardware features to optimise rendering

Endpoints:

 

An endpoint in API terminology refers to a specific path where API-related functions can be accessed. This path is a URL that represents the API's various functionalities.

Structure: Typically, an API endpoint will look something like http://api.example.com/users where the domain (api.example.com) points to the server where the API is hosted, and the path (/users) represents a specific resource or collection of resources.

Functionality Association: For instance, in a system dealing with user data, the /users endpoint might allow a developer to retrieve information about all users, whereas /users/123 would target the specific user with an ID of 123.

Resource Representation: Endpoints can represent singular resources or collections. They can also signify actions, like /reset-password.

 

Methods: 

 

HTTP methods, or verbs, define the types of actions or operations that can be executed against the API's endpoints. They are integral to the function and design of RESTful APIs.

GET: The GET method retrieves data. For instance, a GET request to /users might return a list of all users. This method is idempotent, meaning making the same GET request multiple times will produce the same result.

POST: POST is used to submit data. For example, when creating a new user, a POST request to /users with the appropriate data would add that user to the database. Unlike GET, POST is not idempotent; making the same POST request multiple times can have different outcomes.

PUT: The PUT method updates existing data. If a user with ID 123 needed to update their email address, a PUT request to /users/123 with the new email data would modify that specific record.

DELETE: As the name suggests, DELETE removes data. A DELETE request to /users/123 would remove the user with ID 123 from the system.

Others: There are other methods like PATCH (update part of a resource), HEAD (retrieve headers only), OPTIONS (describe communication options for the target resource), etc. Each has its specific use cases.

 

Data Formats:

 

The data exchanged between clients and servers via APIs is structured in specific formats to ensure both sides can read and understand the data.

JSON (JavaScript Object Notation): This lightweight data-interchange format is easy for humans to read and write and easy for machines to parse and generate. JSON has become the de facto standard for many web-based APIs due to its compatibility with JavaScript and other programming languages.

Example:

4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

I have used Curl in the Spotify Developer site as shown on the Tutorial. The Get tool for the Beyonce album and specific song "We Run the world"  Initiallly I  struggled because it's very specific with regards to characters. I too had an extra forward slash and did not copy the code correctly.  Additionally, I had some trouble loading Curl in Terminal.

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

I feel confident in identifying why an API would be necessary. How it is used specifically in the Spotify app example. It makes sense because it's something that I use daily. I can also wrap my head around the pay portal and weather app. I definetly need to brush up on the commands and requesting the commands (Get, Post, Put, Delete)  in devtools. I have not expolored any of the libraries and have not attempted to run or include an api in my own project. I will have to redo and practice with a tutorial. 
