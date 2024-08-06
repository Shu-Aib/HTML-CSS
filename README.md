# HTML-CSS

<h1><strong>NOTES</strong></h1> _____ [main title. <code>&lt;strong&gt;</code> is an element that represents strong importance/urgency]
<h2><em>2nd level headline</em></h2> _____ [Subtitle usually smaller and maybe longer.<code>&lt;em&gt;</code> adds emphasis]
<h3><i>3rd level headline</i></h3> _____ [smaller kicker headlines and labels.<code>&lt;i&gt;</code> applies visual italics]
<h4><b>4th level headline</b></h4> _____ [the <code>&lt;b&gt;</code> is more generic/neutral]
<p>this is a paragraph</p>
HTML Lists
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

{dt} tag, stands for definition term
{dd} tag, stands for definition description
{dl} tag, represents definition lists
The tags are simply placed side by side simply because thats how a definition list is structured
In summary, we now have three types of lists in HTML: unordered lists, ordered lists, and definition lists.

<h2>HTML QUOTES</h2>
To attribute a quote we use <code>&lt;<em>cite</em>&gt;</code>
To distinguish a quote from the surrounding text we use <code>&lt<i>blockquote</i>&gt;</code>

-    <H3>Example</H3>

<blockquote>
  <p>We've gone from having 21 elements in HTML tags, that first document,
    to having 100 more elemens now, and yet its still the same language. i find it amazing.
    It's still the same language that was created 25 years ago. It has grown an extra 100 elementsin there,
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

-    <h4>Example</h4>

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
<small>©'2019 Fancy Company</small>
