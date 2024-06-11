## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. Understanding and Application: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.
  

The significance of API is that it serves as a middleman, allowing developers to create software that makes use of the functionality and data offered by another application or service. 

Unbeknownst I have been encountering API's in my day-to-day life. Examples include Spotify, a Weather application, an online payment portal (Takealot), remote controls, and IOT devices at home.    

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API?

An API is for software-to-software use with no human consumption. "mainstream media as a technology that allows applications (software programs) to talk to one another"  On the other hand the user interface is for human use and it's what we interact with.  (AP(I) Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses. Interface: A broader term encompassing all interaction points between two systems, devices, or users. It can be tangible (like a user interface) or conceptual. A type of interface between software entities that define interactions through rules and protocols. It's more about software-to-software interaction.

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

Components of API:

API Endpoints:
The endpoints represent each URL that is available in an API. API Endpoints refer to the different requests that can be made, and each endpoint has a  specific function.

Request Methods: 
APIs use HTTP request methods to indicate the desired action to perform for an endpoint. The main HTTP methods include:
GET - Retrieve a resource
POST - Create a new resource
PUT - Update an existing resource
DELETE - Delete a resource
By specifying the HTTP method, the API call indicates whether it is fetching data, modifying data, or performing another action. This guides both the API server and client on the intent of the request.

Header: 
Headers store information relevant to both the client and server. Mainly, headers provide authentication data — such as an API key, the name or IP address of the computer where the server is installed, and information about the response format.

Body: 
A body is used to convey additional information to the server. For instance, it may be a piece of data you want to add or replace.

Types of APIs include:

Web APIs - Operates over the internet and facilitates interactions between systems and devices. 
Public APIs: Available publicly accessible and can be freely accessed by anyone.
Private APIs: These are restricted and often used internally within companies. 
Operating System APIs: These APIs provide a bridge for software applications to request and carry out basic operations within an operating system.
Library and Framework APIs: These are sets of routines, protocols, and tools bundled together in software libraries or frameworks, providing predefined functions to aid application development.
Database APIs: Interfaces enable communication between an application and a database, allowing for data retrieval, storage, modification, and deletion.
Hardware APIs: These interfaces allow software to interact, control, and retrieve data from hardware devices.

I'm most intrigued by the Hardware API. These smart devices can provide automation in your home. An example is being able to switch on the light, alarm, and pool pump from your app on your cellphone. 


4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

I have used Curl on the Spotify Developer site as shown in the Tutorial. The Get tool for the Beyonce album and specific song "We Run the World"  Initially I  struggled because it's very specific with regards to characters. I too had an extra forward slash and did not copy the code correctly.  Additionally, I had some trouble loading Curl in Terminal.

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

I feel confident in identifying why an API would be necessary. How it is used specifically in the Spotify app example. It makes sense because it's something that I use daily. I can also wrap my head around the pay portal and weather app. I definetly need to brush up on the commands and requesting the commands (Get, Post, Put, Delete)  in devtools. I have not explored any of the libraries and have not attempted to run or include an API in my project. I will have to redo and practice with a tutorial. 
