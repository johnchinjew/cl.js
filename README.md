# cl.js - console.log at the speed of light!
> 40 bytes, to make every programmer's life a *byte* easier!
cl.js is a tiny JavaScript snippet that speeds up the repetitive task of logging variables.

**Instead of writing this mush...**
```
console.log(x);
```
**Just write this!**
```
cl(x);
```
Want to try it out? Here's a CodePen **[demo](http://codepen.io/johnchinjew/pen/NNjBYG)**!

## Usage
- Download `cl.min.js` and link it to your page with a `<script>` tag. Make sure you link it **above** the script files you want cl.js to affect!
```
<script src="path/to/file/cl.min.js"></script>

// insert other scripts here
```
- Or, manually paste this snippet at the top of your JavaScript file(s).
```
var cl=function(){console.log(...arguments)} // you can actually rename 'cl' to anything you want to use instead of 'console.log'

// the rest of your js
```
- Finally, use the new logging syntax; like so! `cl(x);`

*PS: You should probably remove cl.js files and code before you push production code.*

## By the way
The cl.js snippet uses ES6, so make sure you're using an up-to-date browser. Here's the regular version for older browsers, just in case:

```
var cl = function() { console.log.apply(console,arguments) }
```

## More info
[Read the post!](http://codepen.io/johnchinjew/post/cl-js-console-log-at-the-speed-of-light)

## License
[MIT](https://github.com/johnchinjew/cl.js/blob/master/LICENSE)

## Awknowledgements
cl.js was thought up and created by [John Chin-Jew](http://johnchinjew.com). Follow on Twitter: [@johnchinjew](http://twitter.com/johnchinjew)!
