# The Mantis Project

The mantis project is a list of important reads, good bocks, great blog posts and comments about modern web development, web design and web technologies. Feel free to add important links as you like.


### General

Front-end performance for web designers and front-end developers

http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers


Slides about Web-Development / Frontend Development

https://speakerdeck.com/dmosher/so-you-want-to-be-a-front-end-engineer


Fixing a broken user Experience

http://uxdesign.smashingmagazine.com/2012/09/27/fixing-broken-user-experience/


Multi-Device Web Design: An Evolution

http://www.lukew.com/ff/entry.asp?1436


Google I/O 2012 - High Performance HTML5

http://www.youtube.com/watch?v=6EJ801el-I8



### Javascript


How to Learn JavaScript Properly

http://javascriptissexy.com/how-to-learn-javascript-properly/


3 ways to define a JavaScript class [b]

http://www.phpied.com/3-ways-to-define-a-javascript-class/

```Javascript
function Apple (type) {
    this.type = type;
    this.color = "red";
}
 
Apple.prototype.getInfo = function() {
    return this.color + ' ' + this.type + ' apple';
};
```

JavaScript undefined vs. null

http://saladwithsteve.com/2008/02/javascript-undefined-vs-null.html

jQuery Transit Plugin

http://ricostacruz.com/jquery.transit/


Professional Javascript® For Web Developers

http://www.amazon.com/Professional-JavaScript-Developers-Nicholas-Zakas/dp/1118026691/ref=sr_1_1?ie=UTF8&qid=1363526656&sr=8-1&keywords=Professional+Javascript+For+Web+Developers

```HTML
Correct include (XHTML):	
<script src="http://www.somewhere.com/afile.js"></script>

Deferred Scripts	
<script src="http://www.somewhere.com/afile.js" defer="defer"></script>

Correct XHTML inline JS	
<script type="text/javascript">
	//<![CDATA[
	function doStuff() { }
	//]]>
</script>

No JS available	
<noscript></noscript>
```

Function Declarations vs. Function Expressions

http://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/

```Javascript
//anonymous function expression
var a = function() {
    return 3;
}
 
//named function expression
var a = function bar() {
    return 3;
}
 
//self invoking function expression
(function sayHello() {
    alert("hello!");
})();

//Function Declaration
function add(a,b) {return a + b};

//Function Expression
var add = function(a,b) {return a + b};
```

A Few New Things Coming To JavaScript

http://addyosmani.com/blog/a-few-new-things-coming-to-javascript/


### CSS

Learning To Use The :before And :after Pseudo-Elements In CSS [b]

http://coding.smashingmagazine.com/2011/07/13/learning-to-use-the-before-and-after-pseudo-elements-in-css/

```CSS
a:after {
   content: attr(href);
}
```

25 Incredibly Useful CSS Tricks You Should Know [b]

http://webdeveloperplus.com/css/25-incredibly-useful-css-tricks-you-should-know/

```CSS
.elem{ 
	text-indent:-9999px; 
	background:url('someimage.jpg') no-repeat; 
	height: 100px; /*dimensions equal to image size*/
	width:500px;
}
a[href$='.doc'] { 
	padding:0 20px 0 0; 
}
body{ 
	font-size:62.5%;
}
```

Compatibility tables for support of HTML5, CSS3, SVG and more in desktop and mobile browsers.

http://caniuse.com/

Vertical Centering With CSS

http://blog.themeforest.net/tutorials/vertical-centering-with-css/

The Boring Bits Of CSS

http://alistapart.com/article/love-the-boring-bits-of-css

Learning CSS Layouts

http://learnlayout.com/

CSS Holy GraiL

http://alistapart.com/article/holygrail


###Editors

Javascript Integration in Sublime Text

http://thechangelog.com/whoa-sublime-web-inspector//

A Nice Sublime Text 2 Course

http://net.tutsplus.com/articles/news/perfect-workflow-in-sublime-text-free-course/

| Commands: | |
| ------------- | -----:|
| CMD + P | Search File |
| CMD + I| Search Inline |
| CMD + D| Select this element / Multicursor |
| CMD + CTRL + G| Select all elements at once |
| CMD + SHIFT + P| Command Line |
| CMD + P + FILENAME + @ + METHOD OR CSS CLASS NAMER | Jump to method or class name in this file |