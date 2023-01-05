(1)What is HTML?

--> HTML stands for Hyper Text Markup Language
--> HTML is the standard markup language for creating Web pages
--> HTML describes the structure of a Web page
--> HTML consists of a series of elements
--> HTML elements tell the browser how to display the content
--> HTML elements label pieces of content such as "this is a heading", "this is a   paragraph", "this is a link", etc.
--> HTML is a markup language because it defines the structure nd layout of the content...nd it marks the information by tagging them...
Example:-
<p>hello</p>  --> hello word marked by the paragraph tag..

HTML boilerplate code:--
 
<!DOCTYPE html>   <!----It shows u are using the HTML 5 document--->
<html lang="en">  ---> Root element of the HTML page 
<head>  ----> It contains meta Information of the html page 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day1</title>  --->  It shows title of webpage 
</head>   -----> Closing of head tag 
<body>  ----->  It is a container for all the visible contents
 <h1>My first page </h1> ----> Heading Tag 
    <h2>Hey there I am Learning!</h2>   -----> Heading tag 2 and there are 6 heading tags but least priorities by the heading number like h1 has higher priority as compare to h2 having least priority.. 
    <p> My name is Lucky nd I am learning HTML</p> ----> It shows content in the paragraph format.. 
</body>  
</html> --------> Root element closing tag

HTML Element :- An Html element is everything from start tag to the end tag.
Html Tags :- Html tags are used to design the structure of websites..

HTML is NOT case sensitive Language:-
<p> = <P>
<html> = <HTML>
<head> = <HEAD>

HTML Attributes:-
Attributes are used to provide additional information to the HTML elements.
<html lang="en">

HEADING TAG :-
Used to display headings in HTML
h1 (most important)
h3
h2
h4
h5
h6 (least important)

Some HTML element having no Content nd no closing tag like <br> tag <br> tag is a line break tag...
there are many tags having no content nd no closing tag like <hr> tag <hr> tag is used to create a horizontal row in our webpage...

HTML LINKS:-
Anchor Tag is used to create links on our webpage 
<a href="https://www.google.com">Google</a>

Line Breaking Tag:-
<br>
Horizontal ruler used for separating Content :-
<hr>
 ---- noshade create a border.
<hr noshade="2">
Bold Tag:-
<b>
Italic Tag:-
<i>
Undereline Tag:-
<u>

Big & Small Tags
Used to display big & small text on your page
<big> Big </big>
<small> Small </small>

Font Tag:-
<font color="red"></font>
it is used to change the colour of the text..

Image Tag:-
It is used to display image on your Websites..
<img src="Your URL of the image"alt="Random Image"width="50"
height="100">

alt is used to give the description of the image which type of image is when the error is coming or the image is not loading properly...
width and height is used to change the size of an image in pexels..

The style Attribute:-

The style attribute is used to add styles to an element, such as color, font, size, and we can also change the background color of the heading and paragraph.
Example:-
<p style="color:red;">This is a red paragraph.</p>
<h1 style="font-size:60px;">This is a sample heading..</h2>
<h1 style="background-color:blue;">It is use to Change the Backgroung of the text...</h1>

<pre> Tag:-
The conttent in the pre tag print as it is without changing any space and any of these it just print the text as it is..
<pre>content</pre>




