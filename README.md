# HTML-CSS

<h1><strong>NOTES</strong></h1>

<h1>HTML  (Hyper text Markup Language) elements are the building blocks of web pages.</h1><br>

<h2>Structural quotes</h2><br>
<Code>&lt;html&gt;</code> - Root element<br>
<code>&lt;head&gt;</code> - Contains metadata about the document<br>
<code>&lt;title&gt;</code> - Sets the title of the page<br>
<code>&lt;body&gt;</code> - Contains the content of the page<br>

<h2>Headings</h2><br>
<code>&lt;h1&gt;</code> - Main heading<br>
<code>&lt;h2&gt;</code> - Subheading<br>
<code>&lt;h3&gt;</code> - Sub-Subheading<br>
<code>&lt;h4&gt;</code> - <code>&lt;h5&gt;</code> - <code>&lt;h6&gt;</code> - Additional Subheadings<br> 

<h2>Text Elements</h2><br>
<code>&lt;p&gt;</code> - Paragraph<br>
<code>&lt;span&gt;</code> - Inline Text Container<br>
<code>&lt;div&gt;</code> - Block Level Container<br>
<code>&lt;strong&gt;</code> - Bold Text<br>
<code>&lt;em&gt;</code> - Emphasized Text<br>
<code>&lt;u&gt;</code> - Underline Text<br>

<h2>Links</h2><br>
<code>&lt;a&gt;</code> - Hyperlink<br>

<h2>Images</h2><br>
<code>&lt;img&gt;</code> - Image Element<br>

<h2>Lists</h2><br>
<code>&lt;ul&gt;</code> - Unordered Lists<br>
<code>&lt;ol&gt;</code> - Ordered Lists<br>
<code>&lt;li&gt;</code> - List Item<br>

<h2>Tables</h2><br>
<code>&lt;table&gt;</code> - Table Element<br>
<code>&lt;tr&gt;</code> - Table Row<br>
<code>&lt;td&gt;</code> - Table Data Cell<br>
<code>&lt;th&gt;</code> - Table Header Cell<br>

<h2>Forms</h2><br>
<code>&lt;forms&gt;</code> - Form Element<br>
<code>&lt;input&gt;</code> - Input Field<br>
<code>&lt;textarea&gt;</code> - Text Area<br>
<code>&lt;select&gt;</code> - Dropdown Menu<br>
<code>&lt;button&gt;</code> - Button<br>

<h2>Multimedia</h2><br>
<code>&lt;video&gt;</code> - Video Element<br>
<code>&lt;audio&gt;</code> - Audio Element<br>

<h2>Semantic Elements</h2><br>
<code>&lt;header&gt;</code> - Header Section<br>
<code>&lt;nav&gt;</code> - Navigation Section<br>
<code>&lt;main&gt;</code> - Main Content Section<br>
<code>&lt;section&gt;</code> - Sectioning Element<br>
<code>&lt;article&gt;</code> - Article Element<br>
<code>&lt;aside&gt;</code> - Sidebar Element<br>
<code>&lt;footer&gt;</code> - Footer Section<br>

<h2><i>These are just some of the many HTML elements available. Each
element has its own Attributes and usage guidelines</i></h2><br>

<h2><i>HTML Elements and tags are often used interchangeably, but theres a subtle difference</i></h2><br>
<pre>
<h2>Html Elements</h2>
‣ Represents a structure or a component on a webpage.<br>
‣ Consists of a start tag, content, and an end tag.<br>
‣ Define the meaning and purpose of the content.<br>
‣ Can have attributes, child elements, and text content.<br>
‣ Examples:<br>
-    -<code>&lt;p&gt;</code><br>
-    -<code>&lt;img&gt;</code><br>
-    -<code>&lt;ul&gt;</code><br>
-    -<code>&lt;table&gt</code><br>
</pre>

<h2>HTML Tags</h2>
<pre>
‣ The actual markup used to define an element.<br>
‣ Consists of angle brackets(<code>&lt;</code> and <code>&gt;</code>) surrounding the element name.<br>
‣ Come in pairs:<br>
-    -Opening tag (<code>&lt;tag&gt;</code>) and closing tag (<code>&lt;/tag&gt;</code>)<br>
‣ Surround the content and apply the element's meaning.<br>
Examples:<br>
-    -<code>&lt;p&gt;</code><br>
-    -<code>&lt;/p&gt;</code><br>
-    -<code>&lt;img src="image.jpg"&gt;</code><br>
</pre>

<h2>Key Differences</h2>
‣ Elements represents the structure, while tags are the markup.<br>
‣ Elements have content, attributes, and child elements, while tags surround the content.<br>
‣ Elements define meaning while tags apply that meaning.<br>

<h2>To Illustrate</h2>
‣ <code>&lt;p&gt;this is a paragraph&lt;/p&gt;</code>.<br>
‣ <code>&lt;p&gt; and &lt;/p&gt;</code> are the tags.<br>
‣ <code>&lt;p&gt;</code> is the element (representing a paragraph).<br>
‣ "This is a paragraph" is the content.<br>

<h2>In Summary</h2>
‣ HTML elements define  the structure and meaning.<br>
‣ HTML tags are the markup used to apply that meaning.<br>

While the terms are often used interchangeably, understanding the distinction helps
clarify the role of each in building web pages.<br>


<h1>Basic Syntax</h1>
css is made up of <i><strong>selectors</strong></i> and <i><strong>declarations</strong></i>.<br>
Heres an example:
<pre>
p {                            
    color: red;                
    font-size: 20px;           
}                              
</pre>

‣ <strong>Selector</strong>: p (This targets all <code>&lt;p&gt; elements) <br>
‣ <strong>Declarations</strong>: inside the curly braces {}, you have properties and values.<br>
<pre>    
    ‣ color: red; (This sets the text color to red) <br>
    ‣ font-size: 20px; (This sets the font size to 20 pixels) <br> 
</pre>

<h1>Common Selectors</h1>
‣ <strong>Element Selector:</strong> Targets all elements of a specific type.<br>
<pre>
h1 {
    color: blue;
}
</pre>

‣ <strong>Class Selector:</strong> Targets elements with a specific class attribute.<br>
<pre>
.myClass {
    background-color: yellow;
}
</pre>

‣ <strong>ID Selector:</strong> Targets a single element with a specific ID attribute.<br>
<pre>
#myId {
    border: 1px solid black;
}
</pre>

<h1>Applying CSS</h1>
You can apply CSS in 3 ways:
‣ <strong>Inline CSS:</strong> Directly in the HTML Element. <br>
<pre>
<code>&lt;p style="color: red;"&gt;This is a red paragraph.&lt;/p&gt;
</pre>

‣ <strong>Internal CSS:</strong> Inside a <code>&lt;style&gt;</code> tag in the HTML <code>&lt;head&gt;</code>.<br>
<pre>
<code>&lt;head&gt;
    &lt;style&gt;
        p {
            color: red;
        }
    &lt;/style&gt;
&lt;/head&gt;</code>
</pre>

‣ <strong>External CSS:<strong> In a seperate .css file linked to HTML<br>
<pre>
<code>&lt;head&gt;                                                                
    &lt;link rel="stylesheet" type="text/css" href="styles.css"&gt;         
&lt;/head&gt;                                                               
</pre>

<h2>EXAMPLE</h2>
Here’s a simple example that combines these concepts:
<pre>
<code>&lt;!DOCTYPE html&gt;
&lt;html7&gt;
&lt;head&gt;
    &lt;link rel="stylesheet" type="text/css" href="styles.css"&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1 class="header"&gt;Hello, World!&lt;/h1&gt;
    &lt;p id="intro"&gt;Welcome to CSS basics.&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre></code>

And the styles.css file:
<pre>
.header {
    color: blue;
    text-align: center;
}

#intro {
    color: green;
    font-size: 18px;
}
</pre>

This example sets the color of the header to blue and centers it, <br>
while the paragraph with the *ID intro* is styled with green text and a font size of 18px.<br>












<h2>HTML Lists</h2>
<ul>
    <li>flour</li> _____ [an <code>&lt;li&gt;</code> is an element, which represents a list of items]
    <li>suger</li>
    <li>baking powder</li>
    <li>salt</li>
</ul>

[after using <code>&lt;ul&gt;</code> for the list  of items we use <code>&lt;ol&gt;</code>(ordered list) to keep the items in a specific order]

<ol>
    <li>in a bowl, mix all the dry ingredients</li>
    <li>in another bowl, mix the rest</li>
</ol>

<code>&lt;dt&gt;</code> tag, stands for definition term<br>
<code>&lt;dd&gt;</code> tag, stands for definition description<br>
<code>&lt;dl&gt;</code> tag, represents definition lists<br>
The tags are simply placed side by side simply because thats how a definition list is structured
In summary, we now have three types of lists in HTML: unordered lists, ordered lists, and definition lists.<br>
                  
<h2>HTML QUOTES</h2>
To attribute a quote we use <code>&lt;<em>cite</em>&gt;</code>
To distinguish a quote from the surrounding text we use <code>&lt<i>blockquote</i>&gt;</code>
HTML Links: Links are created using the A element with an href attribute that specifies the URL.
Absolute URLs: These include the full URL, starting with HTTP or HTTPS, which stands for Hypertext Transport Protocol and Hypertext Transport Protocol Secure, respectively1.
Linking Elements: Links can be wrapped around text, images, or more complex elements like teaser cards2.
Security: Modern browsers automatically add HTTPS for security, but developers need to include it in their code.

-    <H3>Example</H3>

<blockquote>
  <p>We've gone from having 21 elements in HTML tags, that first document,
    to having 100 more elements now, and yet its still the same language. i find it amazing.
    It's still the same language that was created 25 years ago. It has grown an extra 100 elements in there,
    and yet it's still the same language.</p>
    
 <p>if you're familiar at all with computer formats, this is very surprising.
    if you tried to open a Word processing document from the same time when 
    Tim Berners-Lee was creating the World Wide Web project, good luck.
    You'd probably have to run some emulation just to get the thing open.
    And yet you could open an HTML document from back then in browser today.</p>
<cite>Jeremy Keith</cite>
</blockquote>

We can include any element we want within the blockquote. The important thing is that
elements should be nested within each other in a way that makes sense. 

-    <h3>Example</h3>

<p>Jeremy Keith said <q> You could open an HTML document from back then in a browser today</q></p> 
<p lang="Fr">Keith said <q> You could open an HTML document from back then in a browser today</q></p> 

<h4>Using <code>&lt;br&gt;</code> element</h4>

-    <h5>example</h5>

<b>
They
say you took my manhood,
momma
Come sit on my lap
and tell me,
what do you want me to say
to them, just 
before I annihalate
their ignorance?
</b>

-    <h4>using <code>&lt;br&gt;</code></h4>

They<br>
say you took my manhood,<br>
momma<br>
Come sit on my lap<br>
and tell me,<br>
what do you want me to say<br>
to them, just <br>
before I annihalate<br>
their ignorance?<br>

<h4>Using <code>&lt;pre&gt;</code> element</h4>

-    <h5>example of <code>&lt;pre&gt;</code> element</h5>
<h1>[in Just-]</h1>
<p>by e.e.cummings</p>
<pre>
it's
spring
and
   the
      goat-foot
balloonMan     whistles
far
and
wee
</pre>

Using <code>&lt;pre&gt;</code> allows spacing to be an integral part of the contents meaning

Using <code>&lt;pre&gt;</code> and <code>&lt;code&gt;</code> together
<pre>
<code>
&lt;ul&gt;
    &lt;li&gt;flour&lt;li&gt;
    &lt;li&gt;sugar&lt;li&gt;
    &lt;li&gt;salt&lt;li&gt;
&lt;/ul&gt;


ul  {
    colour: teal;
}
li {
    list-style-typ: square;
}
</code> 
</pre>

<h2>HTML Superscripts,Subscripts and Small Text</h2>

Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest.Subscripts are characters that are set below the normal baseline for text
<h4>Example</h4>
<p>H<sub>2</sub>O</p>
<p>Something that has a footnote.<sup>2</sup></p>
<small>© 2019 Fancy Company</small><br>

<p>Subscript<sub>2</sub><br>
   Superscript<sup>2</sup><br>
   <small>small text</small><br>
</p>
<style>
    .intro{
        color:blue;
    }
</style>
<h1>HTML Attributes</h1>
<h2>class attribute</h2>
<p class="intro">-This is the introduction</p>

<h2>ID Attribute</h2>
<p class="intro" id="article intro">-This is the introduction</p></code>

<h1>Aria roles</h1>

<!DOCTYPE html>
<html>
    <head>
    <style>
    </head>
    <body>
    <h1 aria-label="Hello World"><br>
        <div class="grid" aria-hidden="true">
        <span>H</span>
        <span>E</span>
        <span>L</span>
        <span>L</span>
        <span>O</span>        
        <span>W</span>
        <span>O</span>
        <span>R</span>
        <span>L</span>
        <span>D</span>
    </div>
</h1>

<h1 aria-label="Hello World">
<div class="grid" aria=hidden"true>"
</body>
</html>
    
HTML Links: Links are created using the A element with an href attribute that specifies the URL.
Absolute URLs: These include the full URL, starting with HTTP or HTTPS, which stands for Hypertext Transport Protocol and Hypertext Transport Protocol Secure, respectively1.
Linking Elements: Links can be wrapped around text, images, or more complex elements like teaser cards2.
Security: Modern browsers automatically add HTTPS for security, but developers need to include it in their code.
Relative URLs: Useful for linking within the same site, allowing flexibility when moving between servers.
Absolute URLs: Include the full domain name, useful for linking to external sites.
File Structure: Understanding how files are organized is crucial for creating effective URLs.
Clean URLs: Using folders and index.html files can create user-friendly and well-structured URLs1.
logical URL paths.
Leverage Index Files: Use index.html files in folders to create clean URLs (e.g., /people instead of /people.html)2.
Avoid Absolute URLs: Absolute URLs can cause issues when moving the site between different servers.

the SRC tells the browser which image to use
the Alt attribute provides a text description of the image
Width and Height determines the size of the image
<!doctype html>

<html>
<head>
<style>
*--------------*
html{
Font-Family: Lora, Geogia, Seriff
Margin:2em
Font-size:!70%
Line-Height:1.5;
}
    
<img src="https//s3-us-west-2.amazonaws.com/s.cdpn.io/10558/maggie.jpg"
<alt="shiny black dog looking pensive" width="400" height="300"
</style>
</head>
<body>

<h2>Adding an image</h2>
<img src="img.jpg" alt="brown dog" width="400" height="300"

</body>
<html></html>

<header><h3><i>WORKING WITH FORMS</i></h3></header>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>    
    form input{width:30%}
    </style>
</head>

<body>
    <section class='version-A'>
        <h2>Version A</h2>
        <form>
            <label>Name</label>
            <input>
            <label>Email</label>
            <input>
            <button>Sign Up</button>
        </form>
    <section class='Version B'>
        <h2>Version B</h2>
        <form action='success html' method='get'>
            <label>Name</label>
            <input>
            <label>Email</label>
            <input>
            <button>Sign Up</button>
        </form>
    </section>
    <section class='Version C'>
        <h2>Version C</h2>
        <form action="success html" method="get">
            <label>Name</label>
            <input name="Name">
            <label>Email</label>
            <input name="Email">
            <button>Sign Up</button>
        </form>
    </section>
    <section class="version D">
        <h2>Version D</h2>
        <form action="success html" method="get">
            <label for="name">Name</label>
            <input name="name" id="name">
            <label for="email">Email</label>
            <input name="Email" id="email">
            <button>Sign Up</button>
        </form>
    </section>


</body>

</html>
![image](https://github.com/user-attachments/assets/0d3c2d35-0b8c-4bc9-9878-2776ed7a45ea)

