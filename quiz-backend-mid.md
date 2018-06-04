## Introduction

In this task, you are required to build a RESTful api to filter [HackerNews](https://github.com/HackerNews/API) __top stories__ via keywords. You are required to build the api using [expressJS](https://expressjs.com/).


## The tasks

* Create an restful api of the follow endpoint:
`GET /searchnews?query={keyword}`

* Should filter through __HackerNews__ top stories, and retrieve any relevant `title` which has (case insensitive) the `keyword` provided:
```
https://hacker-news.firebaseio.com/v0/topstories.json?print=pretty
```

* All the results from `/searchnews` return must be in a proper `json` format like the following:
```
[
	{
		title: 'New update to Github',
		time: 152148712,
		type: 'story',
		score: 203,
		url: 'https://someurl.com'
	},
	...
]
```

* As the __HackerNews__ API does not return story details in the `/v0/topstories`, all stories must be subsequently populated using multiple calls API calls on another HN API.

* The solution provided must be executable locally and server.


## Unit tests

All of the APIs should have unit test coverage; invoking `npm test` should test your package. We suggest mocha but other frameworks are fine.


## Criteria

Your work will be evaluated primarily on:

* Consistency of coding style
* Idiomatic use of `express`
* Correct use of promises, including proper error handling. async/await may be used
* Absence of "callback hell"
* Correct and complete unit test coverage
* General quality of code and technical communication.

## How to submit your work

Please commit your source code to your **Github** repository as your commits pattern will be assessed as well. Once you have completed the quiz, do share to us the link to the repository.

Please include the instruction on how to run your application in a `README.md` file.