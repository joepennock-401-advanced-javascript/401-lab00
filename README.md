# 401.js Deployment Tutorial

## Author: Joe Pennock
* [Githb PR](https://github.com/joepennock-401-advanced-javascript/401-lab00/pull/1)
* [node.js workflow tests](https://github.com/joepennock-401-advanced-javascript/401-lab00/actions/runs/129253848)
* [Live deployed application](https://joepennock-401-lab00.herokuapp.com/)

## Setup

### .env requirements:
* `PORT = 3000`

### Running the app:
* `npm start`
* Endpoint: /
    * Returns true or false

### Testing
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions made:
    * Assert that isAlive() properly returns a boolean
        * Endpoint `'/'` returns `true`
        * Endpoint `'/?dead=true'` returns `false`
* Assertions remaining:
    * Have not yer confirmed functionality of `jsdoc`