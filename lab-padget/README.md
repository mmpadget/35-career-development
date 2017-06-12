# Lab 35: Hash Table Data Structure

## Description
For this lab created a hash table constructor with buckets that were implemented as an array of doubly-linked-lists. We also implemented the following prototype methods: .hash(key), .set(key), .get(key), and .remove(key).

* [Class 35](https://github.com/codefellows/seattle-javascript-401d15/tree/master/class-35-career-developent)
* [Lab 35](https://github.com/mmpadget/35-career-development)

1. Version
2. Installation
3. Application
4. Tests
5. Resources
6. License
7. Acknowledgments

## Version
* 0.1.0

## Installation
Please visit the following pages for how to install your project locally.

* [Cloning A Repository](https://help.github.com/articles/cloning-a-repository/)
* [Fork A Repo](https://help.github.com/articles/fork-a-repo/)
* [Forking](https://guides.github.com/activities/forking/)

### Node
You need to have node.js installed.
* [Download Node](https://nodejs.org/en/)

### NPM Packages
* [NPM Docs](https://docs.npmjs.com)
* [NPM package.json](https://docs.npmjs.com/files/package.json)

### JSON Configuration
Initializing package.json
```
npm init
```

Dev Dependencies:
```
npm i -D angular-mocks chai karma karma-chrome-launcher karma-mocha karma-mocha-reporter karma-phantomjs-launcher karma-webpack mocha
```

Add the following to package.json:
```
"scripts": {
  "test": "karma start --single-run",
  "test-watch": "karma",
}
```

### Dependencies
The result of installation above:

```
"dependencies": {

},
"devDependencies": {
  "angular-mocks": "^1.6.4",
  "chai": "^4.0.2",
  "karma": "^1.7.0",
  "karma-chrome-launcher": "^2.1.1",
  "karma-mocha": "^1.3.0",
  "karma-mocha-reporter": "^2.2.3",
  "karma-phantomjs-launcher": "^1.0.4",
  "karma-webpack": "^2.0.3",
  "mocha": "^3.4.2",
}
```

### Test Setup
```
karma init karma.conf.js

Which testing framework do you want to use ?
> jasmine

Do you want to use Require.js ?
> no

Do you want to capture any browsers automatically ?
> Chrome

What is the location of your source and test files ?
> test/**/*-test.js

Should any of the files included by the previous patterns be excluded ?
> no

Do you want Karma to watch all the files and run the tests on change ?
> no

Adjust the configuration karma.conf.js file to:

```

## Application
In [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) (Terminal) enter the command:

`node entry.js`

## Tests
In [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) (Terminal) enter the command:

`npm run test`
`npm run test-watch`

## Resources
* [Hash Table](https://en.wikipedia.org/wiki/Hash_table)
* [Linked List](https://en.wikipedia.org/wiki/Linked_list)
* [Doubly Linked List](https://en.wikipedia.org/wiki/Linked_list#Doubly_linked_list)

## License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/mmpadget/) file for details.

## Acknowledgments
* Code Fellows
* Scott Schmidt, Instructor
* Cayla Zabel, Teaching Assistant
* Devon Hackley, Teaching Assistant
* Thomas Martinez, Teaching Assistant
* JR Iriarte, Teaching Assistant
