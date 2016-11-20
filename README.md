
# Yeoman generator for MEAN stack projects 

## Introduction

MEAN stack defines application using MongoDB, ExpressJS, AngularJS and NodeJS for a full Javascript development. This generator will help you to start with a solid base, which permits you to code faster. Some usual tasks are handled in sub-generators too.

## Prerequisites

To use the generator, you need some prerequisites :

- **[Node.js with NPM](http://www.nodejs.org/download/)**
- **[MongoDB](http://www.mongodb.org/)** (only needed if you want to use a local database, you could use a MongoDB web service like [Mongolab](https://mongolab.com/) too, but for development purpose it could be useful to have a local database)
- **[Yo](http://yeoman.io/)** - This package manage all Yeoman's generators 

```
$ npm install -g yo
```

- **[Bower](http://bower.io/)** - Bower will manage your frontend dependencies

```
$ npm install -g bower
```

- **[Grunt](http://gruntjs.com/)** - Grunt will automate some tasks to build your app or check if there's no error in your code.

```
$ npm install -g grunt-cli
```

## Installation

Install the generator 

```
$ npm install -g generator-mean-stack
```

Make a new directory and cd into it 

```
$ mkdir -p mean-project && cd $_
```

Scaffold a new MEAN stack project 

```
yo mean-stack
```

### App

Sets up a new MEAN stack app, generating all the boilerplate you need to get started.

Example: 

```
$ yo mean-stack
```
## Serve and build

The generator makes a gruntfile configuration, so building your app becomes easy.

Build a fresh new distribution :

```
$ grunt
```

Run the app server in development mode :

```
$ grunt serve
```

You can define a `production` target to serve in production mode :

```
grunt serve:production
```
