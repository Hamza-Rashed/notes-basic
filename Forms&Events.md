# Lists in HTML :: 
## HTML offers authors several mechanisms for specifying lists of information. All lists must contain one or more list elements. Lists may contain:

   * Unordered information.
   * Ordered information.
   * Definitions.

## The previous list, for example, is an unordered list, created with the UL element:

``` <UL> ```
``` <LI>Unordered information.``` 
``` <LI>Ordered information. ```
``` <LI>Definitions.``` 
``` </UL> ``` 

## An ordered list, created using the OL element, should contain information where order should be emphasized, as in a recipe:

   * Mix dry ingredients thoroughly.
   * Pour in wet ingredients.
   * Mix for 10 minutes.
   * Bake for one hour at 300 degrees.

> Definition lists, created using the DL element, generally consist of a series of term/definition pairs (although definition lists may have other applications). Thus, when advertising a product, one might use a definition list:
 
* Lower cost 
     The new version of this product costs significantly less than the previous one!
* Easier to use
    We've changed the product so that it's much easier to use!
* Safe for kids
    You can leave your kids alone in a room with this product and they won't get hurt (not a guarantee).

## defined in HTML as:

``` <DL> ```
```<DT><STRONG>Lower cost</STRONG>```
```<DD>The new version of this product costs significantly less than the```
```previous one!```
```<DT><STRONG>Easier to use</STRONG>```
```<DD>We've changed the product so that it's much easier to use!```
```<DT><STRONG>Safe for kids</STRONG>```
```<DD>You can leave your kids alone in a room with this product and```
```they won't get hurt (not a guarantee).```
```</DL>```
![](https://ways2web.weebly.com/uploads/5/4/4/8/54485903/8033093_orig.png)

# HTML tables

## Tables can be a useful way of organising content on a web page, particularly text.

   * A table is defined with the <table> tag.
   * Each row in the table is defined with the <tr> tag.
   * A table heading is defined with the <th> tag. (Headings are bold and centred by default.)
   * Each cell of data in the table is defined with the <td> tag.

Basic table: Set up a table with three headings to your page, by adding the following code to your document under the “ordered list” code. This is a real-life example that lists a weekly class schedule. The <th> tags will form the columns in this table, and the <td> tags will form the rows.

     <table style="width:100%">
     <tr>
       <th>Monday</th>
       <th>Tuesday</th>
       <th>Wednesday</th>
     </tr>
     <tr>
       <td>9AM Lecture</td>
       <td>12PM Lecture</td>
       <td>Study Break</td>
     </tr>
      <tr>
       <td>10AM Lecture</td>
       <td>Study Break</td>
       <td>2PM Lecture</td>
      </tr>
    </table>
![](https://1.bp.blogspot.com/-3V1DEl5pM5Y/XoKBbZcDFJI/AAAAAAAAFw8/hDQWOQOQ_LEJZ9QdZ-ijgtp9XjBMbAW6QCLcBGAsYHQ/s1600/9.png)

# What are web forms?

Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

A web form's HTML is made up of one or more form controls (sometimes called widgets), plus some additional elements to help structure the overall form — they are often referred to as HTML forms. The controls can be single or multi-line text fields, dropdown boxes, buttons, checkboxes, or radio buttons, and are mostly created using the <input> element, although there are some other elements to learn about too.

Form controls can also be programmed to enforce specific formats or values to be entered (form validation), and paired with text labels that describe their purpose to both sighted and blind users.


# Event jacascript :

DOM Events are sent to notify code of interesting things that have taken place. Each event is represented by an object which is based on the Event interface, and may have additional custom fields and/or functions used to get additional information about what happened. Events can represent everything from basic user interactions to automated notifications of things happening in the rendering model.

This article offers a list of events that can be sent; some are standard events defined in official specifications, while others are events used internally by specific browsers; for example, Mozilla-specific events are listed so that add-ons can use them to interact with the browser.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types-640x480.jpg)
