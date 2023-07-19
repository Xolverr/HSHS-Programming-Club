# Day 1
## Introduction to WoofJS
WoofJS is a web based IDE and library, used to make games! This is a great way to learn the basics of programming, while having a ton of fun doing it! When you open up WoofJS (After making an account and logging in) you will see four tabs:
Preview - This is where you can see a snippet of how your game is looking and playing, you can refresh it with the arrow in the top right. You can also open it up into a new window, which will be a fullscreen version of your game. You can share this fullscreen link to other people to show off your creations!\
Documentation - This tab allows you to search and click around for imformation on how to use WoofJS code-wise. I will explain documentation more in the future, as it is very important for not only writing code here in WoofJS, but for any programming project you will ever do.\
Tutorials - This tab has a bunch of tutorials we will go through, and you can do these on your own as well! These all progress in difficulty as you go farther into them, and will help reinforce very important skills down the line. \
Code - This is the tab where you actually write your code! You can adjust the color scale with the tab in the top left of the window to make it look how you like.\


## Writing your first lines of code!
We can start doing stuff! To start off with so that we have something to show before I get into explaining the basics, lets put a rectangle on the screen!\
Im going to give you some code, then explain how it all works:\
```
var rectangle = new Rectangle({
  height: 50,
  width: 500,
  color:"green",
  angle: 45
})
```
This code creates a rectangle on your screen, look!\
Most of this is straightforward - you provide the width, height, color, and angle you want the rectangle to be!\
Now im sorry this will be a lot of talking, but you need to understand how this all works, so that you can use the knowledge and make more complicated games with woof!\
So with the above code we use the var keyword. This defines a variable with the name "rectangle", and then we set it equal to a new rectangle on the screen with the parameters we decided.\
You can think of a variable as a box. This box can hold whatever we want it to, in this case it has a rectangle inside it. This box is labled rectangle, so we can find it again later and change whats inside it, maybe rotate the rectangle or change its size. Variables are the most important thing to know about programming, because they are the basis of everything you will do!

## Now, lets make this rectangle do something interesting!
So weve made a rectangle, and you understand the basics of how we made it. But its pretty boring, dont you think? Just sitting there, rotating when we change the numbers. Lets make this rectangle interactive!\
To make the rectangle do something when we click on it, we need to attach a handler to it! This is very simple:\
```
rectangle.onMouseDown(() => {

})
```
This is very simple - when the rectangle is clicked on (Mouse Down) then we want to do someting! That something is what goes between those {}'s, we can write code in there and it will execute when the rectangle is clicked on!\
Lets try it! write
```
rectangle.height = 25
```
inside those brackets! Now when you click on it that code will execute and change the rectangles height to 25! You can play around with this, changing the value, maybe changing other parts of the rectangle like color and angle! You can use the documentation tab to look up all the properties rectangle has, and change whatever you want! Just make sure to seperate the code lines with a newline or a semicolon (;). Otherwise it might give you an error!

## What next?
Well this is the end of what I had planned for the day, if you are having fun and want a challenge to work on over the week, try doing the tutorial "Star Catcher"\
This is the first tutorial, and might have some things that you have not seen before. If you get stuck, you can look on the documentation tab to see if you can find anything, and dont worry about asking for help on the slack channel! We will always help you with whatever questions you have. If you can get it working, amazing! If you cant, thats perfectly fine, your just starting and theres some stuff there you have not seen yet! We will go over it tomorrow and work on it together!