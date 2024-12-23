# URL_Shortener

I.Introduction
This is an application for storing shortened URLs. It consists of a web interface that serves as a graphical interface for the user, a C application for encoding and decoding URLs, and a database for mapping short and long URLs.

Objective: Provide a fast and efficient URL shortening service.



II. Features
1. Shortening Long URLs into Short Links
The application allows users to convert long and complex URLs into concise, user-friendly short links. This feature ensures better readability and easier sharing across platforms.

2. Automatic Redirection to Original URLs
When a short link is accessed, the system automatically redirects the user to the corresponding original URL, providing a seamless browsing experience.

3. User-Friendly Web Interface
The web interface is designed to be simple and intuitive, making it easy for users to interact with the application, whether they are creating or accessing short links.

4. Flask-Based Backend
The backend is built using Flask, a lightweight and efficient Python web framework. Flask ensures smooth handling of user requests, processing, and communication between the interface and the URL encoding/decoding logic.

5. Encoding and Decoding Algorithm in C
A robust algorithm implemented in C is used for encoding long URLs into unique short codes and decoding them back into their original form. This approach leverages the performance of C for high-speed and reliable processing.



III. Project Architecture
The project is designed with a modular architecture to ensure smooth interaction between its components.

Web Interface:
Developed using modern web technologies such as HTML, CSS, and JavaScript, the web interface serves as the primary point of interaction for users. It allows users to input a long URL, which is then processed to generate a corresponding short link.

Flask Server:
The Flask server acts as the backbone of the application, providing a REST API for seamless communication between the web interface and the C application. It handles HTTP requests (such as POST for creating short URLs and GET for redirection) and ensures efficient data flow.

C Application:
The C application implements the core algorithm for converting long URLs into unique short codes. It also decodes short codes back into their original URLs, leveraging the speed and efficiency of the C programming language for optimal performance.



IV. Prerequisites
To run this project, the following tools and software are required:

Python (recommended version: 3.10+): Python is needed to run the Flask server and handle the web-based functionalities.
Flask: A lightweight Python web framework used to build the server and handle HTTP requests.
C Compiler (e.g., GCC or Clang): A C compiler is required to compile the C application that handles the URL encoding and decoding processes.
Web Browser (e.g., Chrome, Firefox): A modern web browser is necessary to interact with the web interface and test the functionality of the shortened URLs.





