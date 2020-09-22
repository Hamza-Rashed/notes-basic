# CSS Transforms

The transform property  allows authors to resize, position and change elements; this can be on either the two-dimensional (2D) or three-dimensional (3D) setting. Before getting into the their individual properties and values it is good to know that the general syntax for the transform property is very simple; include the transform property followed by the value and its specific values inside parentheses.
-	2D Scale: using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
-	2D Translate: using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
-	2D Skew: the last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.
-	It is common for multiple transforms to be used at once.
-	3D Rotate: with three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.
-	3D Scale: by using the scaleZ three-dimensional transform elements may be scaled on the z axis. This is a source of trouble when no other three-dimensional transforms are in place, as there is nothing in particular to scale.
-	3D Translate: a negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.
-	Elements cannot be skewed on the z axis.

![](https://gutenberghub.com/wp-content/uploads/2020/01/Screen-Recording-2020-01-18-at-01.38-PM.gif)

> As a web designer, you’re probably well acquainted with working in two dimensions, `X `and `Y`, positioning items horizontally and vertically.
> With a 3D space initialized with perspective, we can now transform elements in three spatial dimensions with the third Z dimension.

***3D transforms use the same transform property used for 2D transforms. If you’re familiar with 2D transforms, you’ll find the basic 3D transform functions similar.***

- ```rotateX( angle )```
- ```rotateY( angle )```
- ```rotateZ( angle )```
- ```translateZ( tz )```
- ```scaleZ( sz )```

# Transitions
-	Transitional Properties: it is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another.
-	Transition Duration: the duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms).
-	Transition Timing: the transition-timing-function property is used to set the speed in which a transition will move.
-	Transition Delay: determines how long a transition should be stalled before executing.
* `transition-property`: determines exactly what properties will be altered in conjunction with the other transitional properties
* `transition-duration`: sets the duration in which a transition takes place
* `transition-timing-function`: sets the speed in which a transition will move
* `transition-delay`: sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing

These each can be used as an independent property or can be combined under the transition property in the order listed above.

# Animations

When multiple transitions are required, the transition property becomes obsolete and the animation property becomes the focus. 
To set multiple points at which an element should transition, we use the `@keyframes` rule, which includes the animation name, any animation breakpoints, and the properties intended to be animated.
-	Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.
-	Animation Duration, Timing Function, & Delay: once you have declared the animation-name property on an element, animations behave similarly to transitions. They include a duration, timing function, and delay if desired. To start, animations need a duration declared using the animation-duration property. As with transitions, the duration may be set in seconds or milliseconds.

> When multiple transitions are required, the transition property becomes obsolete and the animation property becomes the focus. To set multiple points at which an element should transition, we use the` @keyframes` rule, which includes the animation name, any animation breakpoints, and the properties intended to be animated.

``` ruby
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```





