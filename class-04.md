# HTML Links, CSS Layout, JS Functions


## Links

Links are the feature that allows users to move from webpage to webpage, regardless if the pages are on the same site or another site. Links are created though the `<a>` anchor tag as well as the `href` attribute. Below is an example of how you can link to the GitHub website in HTML.

`<a href="https://github.com/">GitHub</a>`

That was an example of an absolute URL (normally for other websites); when linking to your own website you use relative URL. In order to have an easier coding experience, it is advised to place different pages in the most suitable directories. Relative links can be fore files form anywhere, whether the same folder or a grandparent  or grandchild folder. 

Other attributes can be added to the anchor tag to specify the type of link and where the link page should open.

> The (a) element uses the href attribute to indicate the page you are linking to.

> If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.


Links are created using the `<a>` element which has an attribute called `href`. The value of the `href` attribute is the page that you want people to go to when they click on the link `<a href="about.html">About Film Folk</a>`. Links can lead to the following:
* Other sites.
* Other pages in the same site, where URLS can be _absolute_ or _relative_.
* Specific part of the same page.
* Specific part of another page
* Email Links `mailto`.

Also, links can be opened in new windows using the `target` attribute.



## Layouts

#### The basics:

| Element | Role |
| --- | --- |
| Block-level elements | start on a new line |
| Inline elements | flow in between surrounding text |
|Containing Elements | the element that holds another block-level element / parent|

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
- Screen Sizes

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens
- Screen Resolution

Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
- Page Sizes

**c.** Also, the `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. This can be `float:right` or `float-left`. Furthermore, float can be cleared using the `clear` property, the values can be `left`, `right`, `both` and `none`. To create multi-column layouts with floats, The following three CSS properties are used to position the columns next to each other:
* `width`: sets the width of the columns.
* `float`: positions the columns next to each other.
* `margin`: creates a gap between the columns.

#### Positioning elements:
* Normal flow: Block-level elements normally appear on a new line after the element before it, this is the default behavior.
*  Relative positioning: shifts element to the top, right, bottom, or left of where it would have normally sat.
* Absolute positioning: This positions the element depending on how its parent is positioned.
* Fixed positioning: A type of absolute positioning but instead of depending on the parent it depends on the browser.
* Floating elements: Takes elements out of normal flow.

# FUNCTIONS
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements). 

Functions are statements that have been grouped together due to their functionality (together they perform a specific task). Using functions makes things more organized and easier, because, if you decided you wanted to perform a task more than once in different places in your code, you can do so with just one function.


### Pair Programming:
Pair programing is a technique used to foster a collaborative environment while developing key industry skills, and it is used commonly in many agile work environments.
pair programming involves two roles: 
* Driver: the programmer who is typing and the only one whose hands are on the keyboard. Manages the text editor, switching files, version control, awriting—code.
* Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. 
Using pai programming touches on all four skills (speaking, listening, reading and writing): _developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves._

The following are reasons _why_ you should do _pair programming_:
1. Greater efficiency.
2. Engaged collaboration
3. Learning from fellow students.
4. Social skills.
5. Job interview readiness.
6. Work environment readiness.







