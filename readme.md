HTML:
Html stands for hypertext markup language.
we use html for creating stucture of the website.
we called html as a markup language because it contains skeleton stucture of web page.
All html are writte in tag line.
H1 TAG:
h-heading is range h1 to h6.
PARAGRAPH TAG:
For writing paragraph.
BREAK LINE:
break the line.
HORIZENTAL LINE:
hr tag used for this.
IMAGE tag:
height
width
alt
src
these are attribute of image tag.
Anchor tag:
href=hyper reference (reference to the another page /element);
TARGET Attribute:
-self=open in same page;
-blank=open in another page;
HTML FORMATING:
-bold text<b>
-italic<I>
-emphasized text<em>
-inserted text<ins>
-deletion text<del>
-subscripted text<sub>
-superscripted text<sup>
-marked text<mark>
example of Super script:
<p>a<sup>2</sup><p>
Example of subscript:
<p>a<sub>2</sub><p>
HTML TABLE:
html table gives us a table like stucture where we can insert our data in row and column format.
<table></table>-main tag
<tr>-table row
<th>-table heading
<td>-table column
HTML LIST:
list are two types
unorder list<ol>
order list<ul>
HTML Blocklevel element:
HTml contain 2 types of block level element to specify the stucture of a web page
1.<p>
2><div>
HTML FORMS:
Html forms provide a Form stucture so that we can give our data bu use of ther forms.
Types Of INPUT:
input type=text;
input type=password;
input type=submit
input type=checkbox
input type=radio-button
input type=time
input type=color
input type=date
input type=url
input type=search
input type=week
input type=email
input type=image 
input type=month
input type=range
input type=file
input type=tel
input type=number
input type=hide
CSS START HERE:
-css stands for cascading Style Sheet.
-css used for designing and styling the web pages.
Syntax:
h1-selector
{
   (property) color:red(Value);
}
Basically CSS are 3types:
1.inline CSS
2.internal Css
3.External CSS
INLINE CSS:
<body>
<h1 style="color:red">Today is Thursday</h1>
</body>
INTERNAL CSS:
<html>
<head>
<style>h1{color:red;}</style>
</head>
<body>
<h1>my name Sujit</h1>
</body>
</html>
EXTERNAL CSS:
<html>
<head>
<link href="a.css" rel="stylesheet">
</head>
<body>
<h1>my name is sujit</h1>
</body>
</html>
a.css:
h1{color:red;}
CSS Selector:
1.ID Selector
2.class Selector
3.Universal Selector
4.group Selector
5.element Selector
ID SELECTOR:
id selector are those selector which unique design/we select only one element in html file.
it is denoted by"#";
ex:
<html>
<head>
<style> #name{color:red;}</style>
</head>
<body>
<p id="name">My name is Sujit Kumar Pradhan</p>
</body>
</html>
CLASS SELECTOR:
we use to class selector for repeating the similar design in multiple times.
"."property used to specify the class selector in our css file.
<html>
<head>
<style>
.name{color:red;}
</style>
</head>
<body>
<p class="name">My name is Sujit</p>
</body>
</html>
UNIVERSAL SELECTOR:
we use universal selector to design whole page in a single design
"*" property we used to specify the University selector in our css file.

<HTML>
<head>
<style>*{color:green;}</style>
</head>
<body>
<p>Sujit</p>
<h1>Gudu</h1>
</body>
</HTML>
GROUP SELECTOR:
we used group selector to create one  design in which we have selected the tags.
<html>
<head>
<style>
    p,h1{color:red}
    </style>
</head>
<body>
<p>my name</p>
<h1>sujit</h1>
</body>
</html>
ELEMENT SELECTOR:
by selecting one single single element we have to design is called the element selector
<html>
<head>
<style>
    p{color:red;}
</style>
</head>
</html>
CREATE A simple div with an id box .add some text content inside the div.set its background color blue.
create 3 heading with h1,h2,h3 give them alla class "heading and set of color heading to red.


























