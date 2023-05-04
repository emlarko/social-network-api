# NoSQL: Social Network API

## Summary 

The aim of this project was to build an API for a social network application using the Express.js and Mongoose packages. The users of the application are able to share thoughts, react to friends’ thoughts, and create a friend list.

## Table of Contents

- [Technology](#technology)
- [Installation](#installation)
- [Usage](#bracket-expressions)
- [Walkthrough Video](#walkthrough-video)

### Technology

This project was created with:

- JavaScript
- Node.js
- Express.js
- MongoDB
- Mongoose

### Installation

After cloning the project to your machine, run the following line of code in your terminal to install the needed packages:

```
npm i
```

### Usage

Once the packages have been installed using the above instructions, run the following line of code to start the applications server:

```
node index.js
```

After starting the applications server, the user will be able to test the API routes in Insomnia.

When opening the API GET routes in Insomnia, the user will be able to view all the data for Users and Thoughts.They will also be able to view individual Users and Thoughts by providing the ID in the GET request.

When viewing Users, the individual User's thoughts and friends can be viewed, a long with a friend count. When viewing Thoughts, the reactions from friends can also be viewed as well as a reaction count. 

When using the API POST and PUT routes in Insomnia, the user is able to successfully create and update Users and Thoughts. The POST route can also be used to add friends to a User's friend list, and reactions to a Thought.

When using the DELETE route, the user is able to delete a User or a Thought, as well as a friend or a reaction. When a User is deleted, their associated Thoughts are also deleted. 

### Walkthrough Video

[Social Network API.webm](https://user-images.githubusercontent.com/101362057/236234761-fc9adac2-4248-49c6-8a52-784fbaaf9254.webm)
