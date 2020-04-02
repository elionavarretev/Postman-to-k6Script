[![N|Solid](https://raw.githubusercontent.com/loadimpact/postman-to-k6/master/assets/postman-to-k6-cover.png)](https://github.com/loadimpact/postman-to-k6)

# Setting up
To run this tutorial, you will need:
* [Node.js](nodejs.org) - JavaScript runtime environment that executes JavaScript code outside of a web browser.
* [Postman](https://www.postman.com/) - Tool that is used, above all, for the REST API.
* [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable) - Dependency manager.


Code Editor:
* [VisualCode](https://code.visualstudio.com/) 
* [Notepad++](https://notepad-plus-plus.org/downloads/)

Now clone this project to your local machine:

```sh
$ git clone https://github.com/elionavarretev/Postman-to-K6.git
```
# Building the project
This project uses a node.js. To run the tests and build an executable jar, open the terminal and run:

```sh
$ npm init --y
```

then, you will need postman-to-k6.

```sh
$ yarn add postman-to-k6
```

# How To Run From Command Line

```sh
$ postman-to-k6 .\\Postman\\Collection\\K6-scritpt.postman_collection.json  --environment .\\Postman\\Environment\\K6-scritpEJEMPLO.postman_environment.json -o .\\k6\\k6-script.js
```
# Note:
Please run and review the code
If you think something needs to be improved; you can indicate the file issue or submit PR.
