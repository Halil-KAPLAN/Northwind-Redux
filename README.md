# Northwind-Redux


## Description

My first project with React. A simple store management system. Redux and Reactstrap were also used with React.


## Installation

NodeJS must be installed for the project to work.

- Download and install **node** (and **npm**): https://nodejs.org/en/
- Make sure you have an editor (I used VSCode)


### Install dependencies

Open a terminal or command prompt inside the project folder, then install the dependencies.

```Bash
# I used json-server for an example api.
$ npm install -g json-server
# Then follow this command to add the node_modules folder.
$ npm install
```

### Start the project

Open a terminal or command prompt inside the project folder.

```Bash
# First terminal
$ json-server --watch api/db.json --port 3001
# Second terminal
$ npm start
```

Then visit http://localhost:3000/
