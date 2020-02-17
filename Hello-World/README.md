# Getting Started

Throughout this guide, we'll make extensive use of [Node.JS](https://nodejs.org/en/). Node.JS provides a great asynchronous event-driven JavaScript runtime using Chrome's lightning fast [V8 JavaScript engine](https://v8.dev/).

## Installing Node

### Visual Studio Code

See Microsoft's [tutorial](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial) to setup a development environment for Node.JS with Visual Studio Code.

## Hello World 

Create a new project folder titled `Hello World`. Then add a new file named `app.js` to the folder with the following content:

{% include "./Examples/Hello-NodeJS/app.js" %}

To run the file, just execute
```
node ./app.js
```
With the current working shell directory set to your `Hello World` folder. You should get the following output:
```
Hello World
```