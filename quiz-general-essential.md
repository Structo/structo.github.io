# React SocketIO Quiz

This is a basic quiz to to assess your familiarity with the technology stack we're using. If you are familiar with the tech stack, this should only take 30-45 minutes of your time. If not familiar, it could take longer.

You are allowed to used any tools and library to complete the task

Please commit your source code to your **Github** repository as your commits pattern will be assessed as well. Once you have completed the quiz, do share to us the link to the repository.

## Pre-requisite
- Node.JS (see [https://nodejs.org/en/](https://nodejs.org/en/))
- SocketIO library (see [https://socket.io/](https://socket.io/))

---

## The tasks:

### Task One
In this challenge, you will need write a SocketIO server. [Click here to find out more about SocketIO](https://socket.io/)

This server will be used to respond to a few predefined client requests. You can use [this online client](http://amritb.github.io/socketio-client-tool/) to test your result.

1. Upon sending/emitting _plain text_ request of `time-now` from **client**, the server should respond the following (in `time-response` event name):
```
Time now is Thu Mar 12 18:12:04 +08 2018 
```
| NOTE the time above should be dynamic and be the current time of request.

2. Upon requesting `date-tomorrow` from **client**, the **server** should respond the following (in `tomorrow-response` event name):

```
Tomorrow is Fri Mar 13.
```
| NOTE the date above should be corresponding to time of request.

---

### Task Two
