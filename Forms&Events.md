# Lists in HTML :: 
## HTML offers authors several mechanisms for specifying lists of information. All lists must contain one or more list elements. Lists may contain:

   * Unordered information.
   * Ordered information.
   * Definitions.

## The previous list, for example, is an unordered list, created with the UL element:

```HTML <UL> ```
```HTML <LI>Unordered information.``` 
```HTML <LI>Ordered information. ```
```HTML <LI>Definitions.``` 
```HTML </UL> ``` 

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

```HTML <DL> ```
<DT><STRONG>Lower cost</STRONG>
<DD>The new version of this product costs significantly less than the
previous one!
<DT><STRONG>Easier to use</STRONG>
<DD>We've changed the product so that it's much easier to use!
<DT><STRONG>Safe for kids</STRONG>
<DD>You can leave your kids alone in a room with this product and
they won't get hurt (not a guarantee).
</DL>

