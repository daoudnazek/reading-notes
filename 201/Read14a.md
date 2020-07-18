# Trsnsforms 

It is a **CSS3** property that has alternative ways to size, position, and change elements. it comes with two different settings:

1- two-dimensional.
2- three-dimensional.

### Transform Syntax

section {
    transform: scale(1.5);
}

**transform** is the *name* of the property and **scale(1.5)** is the *value* of it.

## 2D transforms 

 - **2D Rotate**

 used to rotate an element , values (0 - +-360).

 *example* 
 .box {
  transform: rotate(20deg);
  transform: rotate(-20deg);
 }

 - **2D Scale**

 used to change the appeared size of an element , default values 1 , values larger than 1 make the element larger , and vlues between 0 and 1 make the element smaller.

 *example* 
 .box {
  transform: scale(0.5);
  transform: scale(1.5);
 }

 - **2D Translate**

 used to change the position of an element , in both x and y directions.

 *example* 
 .box {
  transform: translateX(10px);
  transform: translateY(10px);
  transform: translate(-10px,50px); .. in both x and y directions.
 }

 - **2D Skew**

 used to distort the element , in both the horizontal and vertical axizes.

 *example* 
 .box {
  transform: skewX(10deg);
  transform: skewY(-10deg);
  transform: skew(-10deg,50deg); .. in both vertical and horizontal.
 }

# Transitions and Animations

It is used to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.for a transition to take place, an element must have a change in state, and different styles must be identified for each state. 
It has **four properities** :
 - transition-property
 - transition-duration
 - transition-timing-function
 - transition-delay

### Transition Property 

background
-colorbackground
-positionborder
-colorborder
-widthborder
-spacingbottomclipcolorcropfont
-sizefont
-weightheightleftletter
-spacingline
-heightmarginmax
-heightmax
-widthmin-
heightmin
-widthopacityoutline
-coloroutline
-offsetoutline
-widthpaddingrighttext
-indenttext
-shadowtopvertical
-alignvisibilitywidthword
-spacing

