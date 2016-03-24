# cl.js - console.log at the speed of light!
cl.js is a *30 byte small* JavaScript snippet that speeds up the repetitive task of logging variables.

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
- Download 'cl.min.js' and link it to your page with a script tag. Make sure you link it above the script files you want cl.js to affect!
```
<script src="path/to/file/cl.min.js"></script> // replace 'path/to/file'

// insert other scripts here
```
- Or, manually paste the snippet below at the top of your JavaScript file(s).
```
var cl=function(x){console.log(x)}
```
- Finally, use the smaller, more enjoyable cl.js syntax! `cl(x);`

*PS: You can rename the `cl` function to customize usage.*

*PPS: You should probably remove cl.js before you push production code.*

## License
[MIT](https://github.com/johnchinjew/cl.js/blob/master/LICENSE)

## Awknowledgements
cl.js was thought up and created by [John Chin-Jew](http://johnchinjew.com). Follow on Twitter: [@johnchinjew](http://twitter.com/johnchinjew)!
