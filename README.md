# grunt-contrib

A collection of general use grunt tasks.

## Getting Started
Install this grunt plugin next to your project's [grunt.js gruntfile][getting_started] with: `npm install grunt-contrib`

Then add this line to your project's `grunt.js` gruntfile:

```javascript
grunt.loadNpmTasks('grunt-contrib');
```

[grunt]: https://github.com/cowboy/grunt
[getting_started]: https://github.com/cowboy/grunt/blob/master/docs/getting_started.md

## Documentation
Grunt-contrib is currently alpha-quality software.  See the docs dir for more information.

## Contributing

#### Configuration
In order to ensure a consistent configuration style, task submissions should retreive their optional parameters with the included grunt helper, [options](/gruntjs/grunt-contrib/blob/master/docs/options.md).

#### Testing
Tests must be included with your submission.  New tasks can be added to the config in `test/grunt.js`, please see existing tests for guidance.  *Currently, testing with grunt is a bit cumbersome--this will be addressed in a future release.*

#### Running Tests
The following assumes you know how to use command prompt/shell and have nodejs and npm setup on your system.

From the project root, install required packages with npm via shell

```bash
npm install grunt -g  # optional for ease of use on windows
npm install;  # installs all the libs needed for various tasks
```

Switch to the ```test``` directory within the project and run ```grunt``` via shell.

You should see the status of each test and/or errors in your shell.

happy debugging :)

## Release History

* 2012/05/17 - v0.0.3 - Cleanup release.  Getting task configuration consistent.
* 2012/05/01 - v0.0.2 - Remove some debugging code.
* 2012/05/01 - v0.0.1 - Alpha release.

## License
Copyright (c) 2012 "Cowboy" Ben Alman & contributors.
Licensed under the MIT license.
