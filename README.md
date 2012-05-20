A collection of Packages and Clipping Sets for BBEdit.

# Packages

## [CoffeeScript](http://coffeescript.org)

### Codeless Language Module

- Keywords and predefined names
- String coloring, including multi-line and block strings
- Regular expressions (including block regular expressions) are colored as strings.
- Comments (line and block)
- Function folding and names in the function popup. It'll match functions like this:
    ```coffeescript
    square = (x) -> x * x
    ```
  Or this:
    ```coffeescript
    grade = (student) ->
      if student.excellentWork
        "A+"
      else if student.okayStuff
        if student.triedHard then "B" else "B-"
      else
        "C"
    ```
  Or class methods, like this:
    ```coffeescript
    move: ->
      alert "Slithering..."
      super 5
    ```
  Or even this:
    ```coffeescript
    String::dasherize = ->
      this.replace /_/g, "-"
    ```
  
  Note that, due to a limitation of BBEdit's codeless language modules, nested functions will not be parsed.
- Function lookup in the [MDN Reference Library](https://developer.mozilla.org/en/JavaScript)

### Scripts

- **Compile** - Run file through the CoffeeScript compiler and open the resulting JS file.
- **Show Javascript** - Run file through the CoffeeScript compiler and show the resulting JS (does not save file to disk).
- **Run** - Runs the file and opens a new window with the results.
- **Run Selection** - Runs the selected lines and opens a new window with the results. Note that the entire line will be run, even if it is only partially selected.


## [Jade](http://jade-lang.com/) template engine

### Codeless Language Module

- Keywords and predefined words
- Comments, including multi-line block comments and HTML-style comments
- [Blocks](https://github.com/visionmedia/jade#block-append--prepend) map to functions, so block names show up in the function pop-up and can be folded.


## [Stylus](http://learnboost.github.com/stylus/) CSS framework

### Codeless Language Module

- Keywords and lots of predefined names
- Look up CSS properties in the [MDN Reference Library](https://developer.mozilla.org/en/CSS/)
- Comment syntax coloring (both // and /* */ syntax)
- Function/mixin folding and names in the function popup
- String coloring

### Clippings

Clippings for some common CSS properties.


# Clipping Sets

- NodeJS and the [Express](http://expressjs.com) framework.