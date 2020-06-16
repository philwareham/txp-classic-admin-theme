# Classic admin-side theme for Textpattern CMS

[![Build Status](https://travis-ci.org/philwareham/textpattern-classic-admin-theme.svg?branch=master)](https://travis-ci.org/philwareham/textpattern-classic-admin-theme)
[![Known Vulnerabilities](https://snyk.io/test/github/philwareham/textpattern-classic-admin-theme/badge.svg?targetFile=package.json)](https://snyk.io/test/github/philwareham/textpattern-classic-admin-theme?targetFile=package.json)

The classic admin theme that ships as standard with [Textpattern CMS](https://textpattern.com/).

## Demos

[Design patterns documentation](http://design-patterns-classic.textpattern.com/docs/).

[Flat mockup of Textpattern admin area](http://design-patterns-classic.textpattern.com/mockups/).

## Supported web browsers

* Chrome, Edge, Firefox, Safari and Opera the last two recent stable releases.

## Build setup

### Installing required tools

The project uses [Grunt](https://gruntjs.com/) to run tasks and [Sass](http://sass-lang.com/) for CSS pre-processing. First make sure you have base dependencies installed: [Node.js](https://nodejs.org/) and [Grunt](https://gruntjs.com/). You can install Node using the [installer](https://nodejs.org/) and Grunt with npm:

```ShellSession
$ npm install -g grunt-cli
```

Consult the Grunt documentation for more instructions if necessary.

### Installing dependencies

After you have the base dependencies taken care of, you can install the project's dependencies. Navigate to the project's directory, and run the dependency manager:

```ShellSession
$ cd textpattern-classic-admin-theme
$ npm install
```

**npm** installs Node modules for Grunt.

## Building

This repository hosts sources and needs to be built before it can be used. After you have installed all dependencies, you will be able to run tasks using Grunt, including building:

```ShellSession
$ grunt @task@
```

Where the `@task@` is either `build` or `watch`.

* The `build` task builds the project.
* The `watch` task will launch a task that watches for file changes; the project is then automatically built if a source file is modified.

## Pre-built version

We provide a pre-built version of the theme files within the `dist` directory in case you don't want to build it yourself.

## License

Licensed under the [GPLv2 license](https://github.com/philwareham/textpattern-classic-admin-theme/blob/master/LICENSE).
