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






















