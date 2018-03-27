# React Frontend Quiz
This is a basic quiz to to assess your familiarity with the technology stack we're using. If you are familiar with the tech stack, this should only take 30-45 minutes of your time.

Please commit your source code to your **Github** repository as your commits pattern will be assessed as well. Once you have completed the quiz, do share to us the link to the repository.

Please include the instruction on how to run your application in a `README.md` file.

## Introduction
In a Redux-backed React App, actions are often dispatched from different places, eg: Mouse click on button, Asynchronous response from http APIs, etc. One challenge of writing an __Web Application__ is that application's actions are often triggered from _url changes_. 

## Task One
Create a React web app which can do the following:
- Search public Github repositories
- Has a _text input field_ where user can type in the (part of the) name of the _Github_ repository
- The app in turn searching for the repository via [Github API v3](https://developer.github.com/v3/)
- Results of the search must be displayed in a list below the _search field_. (Just displaying the repositories' name with anchor link to source it will do)
- The browser url must display the search query upon every keystroke input by the user, something like this:
	```
	http://localhost:8080?search=react
	```
- Users are allowed to directly visit the domain with `search` query intact. For example, if user key in `http://localhost:8080?search=redux` directly into the browser url, the _search field_ should be pre-filled with the word `redux` and search results list below it should display the relevant results.

## Task Two
In the Application above, search (API call) will be triggered upon every keystroke from the user. This is not ideal as it will consume up the [rate limit](https://developer.github.com/v3/#increasing-the-unauthenticated-rate-limit-for-oauth-applications) too quickly. __Without__ implementing a hard button for the "search action", how would you design a solution where user can search without pressing a button on UI, while not consuming the quota too quickly.