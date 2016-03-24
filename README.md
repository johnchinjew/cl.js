# cl.js - console.log at the speed of light!
> A single line of code, 30 bytes small, to make every programmer's life a *byte* easier!

**Instead of this unnecesarily lengthy mush...**
```
console.log(testVar);
```
**Just write this!**
```
cl(testVar);
```
And for good measure, take a CodePen **[demo](http://codepen.io/johnchinjew/pen/NNjBYG)**!

## Usage
1. Download 'cl.min.js' and link it to your page with a script tag. Make sure you link it above the script files you want cl.js to affect!
```
<script src="path/to/file/cl.min.js"></script> // change 'path/to/file/' to the file path to cl.min.js

// insert other scripts here
```
2. Or, manually paste the snippet below at the top of your JavaScript file(s).
```
var cl=function(x){console.log(x)}
```
3. And lastly, use the smaller, more enjoyable cl.js syntax! `cl(testVar);`

*PS: You can rename the `cl` function to customize usage.*
*PPS: You should probably remove cl.js before you push production code.*

## License
[MIT](https://github.com/johnchinjew/cl.js/blob/master/LICENSE)

## Awknowledgements
cl.js was thought up and created by [John Chin-Jew](http://johnchinjew.com). Follow on Twitter: [@johnchinjew](http://twitter.com/johnchinjew)!
