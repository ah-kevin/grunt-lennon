# grunt-lennon

> bug 88

## Getting Started
This plugin requires Grunt.

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-lennon --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-lennon');
```

## The "lennon" task

### Overview
In your project's Gruntfile, add a section named `lennon` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  lennon: {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
})
```

### Options

#### options.separator
Type: `String`
Default value: `',  '`

A string value that is used to do something with whatever.

#### options.who
Type: `String`
Default value: `'buddha'`

指明是哪一种
#### options.commentSymbol
Type: `String`
Default value: `'//'`
使用的是哪一种注释符

A string value that is used to do something else with whatever else.

### Usage Examples

#### Default Options
In this example, the default options are used to do something with whatever. So if the `testing` file has the content `Testing` and the `123` file had the content `1 2 3`, the generated result would be `Testing, 1 2 3.`

```js
grunt.initConfig({
  lennon: {
    options: {
      'who':'buddha,
          'commentSymbol':'//'
    },
    dist:['examples/*.js']
  },
})
```


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
150410 &nbsb&nbsb&nbsb&nbsb&nbsb;

## License
Copyright (c) 2015 lennon. Licensed under the MIT license.
