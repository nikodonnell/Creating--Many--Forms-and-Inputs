#Questions

1: *The `input` element has an attribute called "type." Discuss the purpose and function of this attribute, and list some of the values 'type' can be.*

The purpose of the input element is to give recognition to an input field which acts to give context to that input field. 

An example of using the input element is the date type.

```
<input type="date" name="appointment">
<input type="time" name="time">
```
This creates an easy way to integrate time and date selection – without building one from scratch. Allowing a developer to focus their efforts on design, customization and functionality.

---

2: *Fully explain what a CSS selector is and list and explain the different types of CSS selectors.*

CSS selectors are used to target html elements for style and design. 

They include:

Standard elements like heading <h1,h2,h3>, paragraphs <p>, body, footer etc.

ID

\#idname

Class
.classname

Each different type of element has its corresponding CSS selector – for ID's the hashtag (#) is used, for Class's its the dot (.) and for standard HTML tag elements the name of that element can be given. 

CSS selectors can also be combined to give style to multiple elements for example:

```
.classname, #idname, h2{
color: blue;
font-size:16px;
}
```
Allows us to style the specified class, id and h2 (heading 2) elements all at once – Neat right!

---

3: *Describe what a "next-sibling selector" is. Explain how it works and give an example of its usage.*

As we've discussed in previous sections, the DOM document object model follows a hierarchy using parent and child elements. A parent element will often have multiple child elements. The relationship between these child elements is referred to as the element's siblings. 

Using CSS we can target an element's siblings and more specifically it's next adjacent sibling using the 'next-sibling' selector. 

For example if we wish to color the second list item (<li>) in a list, we can do so my adding the following CSS rule.

```
li:first-of-type + li{
color: blue;
}
```
---

4: *Describe what color opacity is and explain how to specify it using color declarations.*

Opacity is not a color perse, but rather a value given between 0.0 (fully transparent) and 1.0 (fully opaque or not transparent). 

A newer technique for declaring opacity using CSS is with RGBA. The RGB still stands for the primary colors of Red, Green & Blue respectively. The addition is the A character which nominates the alpha channel and gives this value between 0.0 and 1.0 to activate the level of transparency or opacity desired for styling. 

```
body{
background-color: rgba(255, 0, 0, 0.3);
}
```

5: *Explain in detail what the CSS Box Model is.*

The CSS box model describes the spacing distributing between an element, it's border and other elements on the page. 

![CSS Box Model](http://i.imgur.com/BWrL7Q2.png)

One sets an element and can nominate a value of padding which is the space between the element and its border (which can be either visible or invisible). A margin can be allocated to provide spacing between this element and other elements on the page. Values can be specified for top, right, bottom and left (in that clockwise order) of the element. 

6: *Explain how the width of an element is calculated, taking into account the element's content, padding, border, margin, etc.*


Title: Calculating The Width of a CSS Element
Category: The Box Model

When calculating the width of an element being rendered on a page, it must be factored in that the assigned width of an element will be added to by the respective left and right padding, margin and border that unite to form the elements desired appearance on the page.

Here is the example given in the material 

```
.element {
    width: 300px;
    padding: 20px;
    margin-left: 10px;
    margin-right: 10px;
    border: 1px solid black;
}
300 (width) 
+ 20 (left padding) 
+ 20 (right padding) 
+ 10 (left margin) 
+ 10 (right margin) 
+ 1 (left border) 
+ 1 (right border)
= 362 pixels
```

As you can see, even though 300px is the given width of the element – the true or resulting width of the element is actually 362px, those extra 62 pixels are distributed between its padding, margin and border.

7: *Explain the purpose and function of the `clear` property in positioning elements. List and explain the different values this property can take. Give an example of how to use this property.*

In very simple terms, the clear property specifies the sides of an element where elements are not allowed to float. 

Designers & developers usually float elements to give the page distinct sections, either floating elements to the left or to the right. This creates empty space which other elements can fill. 

However, in cases where they want to keep that empty space clear (either to the left or right or both) they can engage the `clear` property to ensure that this space remains empty. 

These examples should help visualize this idea:

Example 1:

![](http://i.stack.imgur.com/urCUS.jpg)
Example 2:
![](http://i.stack.imgur.com/HNB63.jpg)

---














