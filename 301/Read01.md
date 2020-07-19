# 301 - Read01

## Responsive Web Design 

It is the practice of building a websites suitable to work in different devices (desktops , mobile phones , tablets, etc) with different sizes.

**Responsive Web Design** has three main components:

- **Flexible Layouts** : capable of dynamically resizing to any width.
- **Media Queries** : built as an extension to media types commonly found when targeting and including styles
- **Flexible Media** : changing the media size as the size of the viewport changes.


**Relative Values** 

target (target width) ÷ context (parent width) = result (percentage or em units)

## Float 

It is a css positioning property. Each Element with float property, will make the text wrapped around it.

![Float](https://css-tricks.com/wp-content/csstricks-uploads/web-text-wrap.png)

**Problems with float** 

- Pushdown: when the element inside the floated element is wider, the browser will render the element outside the float 
*Quick Fix* : (overflow: hidden to cut off excess)

- Double Margin Bug: when you apply margin in the same direction as the float, the margin will be doubled.
*Quick Fix* : (display: inline)

- The 3px Jog: when the text that is up next the floated element is kicked away by 3px
*Quick Fix* : (set a width or height on the affected text)

- Bottom Margin Bug (in IE7): if the floated parent element has floated children inside it, bottom margin of these children is ignored.
*Quick Fix* : (using bottom padding on the parent instead)