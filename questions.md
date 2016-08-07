#Questions

1. The `input` element has an attribute called "type." Discuss the purpose and function of this attribute, and list some of the values 'type' can be.

The purpose of the input element is to give recognition to an input field which acts to give context to that input field. 

An example of using the input element is the date type.

```
<input type="date" name="appointment">
<input type="time" name="time">
```
This creates an easy way to integrate time and date selection - without building one from scratch. Allowing a developer to focus their efforts on design, customization and functionality.


2. Fully explain what a CSS selector is and list and explain the different types of CSS selectors.

CSS selectors are used to target html elements for style and design. 

They include:

Standard elements like heading <h1,h2,h3>, paragraphs <p>, body, footer etc.

ID

\#idname

Class
.classname


3. Describe what a "next-sibling selector" is. Explain how it works and give an example of its usage.

As we've discussed in previous sections, the DOM document object model follows a hierachy using parent and child elements. A parent element will often have multiple child elements. The relationship between these child elements is referred to as the element's siblings. 

Using CSS we can target an element's siblings and more specifically it's next adjacent sibling using the 'next-sibling' selector. 

For example if we wish to color the second list item (<li>) in a list, we can do so my adding the following CSS rule.

```
li:first-of-type + li{
color: blue;
}
```

4. Describe what color opacity is and explain how to specify it using color declarations.

translucent
rgba

5. Explain in detail what the CSS Box Model is.



6. Explain how the width of an element is calculated, taking into account the element's content, padding, border, margin, etc.


Title: Calculating The Width of a CSS Element
Category: The Box Model


7. Explain the purpose and function of the `clear` property in positioning elements. List and explain the different values this property can take. Give an example of how to use this property.