# Social Network API

## Description and Requirements

This week's challenge was to build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. The application uses Express.js for routing, a MongoDB database, and the Mongoose ODM. 

No seed data is provided, so you’ll need to create your own data using Insomnia after you’ve cloned the API.

## Acceptance Criteria

```md

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

## User Story

```md

AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

```

## Walkthrough Video

https://drive.google.com/file/d/1k97rZ1cRWULzc5PfkWoRS7xRImtm6Z-l/view

## Live link?

Because this application isn't deployed, the walkthrough video demonstrates its functionality.