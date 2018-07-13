# Ember-vs-React-Ember

This project is the Ember code relating to the Ember vs React— the ultimate battle (Round 1) and 
Ember vs React - round 2 articles.

This is a very basic example of how to get started with Ember. It uses firebase for data persistence
and sass for styling. 

## Common Commands

`ember serve` - Starts the project and go to localhost:4200 to view the project

`ember test` - Runs the tests

## Firebase 

1. You need to make a firebase account.

2. Create a project
  * Click on database tab 
  * Click real time database 
  * Click start in test mode 

3. Go to overview page 

4. Click 'Add firebase to your web app'

5. Create a file called firebase.js in the config folder. And copy the firebase object into it so it looks similar to this:

```javascript
module.exports = {
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: ""
  };
```

And then you will have your own firebase setup.

## Articles:

[Ember vs React— the ultimate battle (Round 1)](https://medium.com/buildempire/ember-vs-react-the-ultimate-battle-round-1-dcc034bc725d)

[Ember vs React - Round 2](https://medium.com/buildempire/ember-vs-react-round-2-f07b07f49bb9)





