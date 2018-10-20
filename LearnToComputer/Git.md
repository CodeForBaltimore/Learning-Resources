# Learning Git

# Learning Node.js

Node.js (commonly referred to as Node) is a JavaScript Runtime built on Chrome's V8 JavaScript engine.  More information can be found at the official [Node.js website](https://nodejs.org).  Below is an example of a Node.js "Hello World" from the about page.

```js
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World\n');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});
```

## Installing Node

Installing Node is straight forward in most operating systems.  Installing Node will also install the NPM package manager as well.  NPM is used to install packages that run in your projects on Node like React, Angular, Vue, Express, and many more.

Most users just getting started with Node are best to install the LTS (Long Term Support) version of Node.  As you gain proficiency, installing Latest versions or using Node Version Manager (NVM) will provide more options.

### MacOS

#### Direct Download

Visit the [Downloads](https://nodejs.org/en/downloads) page of the Node website to download the install package file.

#### Brew Install

From the command line in Terminal:

```
brew install node@8
```

### Windows

#### Direct Download

Visit the [Downloads](https://nodejs.org/en/downloads) page of the Node website to download the install msi file.

#### Chocolatey Install

From the command line in CMD or PowerShell:

```
C:\> choco install nodejs-lts
```

### Linux

Visit the [Installing Node.js via package manager](https://nodejs.org/en/download/package-manager/) page for instructions for your distribution.  

## Beginners

All of these tutorials are going to expect a level of understanding of JavaScript.  If you are new to web development, please look at the Learning JavaScript section first.

All of these resources are free and give you a great introduction to Node in a try before you buy setting.

### [Node School](https://nodeschool.io)

One of the best beginner resources on the web to get started with Javascript & Node programming.  Look for the LearnYouNode course to get started.

### [w3schools.com](https://www.w3schools.com/nodejs/)

One of the best beginner resources for web development as a whole.  They have a great tutorial to get you familiar with Node among many other things.

### [freeCodeCamp](https://www.freecodecamp.org)

A free online web development bootcamp.  Their latest curriculum has rolled out this year and includes Node and Express tutorials and projects.

### [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

Next to Stack Overflow, probably the second most used resource on the web about the web.  This a great introduction to Node and it's most used framework, Express.

### [Node Documentation](https://nodejs.org/en/docs/)

The best place to learn is at the root.  If you are developing in Node, having the documentation bookmarked is a must have.

## Advanced Learners

This section is for those that are looking to move to the next level in Node development.  Some of these resources are free and some are paid.  You do not have to pay to learn Node, but some of these paid resources are worth the mention.

### [YouTube](https://www.youtube.com)

YouTube has a wealth of knowledge both good and bad.  You must look at the date released or you could learn outdated material.  Some providers of great content are (but not limited to):

* Programming with Mosh
* Traversy Media
* freeCodeCamp
* Derek Banas
* The Net Ninja
* LevelUpTuts
* Wes Bos
* LearnCode.academy

### [egghead.io Introduction to Node](https://egghead.io/courses/introduction-to-node-the-fundamentals)

Even though this is titled an introduction to Node, the course goes more in depth than most introduction courses.  A great free resource that starts branching out.

### [Learn Node - by Wes Bos](https://wesbos.com/learn-node/)

A paid course that is worth the money.  It walks you start to finish through a full stack restaurant application covering topics like authentication, database storage, REST APIs, and more.  Follow Wes on Twitter and he usually gives out discount codes every couple of months.

### Online Training Academies

There are several online training academies on the market and all of them offer a trial.  Try them all to see which ones you like or if it's not for you.  Here are some of the most popular:

* [PluralSight](https://www.pluralsight.com/)
* [Lynda / LinkedIn Learning](https://www.lynda.com/)
* [Team Treehouse](https://teamtreehouse.com/)
* [Codecademy](https://www.codecademy.com/)
* [Udemy](https://www.udemy.com/)

## Other Resources

As you learn more about Node you will become more aware of the surrounding ecosystems.  For more information you can look into specific stacks that include Node.  Some of the most popular are:

* MEAN - **M**ongo, **E**xpress, **A**ngular, and **N**ode
* MERN - **M**ongo, **E**xpress, **R**eact, and **N**ode
* NERP - **N**ode, **E**xpress, **R**eact, and **P**ostgreSQL

