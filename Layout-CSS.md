# What is CSS layout ?? 
CSS page layout techniques allow us to take elements contained in a web page and control where they 
are positioned relative to their default position in normal layout flow, the other elements around 
them, their parent container, or the main viewport/window.  The page layout techniques we'll be 
covering in more detail in this module are

   * Normal flow
   * The display property
   * Flexbox
   * Grid
   * Floats
   * Positioning
   * Table layout
   * Multiple-column layout

Each technique has its uses, advantages, and disadvantages, and no technique is designed to be 
used in isolation. By understanding what each method is designed for you will be in a good place 
to understand which is the best layout tool for each task.

![](https://miro.medium.com/max/1024/1*XCZZZmhQN4rHLw2dW14BZQ.png)

## The methods that can change how elements are laid out in CSS are as follows:

    The display property — Standard values such as block, inline or inline-block can change how 
    elements behave in normal flow, for example making a block-level element behave like an inline
    element (see Types of CSS boxes for more information). We also have entire layout methods that
    are switched on via specific display values, for example CSS Grid and Flexbox, which alter how 
    elements inside the element they are set on are laid out.
    Floats — Applying a float value such as left can cause block level elements to wrap alongside 
    one side of an element, like the way images sometimes have text floating around them in magazine layouts.
    The position property — Allows you to precisely control the placement of boxes inside other boxes.
    static positioning is the default in normal flow, but you can cause elements to be laid out differently 
    using other values, for example always fixed to the top of the browser viewport.
    Table layout — features designed for styling the parts of an HTML table can be used on non-table 
    elements using display: table and associated properties.
    Multi-column layout — The Multi-column layout properties can cause the content of a block to layout
    in columns, as you might see in a newspaper.
