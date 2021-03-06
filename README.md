# jwlin-react-web-app

[![npm version](https://badge.fury.io/js/npm.svg)](https://badge.fury.io/js/npm)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/jwlin17/jwlin-react/issues)

## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

As a student studying Data Science but passionate about Computer Science, I thought it would be beneficial to learn how to implement a frontend and backend system using the best practiced methods. My goal is to write a Full-stack web application that not only loads instantly(almost) but is also well documented, aesthetically pleasing, and effectively displays my portfolio. 

I want my website to show **why** I am pursuing Data Science. I deeply appreciate any feedback or advice about my website because I know there are constant improvements and changes in the ways we code. 

## Index
- [About](#about)
- [Installation](#installation)
- [Documentation](#documentation)
- [Todo List](#todo-list)
- [References and Guides](#references-and-guides)

## About

Building my Full-stack progressive web application - Aiming for near instant load times

*Disclaimer: This README is really entry-level and helpful to remind me keep track of the various tools I used in my process. While I spent a lot of time on this project, I know this is just the beginning. It is merely a practice project for a budding software engineer such as myself*

## Installation
**TODO**
**Will create a more thorough guide of how to install after finishing project**
Probably using yarn to quick install all Dependencies needed. Will also be implementing Greenkeeper to help keep dependencies updated as painlessly as possible.

## Documentation

Each section below documents why I used the tools I used and how I used them. These are just the tools I found most relevent and worthwhile to learn my first project, but not necessarily the best.

  - Structure:
    - [Isomorphic / Universal JS](#isomorphic--universal-js-with-node-express--react)
    - [React](#react) 
    - [Node.js](#nodejs)
    - [Express.js](#expressjs)
  -  Styling:
    - [React-Bootstrap](#react-bootstrap)
  - Configuration Tools:
    - [Babel](babel)
    - [Webpack](#webpack)
    - [Nodemon](#nodemon)
    - [ESLint](#eslint) (Airbnb)
      
### Isomorphic / Universal JS with Node (Express) + React

Going into this project, I was not really familiar with any of the industry standard practices. If I had a chance to restart, I would have started with learning about Isomorphic JS first. It really changes the way you understand client-side vs. server-side rendering and how to optimize the interaction between the two. Check [this link](https://developer.ibm.com/node/2015/06/10/node-js-react-isomorphic-javascript-why-it-matters/) out for an AMAZING intro on the topic. 

#### Side-Note: The isomorphic/universal version is not polished yet so I decided to not push to github as of yet. Just imagine this current project but faster and smoother transitions. :)

### React

I conducted a decent amount of research to decide between using Angular or [React](https://reactjs.org/). Ultimately, it felt that React is the generally more recommended structure for my first web app. As well as, an excuse to learn how to use Javascript more efficiently. React and Node.js seemed to be more often requested by job listings as well making it a great first thing to learn. Although, realistically I think the fundamental differences are miniscule and I could have used either to accomplish my tasks.

### Node.js
[Node.js](https://nodejs.org/en/)
**TODO**
### Express.js
[Express.js](https://expressjs.com/)
**TODO**

### React Bootstrap

I decided to use [React Bootstrap](https://react-bootstrap.github.io/) because I am familiar with bootstrap css styling from previous projects. Therefore using the react version of bootstrap would be less of a headache. In addition, it was really easy to install and use with plenty of available support and guides online already. Bootstrap is one of the most popular styling frameworks for a reason right?

### Babel

[Babel](https://babeljs.io/) allows us to load and implement various features in Javascript that might not be natively supported. From my readings, Babel seemed to be the most supported and recommended tool for supporting the platform I was building.

### Webpack

[Webpack](https://webpack.js.org/) is an incredible tool for bundling all of the Javascript in my project efficiently. There are many guides on code splitting and lazy loading that allow for quick web loading which was a key goal of this project.

### Nodemon
[Nodemon](https://github.com/remy/nodemon)
**TODO**
### ESLint

[ESLint](https://eslint.org/docs/about/) is a linting tool that allows for various configurations and styling rules. Deciding between an Airbnb config set and a Google config was difficult. It seemed odd that I would choose alternatives against Google every time but it just fit better for my styling. Take a look at the differences in [this article](https://medium.com/@uistephen/style-guides-for-linting-ecmascript-2015-eslint-common-google-airbnb-6c25fd3dff0). 
 
 ## Results
 ![Website Speed Test Score: 97](web-speed-test.png)
 
## Todo List
- [**NASDAQ Earnings Report Updates**](https://www.nasdaq.com/earnings/earnings-calendar.aspx)
- **Travel Blog Content**

## References and Guides
    
Amazing Universal / Isomorphic JS Guide - https://developer.ibm.com/node/2015/06/10/node-js-react-isomorphic-javascript-why-it-matters/
Big Reference and Inspiration Guide - https://github.com/crsandeep/simple-react-full-stack/edit/master/README.md    
Guide of Badges and Clean Repos - https://github.com/dwyl/repo-badges/edit/master/    
For Build passing guide and TDD - https://github.com/dwyl/learn-travis    
For Link Routing and Page Navigation - https://medium.freecodecamp.org/beginners-guide-to-react-router-4-8959ceb3ad58
