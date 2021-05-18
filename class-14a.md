


# Transforms
> CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements Within this lesson we’ll take a look at both two-dimensional and three-dimensional transforms. Generally speaking, browser support for the transform property isn’t great, but it is getting better every day.

## Transform Syntax
> The transform-function> data type is specified using one of the transformation functions listed below. Each function applies a geometric operation in either 2D or 3D. The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses

### 2d 
> Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis

![](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/transform-origin-examples.png)

### 2D Scale
> Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger 
![](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/CSS3Transforms2D.png)



# Transitions & Animations
> Animations give the appearance of motion or change over time. ... Transitions are animations used to keep users oriented during user interface (UI) state changes and object manipulations, and make those changes feel smooth instead of jarring.The transition defines how the change occurs, but not the specific start and end values. Animations, on the other hand, can change property values inside their keyframes. The property values don't even need to exist outside of the animation keyframes. This makes animation far more dynamic and flexible than transitions.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQos6_-yLvIKq3_c3ScTIUZiTRAoecwLTx85w&usqp=CAU)


### Transitions
> pecify the Speed Curve of the Transition
ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
linear - specifies a transition effect with the same speed from start to end.
ease-in - specifies a transition effect with a slow start.
You can transition background-image . Use the CSS below on the img element: -webkit-transition: background-image 0.2s ease-in-out; transition: background-image 0.2s ease-in-out; This is supported natively by Chrome, Opera and Safari.

### Animations 
>  CSS animations make it possible to animate transitions from one CSS style configuration to another. Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation's style, as well as possible intermediate waypoints.
CSS
* body {
padding: 30px;
}
* #animate {
top: 100px;
left: 30px;


1. Fade in
> CSS Fade-in Transition on Hove
This can be applied to text or images. For example, you could set an image to start at 50% opacity and increase to 100% opacity over the duration of two seconds when a user hovers over it. Use this CSS code: HTML .
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRO-WlDaip6Oi_3W7NuI3vE3tHZWin8hrGm1g&usqp=CAU)


2. Change color
> ![](https://i.stack.imgur.com/2QaEG.png)Simply add the appropriate CSS selector and define the color property with the value you want. For example, say you want to change the color of all paragraphs on your site to navy. Then you'd add p {color: #000080; } to the head section of your HTML file


3. Grow & Shrink
> The flex-shrink property specifies how the item will shrink relative to the rest of the flexible items inside the same container. Note: If the element is not a flexible item, the flex-shrink property has no effect Flex-shrink is the opposite of flex-grow, determining how much a square is allowed to shrink. It only comes into play if the elements must shrink to fit into their container — i.e. when the container is just too small. Its main use is to specify which items you want to shrink, and which items you don't .![](https://miro.medium.com/max/3752/1*43faUXdI5KbcSb_LbXO-Ng.png)


4. Rotate elements
> An element can be rotated 90 degrees by using the transform property. This property is used to move, rotate, scale and others to perform various kinds of transformation to elements. The rotate() transformation function can be used as the value to rotate the element.![](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/transform-origin-examples.png)


5. Square to circle
> Squares and rectangles are easy, as they are the natural shapes of the web. Add a width and height and you have the exact size rectangle you need. Add border-radius and you can round that shape, and enough of it you can turn those rectangles into circles and ovals.tep 1: Position the Object to the Center. Position he object you want to move to the center of the circular path. ...
Step 2: Use translateX() To Define the Radius of the Circle. ...
Step 3: Insert A rotate() Or Two Into The Mix. ...
Step 4: Apply The Animation Code 
1[](https://i.ytimg.com/vi/0jIy68xroxA/maxresdefault.jpg)


6. 3D shadow
> With CSS you can add shadow to text and to elements.
In these chapters you will learn about the following properties:
text-shadow
box-shadow
![](https://i2.wp.com/www.csscodelab.com/wp-content/uploads/2020/02/css-3d-cube-logo-animation-shadow.png?fit=867%2C604&ssl=1)


for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)
 
 ***best regard*** 
 
