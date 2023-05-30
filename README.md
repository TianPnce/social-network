# NoSQL: Social Network API

## Description
API for social network application where users can share their thoughts. In the following functions you are able to create, update, delete users, aswell as creating and deleting thoughts. There is no front end for this web application, evrything has been tried through Insomnia

## Table of Contents
* [Walkthrough](#walkthrough)
* [Technology](#technology)
* [Installation](#installation)
* [Usage](#usage)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)

## Walkthrough
[Click me to watch walkthrough!](https://watch.screencastify.com/v/vrGMZsslNUWklSOGLLCQ)

## Technology
- Node.js
- Express.js
- Mongoose

## Installation
Run `npm i` to install dependencies

## Usage
`npm start`

## User Story
```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Notes
I found this assignment to come really useful and will take what I learned and apply it to future projects. Issues that I did run into was adding and removing friends, I would get a "wrong id" message but could not figure out the root of the problem.

## Questions
[TianPnce](https://github.com/TianPnce)
