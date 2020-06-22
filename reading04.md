# building websites 
## Getting started

##### important things to consider when building a site 

* The website's target audience : - age - gender -region  - individual or company 
* The reason of visit : design content according to the motivation and goals of the visitors
* what do they want to achieve 
* what info they need : on the product or the organization 
* how often do they visit 

##### what information needed in order to achieve the audience goals quickly and effectively.

* do you need to introduce yourself?
* do they need background information on your product?
* What are the features of what you are offering?
* What is special about what you offer?
* are there common questions people ask about?


## design 

After figuring out the content the **first** step is to create a site map of how the pages connectd and grouped together to make navigation easier and more effective.
when designing site navigation make sure the design is:
 * concise 
 * clear 
 * selective
 * in context 
 * interactive
 * consistent

**second** step is to create a wireframe of how the site will look like, nothing fancy just a simple sketch.
**lastly** combine the content and the design using HTML to create the final pages layout.


HTML5 layout elements

How old browsers understand new elements
```
header, section, footer, aside, nav, article, figure
{
display: block;}
```
```
<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/
trunk/html5.js"></script>
<![endif]-->
```
js^

Styling HTML5 layout elements with CSS

ndicate the purpose of
different parts of a web page and help to describe
its structure.
XX The new elements provide clearer code (compared
with using multiple <div> elements).
XX Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
XX To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.

new elements (article section header footer fgcaption figure hgroup aside nav)




DOCTYPES tell browsers which version of HTML you
are using.
XX You can add comments to your code between the
<!-- and --> markers.
XX The id and class attributes allow you to identify
particular elements.
XX The <div> and <span> elements allow you to group
block-level and inline elements together.
XX <iframes> cut windows into your web pages through
which other pages can be displayed.
XX The <meta> tag allows you to supply all kinds of
information about your web page.
XX Escape characters are used to include special
characters in your pages such as <, >, and ©.