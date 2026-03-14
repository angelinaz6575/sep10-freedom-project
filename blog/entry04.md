# Entry 4
##### 3/9/2026

## Content
Part of coding our website is going to know how we are going to code it. This means we are researching tools that we feel confident with using while coding. I did my own research, and here are the tools I picked: CSS flexbox, CSS grid, and Aframe.

### CSS flexbox
I chose CSS flexbox because I find it easy to work with. Using this [website](https://www.w3schools.com/css/css3_flexbox.asp), they gave many examples and readings on how to use CSS flexbox. I took this into consideration and started practing the codes that they had set up for me to practice.

For example,

<img src="cssflexbox1.png"> </img>

This shows a flex box for CSS. What this does is that it helps align, arrange or distribute spaces within a container. It arranges them horizontally, or vertically (rows or columns) in a responsive way. The code in the ` .container ` selector, ` display: flex; ` makes the element into a container so that ti can automatically be responsive. There are also other flexbox properties thats similar to ` flex `.

A few of these are:

 * ` flex-direction ` - Sets the display-direction of flex items (rows/column)
 * ` flex-wrap`- Specifies whether the flex items should wrap or not
 * `justify-content` - Aligns the flex items when they do not use all available space on the main-axis (horizontally)
* `align-items` - Aligns the flex items when they do not use all available space on the cross-axis (vertically)

<img src="cssflexbox2.png"> </img>

If we apply the `display` and `flex-direction` it will turn out to be:

<img src="cssflexbox3.png"> </img>

### CSS grid

This was my second option in researching a tool to use for my projext. Using the same website as CSS flexbox, I learned The Grid Layout Module offers a grid-based layout system, with rows and columns. The *Grid Layout Module* makes it easy to design a responsive layout structure, without using `float` or positioning.

One of the things I had tinkered with is the CSS grid-template-columns Property.

* `grid-template-columns` - Defines the number and width of the columns in the grid
* `grid-template-rows` - Defines the number and height of the rows in the grid
* `grid-template-areas` - Defines how to display columns and rows, using named grid items

I chose one of the three, which is `grid-template-columns`. If we're defining the number and width of the colums in the grid, there is different common values to do this.

* Fixed lengths (100px 300px 200px)
* Percentages (20% 60% 20%)
* fr unit (1fr 2fr 1fr)
* auto (auto auto auto)
* repeat() (repeat(3, 1fr))
* minmax() (minmax(80px, 1fr) 150px 150px)

I worked with the `auto`. This means that the `auto` creats however many columns. If you put 1x auto, then there will only be one column. If you put 2x auto, then here will be 2 column.

Heres an example:

<img src="cssgrid1.png"> </img>

There is 3x auto, meaning there will be 3 columns created. If there would be 2x auto, then it will look like this:

<img src="cssgrid2.png"> </img>

You can already probably guess what it'll look like if there were only 1 auto.

### Aframe

This was my 3rd option as a tool to use for my project. This [website](https://aframe.io/) can help create VR experiences and 3D models. To use this code, it's mainly based off of using HTML. To apply this, we're going to need to apply the starter code ` <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script> ` for the Aframe codes to work.

 One the best things about these website is that it has already given you most of the code. You just have to copy and paste then edit it yourself to your liking.

 For example, if I want a sphere, then I would go to sections full of shapes and go to sphere to copy and paste this code on jsbin `<a-sphere position="0 1.25 -5" radius="1.25" color="red"></a-sphere>`. This is already set up as:
 <img src="aframe.png"> </img>

 Another example is this. ` <a-cylinder color="cyan" segments-radial="6"></a-cylinder> ` This is also another shape, but the `segments-radical="6"` represents how many sides it should have. So when it says 6, then it would have 6 sides. If it were to have the numbers 1-5 in the property, then we the shape will have the number 1-5 in the shape.

 Using the mumber 6 in the property, it'll look like this:

 <img src="aframe1.png"> </img>

 If there were to be 3 10 sides, it'll look like this:

 <img src="aframe2.png"> </img>


 # Skills

### Researching

One of the skills I had developed when doing this tool-finding homework was researching. By researching, I mean like actually trying out the website, and playing around with the code to see if I like it or not. I researched because not only did I have to see if it's easy to use, but I had to see if I understand how to use the tools I'm researching. If I don't, then likely it's not good for me to use it during my project. Researching allowed me to dig deep in to see if it's:
* Easy to use
* I can undertand well
* Deidcated to using it

This applies to all 2 of the websites I'm using for my project. At first, I didn't understand any of the things in it. But after researching, like tinkering around with it on jsbin and the website itself, and reading sections to see how it works, at the end I understand how to use it.

### Trying new things

This is also one of a new skills I had developed. Usually, I would never try new things if I hadn't learn it yet. But I figured it's time to step out of my comfort zone and really try new things I don't know how to do. I would always wait for like a adult to discover new ideas or things to me before I would do it too. This connects back to this entire blog because my teacher didn't teach me what Aframe is, or what CSS flexbox and grid is. I had to really work and try things myself.











[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
