#Exercise

Notably, make the following changes:

1. Change the .favorites selector so that it only applies color: red to the unordered list (ul) of favorites.

2. Set the color of the favorite food to be the color green.

3. Change the div with the class favorites to have a background-color of yellow. (background-color is the property name.)

```
body {
  padding: 2% 5%;
  color: #555;
}
/* Write your CSS Styles below: */
.favorites {
  background-color: yellow;
  color: red;
}
.food {
  color: green;
}
.sport{
  color: pink;
}
```

#Exercise 

Determine the color of the p element using the information below:
The p element is located on line 30.
An HTML document has three external stylesheets attached, and a style tag defined within the body.

Two of the external stylesheets are located at line 8 and 9, within the head tag.
The final external stylesheet is located at line 64, before the end of the body tag (line 65 is “</body>“)
The style tag is defined on line 24, with its closing tag on line 29.
The stylesheet on line 8 has the ruleset: p {color: green;}.
The stylesheet on line 9 has the ruleset: p {color: yellow;}.
The stylesheet on line 64 has the ruleset: p {color: cyan;}.
The style tag on line 24 has the ruleset: p {color: orange;}.

Use the rules of how styles are applied to determine the color that the p element will have.

---

The Color of the \<p> tag is orange, though the external style sheet on line 64 would take preference over the thers due to it loading last - I believe CSS rules within HTML in a style tag take preference over all other external rulesets. 

---

#Exercises

Use your newfound knowledge of combinators for the following exercises. Do the exercises in this codepen.

In a new ruleset, use a combinator to color all .b‘s that are siblings of .a‘s.
Use a selector with a combinator to color all siblings of .c orange.
Use a selector with a combinator to color all immediate descendants of .animals green.


```
ul.some-letters .a + .b {
  color: cyan;
}
.c ~ li {
  color: orange;
}
.animals > li{
  color: green;
}
```

#Exercises

1. Write a CSS class that will italicize, uppercase, and strike-through its text.

```
.css-class{
	font-style: italic;
	text-transform: capitalize;
	text-decoration: line-through;
}
```

2. Navigate to Google’s Library of web fonts: www.google.com/fonts; then, choose a font you find pleasing. Write the CSS class named myfont that changes the font family to your chosen font, falling back to the fonts Lora and Times New Roman, and finally falling back one more time to a generic font family of your choosing.

```
.myfont{
	font-family: Lobster, Lora, Times New 		Roman, Arial;
	
}
```

3. Spend time experimenting with the CSS line-height property and create three classes, each corresponding to significantly different line-heights. Which line-height do you find easiest to read?

```
lineheight-1{
font-style: italic;
text-transform: capitalize;
text-decoration: line-through;
line-height: 3em;
}
lineheight-2{
font-style: normal;
text-transform: uppercase;
text-decoration: over-line;
line-height: 2em;
}
lineheight-3{
font-style: oblique;
text-transform: lowercase;
text-decoration: underline;
line-height: 1.5em;
}
```

#Exercises

1. Calculate the result in pixels: What is 80% of 16px?

12.8px


2. Calculate the result in em: What is 2em of 1.6em

51.2px


3. Determine the child‘s font size in the below sample:

```
html {
  font-size: 10px;
}
parent {
  font-size: 2em;
}
.parent .child {
  font-size: 1.6rem;
}
```
16px

#Exercises

1. Create a web page that resembles a newspaper, with a heading area, three columns, and a footing area. Each column needs an <h3> tags and at least 5 <p> tags. You will need to utilize floats, percentage widths, and clears to succeed.

```
<p data-height="265" data-theme-id="0" data-slug-hash="ZOjrAz" data-default-tab="html,result" data-user="nikpod" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/nikpod/pen/ZOjrAz/">Three forms of travel</a> by Nik (<a href="http://codepen.io/nikpod">@nikpod</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
```

2. After creating the newspaper layout in the exercise above, write a simplified write-up of how floats function as if you were writing it for a child. Try to find an analogy or example from the physical world, but also try to adhere to accuracy. Add your simplified write-up to the center column of your newspaper layout. The write-up should be between 3 and 5 paragraphs.

What is a float?

Well, imagine that balloon your holding filled with helium.

It floats, depending on the wind it will float left or right.

Now say we can tell the wind which way to blow.

And we have a glass window that you can't see but can be used to hold the balloon in a location stopping the ballon from moving further to the left or right (depending on the breeze).

---

#Exercises

1. Create a web page containing 6 elements: 2 of each document flow context–normal, floating, and positioning. Write inside of each element which property, or lack thereof, is determining the element’s context.

<p data-height="265" data-theme-id="0" data-slug-hash="QEBRbX" data-default-tab="html,result" data-user="nikpod" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/nikpod/pen/QEBRbX/">QEBRbX</a> by Nik (<a href="http://codepen.io/nikpod">@nikpod</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

2. Create a web page that includes three elements with the classes .a, .b, .c. Fill each with unique text, like the names of your favorite foods. Then, set each to have a unique background-color as well. Float all three to the left, and set their width to be 50%. Then, change .b to be in the positioning context. Observe and document the changes to .b. Based on the information you were taught in this chapter, can you explain what is happening?

In the example below, each of the elements, the h1,h2 and unordered list have the classes of a, b & c. As each is floating to the left, they are pushcing up and against each other in a row. Until the limit of the space available at which point the element has a line break. 


<p data-height="265" data-theme-id="0" data-slug-hash="vKzBAQ" data-default-tab="html,result" data-user="nikpod" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/nikpod/pen/vKzBAQ/">vKzBAQ</a> by Nik (<a href="http://codepen.io/nikpod">@nikpod</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>



---

#PROJECTS:

Project Assignment 1: Multi-Page Web Site
Project Assignment 1 will be the glue that binds together all other project assignments for this chapter.4

You will create a website consisting of multiple web pages. We list this project assignment first because it brings together all of the other assignments in this chapter, but you may want to work on it last, when you have completed the other components. Below are the guidelines for creating the web pages:


A Homepage that contains:
A menu with links to every other page
A large background image behind a large heading containing your name, your career path, and a quote that you find inspiring.
A page each that showcases Project Assignment 2, 3, 4, 5 and 6. Each page should also contain a link back to the homepage.
A page that links to each form you will create for project assignment 4

---


