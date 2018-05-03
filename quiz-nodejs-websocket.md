# Node.JS Software Quiz

This is a basic quiz to to assess your familiarity with the technology stack we're using. If you are familiar with the tech stack, this should only take 30-45 minutes of your time. If not familiar, it could take longer.

You are allowed to used any tools and library to complete the task

Please commit your source code to your **Github** repository as your commits pattern will be assessed as well. Once you have completed the quiz, do share to us the link to the repository.

## Pre-requisite
- Node.JS (see [https://nodejs.org/en/](https://nodejs.org/en/))

## The task:

In this challenge, you will need write a simple websocket and authentication server.
- Implement a RESTful login API by __email + password__ ( you can hardcode for the login credentials for this purpose )
- Upon successful request, the Auth module should return a secured JWT
- With the JWT, the user should then be allowed to establish a websocket connection to your websocket server. Some kind of authentication must happen during the initial establishment of the websocket connection.
- Deny connection to the websocket server whenever the JWT is not valid
- Design and write the test cases against the scenarios above