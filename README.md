# React-Practice
## Introduction
Hi! In this exercise you will be learning basic and concepts of React and Redux and learning to apply them by building a react app. By the end of this exercise you should have a strong understanding of concepts and working of React, getting used to Agoda's standard & code review process.You would already have an assigned "buddy" to help you with this, if not reach out to your manager to get a dedicated person asssigned for this role. 

Listed below in the "All topics to cover" section you'll find topics we want to cover, and some tasks to do where you can apply what you have learnt.

You can start by creating a branch named `develop-yourname` eg: `develop-scotthanselman` and keep creating PR/MRs to this branch. There are a total of 6 tasks in this exercise, at the end of each excercise you have to raise a PR/MR and get it code reviewed with your help and/or team members.

**How can I be successful**
- Commit to learning. Demonstrate ownership of your learning and proactively drive your tasks.
- Don't assume you already know, and don't assume that you understand.
- Ask many questions, especially as you are getting started.
- Listen for and act on the feedback.
- Be proactive.
- Try new things, and always evaluate the outcome to see what you can improve next time. For most questions, please check with your buddy or manager first.

## All topics to cover
Javascript
- Collection management
- Event handling
- Typescript
- Promises

React basics - https://reactjs.org/tutorial/tutorial.html
- Creat React App
- React DOM
- setState
- Render & Re-render in React
- Hooks - useState & useEffect
- React router

State Management
- Context API
- Redux
- Reducers

Testing React
- Mocks & Spies
- Enzyme vs React Testing Library
- Snapshot testing

Tools
- React dev tools
- Redux dev tools

# Task Details

## Task 1 - Create react app with mock data
<img src="https://user-images.githubusercontent.com/70643030/174858081-b8d91f6a-a95c-40af-a381-21e3f531871f.png" width="300" />

### Topics to be learnt in this section
- [ ] Javascript - Collection management (map/reduce/filter)
- [ ] Javascript - Event handling
- [ ] Typescript
### Task details
- [ ] Create a new app using Create React app with Typescript
- [ ] Implement header, to show logo and app name
- [ ]  Using the below hardcoded list of data implement UI to show a list of characters
```
['Rick Sanchez', 'Morty Smith', 'Summer Smith', 'Beth Smith', 'Jerry Smith']
```
- [ ] Implement search functionality, user should be able to search using both button and press of ENTER key
- [ ] Setup ESLINT using [agoda config](https://github.com/agoda-com/eslint-config-agoda) and fix errors if any
- [ ] Prepare documentation on how to run your app, lint etc
- [ ] Code review with peers

## Task 2 - Use a real API
<img src="https://user-images.githubusercontent.com/70643030/174858156-c0badc44-662b-41c3-b823-7f824c36b772.png" width="300" />

### Topics to be learnt in this section
- [ ] Javascript - Promises
- [ ] React - Hooks useState & useEffect
### Task details
- [ ] Fetch data using Rick&Morty API - https://rickandmortyapi.com/documentation/#filter-characters
- [ ] Show more details about each character
- [ ] Show loader/errors
- [ ] Handle no results
- [ ] Pagination, default page size = 5
- [ ] Show all characters if no search term present
- [ ] Code review with peers

## Task 3 - Implement new page using react router
<img src="https://user-images.githubusercontent.com/70643030/174858234-e7114858-d844-416d-a7c3-33059d8036d2.png" width="300" />

### Topics to be learnt in this section
- [ ] React - react router
### Task details
- [ ] Open a new page when user clicks on the card
- [ ] New page to show more details about the character selected
- [ ] Code review with peers

## Task 4 - Implement themeing using Context API
<img src="https://user-images.githubusercontent.com/70643030/174858258-12a28223-81fc-4bd7-9c71-5822d2714faf.png" width="300" />

### Topics to be learnt in this section
- [ ] Context API
### Task details
- [ ] Implement option to change from light/dark mode
- [ ] Code review with peers

## Task 5 - Implement themeing using Redux

### Topics to be learnt in this section
- [ ] Redux
### Task details
- [ ] Introduce Redux where you think is making sense
- [ ] Code review with peers

## Task 6 - Testing
### Topics to be learnt in this section
- [ ] Testing React components
- [ ] Mocks & Spies
- [ ] Enzyme vs React Testing Library
- [ ] Snapshot testing
### Task details
- [ ] Add all kinds of tests
- [ ] Code review with peers

# All done!
Congratulations! You have reached the end of the exercise. Please share you feedback by filling this survey <insert-survey-link-here>, and if you have found any issues/inconsistency/or-have-ideas to make this exercise better, please help submit an MR. (and get a chance at some cool Agoda merch)

Next you may be interested in the following, please check with your buddy or manager before proceeding.
- Deploying your React App on K8s
- Using Drone JS on your React App

Thank you!
