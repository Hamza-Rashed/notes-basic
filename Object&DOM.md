
# Prpblem Domain 

A problem domain is the area of expertise or application that needs to be examined to solve a problem. 
A problem domain is simply looking at only the topics of an individual's interest, and excluding 
everything else. For example, when developing a system to measure good practice in medicine, carpet 
drawings at hospitals would not be included in the problem domain. In this example, the domain refers
to relevant topics solely within the delimited area of interest: medicine. This points to a limitation
of an overly specific, or overly bounded, problem domain. An individual may think they are interested 
in medicine and not interior design, but a better solution exists outside of the problem domain as it
was initially conceived. For example, when IDEO researchers noticed that patients in hospitals spent a
huge amount of time staring at acoustic ceiling tiles, which "became a symbol of the overall ambiance:
a mix of boredom and anxiety from feeling lost, uninformed, and out of controle .

# Object

So, firstly, how do we create an object? We can do it two ways:

```  var x = new Object(); ```
```  var y = {}; ```

Both of these mean exactly the same thing & both simply instantiate an empty object. In reality, the vast majority of developers use the second method - it's a lot shorter whilst still being clear as to what it does.

As a side note, this is identical to how we might create new arrays, either through var z = new Array(); or through simply var z = [].

Now we have this object, we can define properties (or keys) and values. This can be done in a number of ways. You can create an empty object & then add properties:

```  var x = {}; ```

```  x.foo = "bar"; ```
```  x["baz"] = 123; ```

You'll notice the two ways of assigning properties. You can either use the dot notation or the square brackets. The differences between the two are easily shown through this code snippet:

``` //x = some object ```
   
``` var bar = "foo" ```
   
``` x.bar //looks for "bar" property in object "x" ```
   
``` x[bar] //looks for "foo" property in object "x" ```


# DOM 
The DOM is the way Javascript sees its containing pages' data. It is an object that 
includes how the HTML/XHTML/XML is formatted, as well as the browser state. A DOM element
is something like a DIV, HTML, BODY element on a page. You can add classes to all of these using CSS, or interact with them using JS.






