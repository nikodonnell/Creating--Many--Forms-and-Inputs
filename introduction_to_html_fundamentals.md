#Questions


1. HTML elements have a hierarchical structure relationship; there are parents, siblings, children, children of children, etc. Explain each of these terms and the meaning of these relationships.

Parents: When a html tag has another html nested within it, the nested tag can be considered a child of the html tag it lies within. When setting up an unordered list <ul> the list items <li> tags that are under it are the child tags and the <ul> their parent.

Siblings: In the above setting, other <li> tags in that nested group would be siblings to each other sharing the same <ul> parents.

Children: As above, the <li> elements are the children of the parent elements. 

Children of Children: Now, give one of the <li> tags above a paragraph <p> that <p> is the child of the <li> its sits within. It is also now a grandchild or (child of another child element) to the <ul> tag.


2.Describe the function of the `meta` tag, and give at least two examples of its usage.

Meta tags are used for a range of tasks and support cross browser integration. Further are also important for search engine optimization, getting linked to the major search engines through keywords alluding to relevance to a given search query.

Two examples of this is

  <meta name="keywords" content="wood, furniture, garden, garden-table, bamboo">

  <meta name="description" content="Official dealer of bamboo garden furniture.">

3. Describe the function of the div tag and discuss the advantages and disadvantages of using it.

The div tag or division tag allows the grouping of relevant sets of information. 

Further classes and ids can be assigned to divs for use in CSS, JavaScript & jQuery.

4. Fully describe the function of the `pre` tag.

The pre tag preserves formatting, an example of this being used is when showing code snippets – to stop these being rendered by the browser and actually display html and other syntax in the manner intended including spaces/indentations. 

5. Explain the function of the `textarea` element and describe in detail the attributes it accepts and their effects of their different values.

The textarea tag is used to create long-form and multi-line text input fields allowing a user to enter information into a form.

Columns (width) and rows (height) can be specified. 


Title: How to Input a Large Body of Text in HTML
Category: HTML Forms


6. Explain in detail the function of the `select` tag and how it is added to web pages.

The select tag allows you to create drop down and multi-select lists within html markup, often used in forms and in payment gateways. An example would be selecting the appropriate currency from a drop down list. 

A multi-select field, used when more than one option can be selected could be used when asked to select spoken languages.