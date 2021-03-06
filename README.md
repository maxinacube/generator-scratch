# Scratch

Scratch is a [Yeoman generator](http://yeoman.io) for quickly creating new WordPress projects.

## Getting Started

If you need it, install Yeoman through npm:

```
$ npm install -g yo
```

To install generator-scratch clone this repository, enter the directory, and link it to npm:

```
$ git clone git@github.com:mrdink/generator-scratch.git && cd generator-scratch
$ npm link
```

Finally, in the desired project directory, initiate the generator:

```
$ yo scratch
```

![yo scratch:theme](/screens/scratch-theme.gif?raw=true "yo scratch:theme")

## Project Types

Scratch ships with two default project types, each invoked with a subgenerator.

For each project type you get:

- Bower to manage front-end dependencies
- NPM to manage development dependencies (like Grunt)
- Grunt to streamline development

### Foundation Support

Choose from using Foundation 5 or 6 using the following.

```
$ yo scratch:f5
$ yo scratch:f6
```

### Theme

This subgenerator scaffolds out a standard WordPress theme.

### Child Theme

This subgenerator scaffolds out a standard WordPress child theme.

## License

MIT

## Credit

glass by juan manjarrez from the Noun Project
