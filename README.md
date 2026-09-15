# Markdown Syntax and Equivalent HTML Syntax


## HEADINGS
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

<h1>Header 1</h1>
<h2>Header 2</h2>
<h3>Header 3</h3>
<h4>Header 4</h4>
<h5>Header 5</h5>
<h6>Header 6</h6>
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

<h1>Header 1</h1>
<h2>Header 2</h2>
<h3>Header 3</h3>
<h4>Header 4</h4>
<h5>Header 5</h5>
<h6>Header 6</h6>


## TEXT EMPHASIS
```
**This is bold text**  
__This is bold text__ 
<strong>This is bold text</strong> 
*This is italic text*   
_This is italic text_  
<em>This is italic text</em>  
***Bold and Italic***   
___Bold and Italic___  
<strong><em> Bold and Italic </em></strong>  
~~Scratch this~~  
<del>Scratch this</del>  
```
**This is bold text**  
__This is bold text__  
<strong>This is bold text</strong>  
*This is italic text*  
_This is italic text_  
<em>This is italic text</em>  
***Bold and Italic***   
___Bold and Italic___  
<strong><em> Bold and Italic </em></strong>  
~~Scratch this~~  
<del>Scratch this</del>  

## PARAGRAPHS
```
<p>Hello World!</p>
<p>We are learning Markdown.</p>
Some text <br>
Some more text
```

## BLOCKQUOTES
```
> This is a blockquote
<blockquote>This is a blockquote</blockquote>
> some text
>> and then some more text
>>> and then some more

<blockquote>
<p>some text</p>
<blockquote>
<p>and then some more text</p>
<blockquote>
<p>and then some more</p>
</blockquote>
</blockquote>
</blockquote>
```
> This is a blockquote
<blockquote>This is a blockquote</blockquote>

> some text
>> and then some more text
>>> and then some more

<blockquote>
<p>some text</p>
<blockquote>
<p>and then some more text</p>
<blockquote>
<p>and then some more</p>
</blockquote>
</blockquote>
</blockquote>

## HORIZONTAL LINE
````
---
___
***
<hr>
````
---
___
***
<hr>

## ORDERED LIST
```
1. Cheese
2. Carrot
3. Coconut
<ol>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
</ol>
```
1. Cheese
2. Carrot
3. Coconut
<ol>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
</ol>

## UNORDERED LIST
```
- Cheese
- Carrot
- Coconut

*  Red
*  Green
*  Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

<ul>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
 </ul>
```
- Cheese
- Carrot
- Coconut

*  Red
*  Green
*  Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

<ul>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
 </ul>

## GRAPHICS
 ```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Python Logo")
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" title="Python Logo"/>
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Python Logo")
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" title="Python Logo"/>

## LINKS
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com)

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>

https://en.wikipedia.org
<a href="https://en.wikipedia.org">https://en.wikipedia.org</a>
[click me](https://en.wikipedia.org)
<a href="https://en.wikipedia.org">click me</a>
[click me](https://en.wikipedia.org "Wikipedia")
<a href="https://en.wikipedia.org" title=”Wikipedia”>click me</a>
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com)

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>

https://en.wikipedia.org  
<a href="https://en.wikipedia.org">https://en.wikipedia.org</a>  
[click me](https://en.wikipedia.org)  
<a href="https://en.wikipedia.org">click me</a>  
[click me](https://en.wikipedia.org "Wikipedia")  
<a href="https://en.wikipedia.org" title=”Wikipedia”>click me</a>  

## TASK LISTS
```
- [x] Some task
- [ ] Some more task
```
- [x] Some task  
- [ ] Some more task  


## TEXT COLOR
```
<span style="color:blue">Text</span>
<span style="color:red">Text</span>
<span style="color:green">Text</span>
<span style="color:pink">Text</span>
<span style="color:yellow">Text</span>
```
<span style="color:blue">Text</span>
<span style="color:red">Text</span>
<span style="color:green">Text</span>
<span style="color:pink">Text</span>
<span style="color:yellow">Text</span>

## TEXT FONT FAMILY
```
<span style="font-family:Comic Sans MS">This is a text</span>
```
<span style="font-family:Comic Sans MS">This is a text</span>

## COLORED NOTE BOXES
```
<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes.</div>

<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not inside code cells, or use for mathematical formulas if needed. Typically also used to display warning messages.
</div>

<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>

<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>
```
<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes.</div>

<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not inside code cells, or use for mathematical formulas if needed. Typically also used to display warning messages.
</div>

<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>

<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>

## CELL BACKGROUND COLOR
```
<code style="background:yellow;color:black">Useful for highlighting to grab the attention of the reader towards certain points.</code>
<p style="background:black">
<code style="background:black;color:white">C:\Users\YOUR_USERNAME> pip3 install roughviz
</code>
</p>
```
<code style="background:yellow;color:black">Useful for highlighting to grab the attention of the reader towards certain points.</code>
<p style="background:black">
<code style="background:black;color:white">C:\Users\YOUR_USERNAME> pip3 install roughviz
</code>
</p>

## HTML MARK TAG
```
Do not forget to buy <mark>milk</mark> today.
```
Do not forget to buy <mark>milk</mark> today.



<hr>
https://medium.com/analytics-vidhya/the-ultimate-markdown-guide-for-jupyter-notebook-d5e5abf728fd  
<hr>
https://daringfireball.net/projects/markdown/syntax  
<hr>
https://www.markdownguide.org/basic-syntax/  