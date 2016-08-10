
Exercise:

[Codepen Exercise 1](http://codepen.io/nikpod/pen/YWRRaJ)


#Questions


1: *HTML elements have a hierarchical structure relationship; there are parents, siblings, children, children of children, etc. Explain each of these terms and the meaning of these relationships.*

As a result of the structure of HTML and the Document Object Model (DOM) utilising the tree structure; a structure we are all familiar with from our own family trees. The concept has been used further  to give names and relationships between elements within HTML. 

These will be described, very breifly below: 

Parents: When a html tag has another tag nested within it, the nested tag can be considered a child of the html tag it lies within. For example, when setting up an unordered list (ul) the list items (li) tags that are under it are the child elements and the (ul) are their parent element.


```
<code><ul> I'm the parent
	<li>I'm the child</li>
</ul></code>
```


Siblings: In the above context, other (li) tags in that nested group would be siblings to each other sharing the same (ul) parent element.


```
<code><ul> 
	<li>and we are siblings</li>
	<li>and we are siblings</li>
</ul></code>
```

Children: As explained above, the (li) elements are the children of the ul parent elements. 

Children of Children: Now, give one of the li tags above a paragraph (p) that p tag is the child of the li element it sits within. It is also now a grandchild or (child of another child element) to the ul tag.


```
<code><ul> I'm the parent
	<li>I'm the child of the ul and a parent to the p</li>
		<p>I'm a child of the li, and a grandchild (or child of a child) of the grandpa ul element</p>
</ul></code>
```

---


2: *Describe the function of the `meta` tag, and give at least two examples of its usage.*

Meta tags are used for a range of tasks and support cross browser integration. Further they are also very important for search engine optimization, getting linked to the major search engines through keywords alluding to relevance to a given search query.

Two examples of this is

If we were running web store selling garden furniture made from bamboo - we can specify this with meta tags.

  <meta name="keywords" content="wood, furniture, garden, garden-table, bamboo">

  <meta name="description" content="Official dealer of bamboo garden furniture.">
  
Then when a potential customer online is searching for bamboo garden furniture, our webstore has a better chance of being seen in their search results. 
  
  ---

3: *Describe the function of the div tag and discuss the advantages and disadvantages of using it.*

The div tag or division tag allows the grouping of relevant sets of information. It is very heavily used in web development to give order and structure to a page as well as applying classes and ids to divs for use in CSS, JavaScript & jQuery.

The advantages are that it offers a simple, easy and widely adopted way to organize and design web pages. 

However, its main disadvantage is that a div tag offers no contextual information of what it is doing. One div could be for a menu navigation, the next a login section, followed by a form and so on. 

Semantic code is the idea that a reader should be able to gain some understanding of what code is doing by the elements chosen to display it. HTML now offeres many ways to achieve this. for example using section tags instead of divs, using header, footer and nav give much clear guidance and interpretability to code; thus having more semantic value.

---

4: *Fully describe the function of the `pre` tag.*

The pre tag preserves formatting, an example of this being used is when showing code snippets – to stop these being rendered by the browser and actually display html and other syntax in the manner intended including spaces/indentations along with the html elements.

Thought it is much the same as the code tag, I think one difference is that the pre tag preserves spacing as well, whereas the code tag just allows code to be displayed and not rendered to the page. 

```
<code><pre>
	<ul> I'm sligthly indented
		<li>I'm also indented</li>
			<p>I'm even further indented</p>
	</ul>
</pre></code>
```



---

5: *Explain the function of the `textarea` element and describe in detail the attributes it accepts and their effects of their different values.*

Title: How to Input a Large Body of Text in HTML
Category: HTML Forms

The `textarea` element is used to create longer, multi-line text fields allowing a user to enter more information into a form. 

One area that many website utilise this is with the contact form, usually seperated into a few input fields: name, email, and message. The message uses this textarea element to enable the user to write an informative, though usually brief, message with their message - perhaps a question or some feedback.

Columns (width) and rows (height) can be specified so the format can match the other input fields (note: It is better to use CSS for this). It is common however to have the drag to extend function enabled on the bottom right of the textarea box; so that more the text can be viewed. 

```
<FORM ACTION="" METHOD=POST>
Name <input type="text" placeholder="Name">
Email <input type="email" placeholder="Email">
Url <input type"url" placeholder="http://www.example.com">
Comment
<TEXTAREA NAME="comment" COLS=40 ROWS=6 maxlength=200 placeholder="Comment (Max 200 characters)"></TEXTAREA> <P> 
</FORM>
```
![textarea input form](http://i.stack.imgur.com/QEFNz.jpg)


---

6: *Explain in detail the function of the `select` tag and how it is added to web pages.*

The select tag allows a developer to create drop down and multi-select lists within html, often used in forms and in payment gateways. An example would be selecting the appropriate currency from a drop down list. 

A multi-select field, used when more than one option can be selected could be used when asked to select spoken languages, or in the example below Country of residence.

```
<code><select name="select">Select Country:
  <option value="value1" selected>USA</option> 
  <option value="value2">Canada</option>
  <option value="value3">Mexico</option>
</select></code>
```
![Select Tag image](https://cdn.dzone.com/static/images/vaannila/struts1/HtmlSelectTag1Pic2.gif)













