# start-node-project
node project starter

[![Build Status](https://travis-ci.org/suxxus/start-node-project.svg?branch=master)](https://travis-ci.org/suxxus/start-node-project)
<a href="https://codeclimate.com/github/suxxus/start-node-project"><img src="https://codeclimate.com/github/suxxus/start-node-project/badges/gpa.svg" /></a>


## Features ###
* npm scripts
* Lint ESLINT
* Unit testing TAPE

## Clone the repo & install
```
git clone https://github.com/suxxus/start-node-project.git
cd ./start-node-project
npm install
```
## Usage
* delete .git
* npm run start

## Scripts
The `package.json` file comes with the following scripts

`npm run <name of script>`

`test`: run provided unit tests.

`lint`: lint all code.

`start`:  runs a dev console that reports lint and unit tests and start watching for changes at *.js files

`check`: check outdated npm modules.

`coverall`: code coverage placed at ./coverage
