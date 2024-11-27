# Instagram Clone Project

![Instagram Feed](./images/GUI_1.png)

## Disclaimer
This repo is just a display of a course project for EECS 485 Web Systems @ University of Michigan. I'm excluding the code to comply with academic integrity policies.

## Technologies Used
- **Frontend**: React, JavaScript, HTML, CSS  
- **Backend**: Python Flask, REST API  
- **Data Processing**: SQLite 
- **Architecture**: Client-side dynamic pages, asynchronous programming (AJAX)
- **Testing**: Cypress
- **Deployment**: AWS (EC2)

![Instagram Login](./images/GUI_2.png)
![Instagram Profile](./images/GUI_3.png)

## Project Overview
Usable instagram clone implementation featuring:
- **Client-Side Dynamic Pages**: Dynamic DOM updates via JavaScript.  
- **REST API Integration**: Backed by a Flask REST API.  
- **Infinite Scroll**: Seamlessly load additional posts while scrolling.
- **User Interaction**: Like, comment, and delete actions without reloading the page.
- **AJAX Calls**: Asynchronous data retrieval for real-time updates.
- **User Authentication**: Secure login using session cookies or HTTP Basic Auth.

## System Architecture
### Client-Side Dynamic Pages
- The client application runs JavaScript in the browser to render and update pages dynamically.  
- Data is fetched from the Flask REST API via **AJAX calls** and used to modify the DOM.  
- This enables features like infinite scrolling, real-time likes, and more.

### REST API
The backend provides RESTful endpoints for key operations:
- **Posts**: Retrieve, paginate, and filter posts.
- **Likes**: Add or delete likes.
- **Comments**: Add or delete comments.
- **Authentication**: Supports both session cookies and HTTP Basic Access Authentication.

### Authentication Protocols
The project implements two main authentication methods:
- **Session Cookies**: A secure mechanism to maintain user sessions. It allows users to remain authenticated between actions without repeatedly entering credentials.
- **HTTP Basic Authentication**: Utilized for direct API requests, requiring credentials to be included in the request headers. Unauthorized actions are blocked with appropriate error codes (403 for forbidden and 404 for non-existent resources).

## Code Tree

<pre>

</pre>
