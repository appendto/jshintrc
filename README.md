# appendTo Standard .jshintrc file

This repository contains a standard .jshintrc for use with appendTo projects.

Options are current as of jshint@2.x.x.

### Use

To use a .jshintrc file, place it in the root directory of your project.

Install the jshint command globally with npm.

```
$ npm install -g jshint
```

Invoke the jshint command at the root of your project (or on specific folders or files within your project). Use the `-c` parameter to specify the location of the .jshintrc file.

```
$ jshint -c ./.jshintrc .
```

If you wish to exclude directories from jshint's reach, add a .jshintignore file to the root of your project and add ignore directives to it (same syntax as .gitignore files).

```
node_modules/
public/scripts/lib
```

Many IDEs and editors support .jshint natively, and will use your custom .jshintrc file automatically during the linting process.

### See also:

- [jshint options documentation](http://www.jshint.com/docs/options/)
- [Felix's Node.js Style Guide](http://nodeguide.com/style.html)