
**Arrays []**
houses=[x1,x2,x3];

*Arrays are used to store multiple values in a single variable*

*You access an array element by referring to the index number. console.log(houses[2]);*
*You can change the value of a specific element, refer to the index number. house[0]=xx;*
*the numbering of this list starts at zero (not one).*

**(If and Else) (switch) statements**
var hp=110;
var chance=0;
var triger=false;
if(hp==0)
{
if(chance==0){
die();
}
}
if(hp!=100 && hp<100){
healing();
}
else
{
triger=true;
}

switch(triger){
case true :
consol.log("HI");
break;
default:
consol.log("bye");
break;
}

**console will show HI.**

**Chapter 3**
There are three list types in HTML:
1-An ordered list < ol > : *The list items will be marked with numbers by default* 
2-An unordered list < ul > : *The list items will be marked with bullets by default*
3-Definition lists :
  - < dl > :*tag defines the definition list , contain < dt > and < dd >*
  - < dt > :*tag defines the term name*
  - < dd > :*tag defines the term*
*you can put list inside list (Nested List).*

**Chapter 13**
*you can adjust size of a box by using (width,height) in CSS.*
*you can make a limitaion in width and height by using (min-width,max-width) for width and (min-height,max-height) for height.
**Overflowing Content**

**Overflow** *tells the browser what to do if content larger than box,have two values:*
1- hidden : *hides any extra content that does not fit in the box.*
2-scroll: *adding scrollbar to the box*

**Border**
**Border Width** value :
border-width: 10px(top) 10px(right) 10px(bottom) 10px(left);
**Border Style** *this property using to change style and have many types like solide,dashed,double,etc.*
**Border Color** *you can change color of border by border-color: #00ffff;  for a whole border and border-color: #bbbbaa #111111 #ee3e80 #0088dd; for each line.*
**border-radius to create a corner**
**padding**
*padding properties are used to generate space around an element's content, inside of any defined borders*
*the value can be padding: 10px; for every side and  10px 10px 10px 10px; for each side.*
**Margin**
*margin properties are used to create space around elements, outside of any defined borders.*
*value of property can change like padding margin : 10px; or margin: 10px 10p 10px 10px;*

*text-align property used to change position of text.*

**Display**
*property specifies the display behavior of an element.*
the value can be :
1-inline
2-block
3-inline-block
4-none

*The visibility property allows you to hide boxes from users but It leaves a space where the element would have been.*
*can be two values : hidden and visible*

*you can make a border for image by using border-image property, the value can be (stretch,repeat and round).*
*you can add shadow to box by using box-shadow property*


**Loops**
*Loops check a condition. if it returns true, a code block will run.*
*Then the condition will be checked again and if still returns true, The code block will run again.*
*It repeats until the condition returns false.*
Three common types of loops : 
For,While and do while.

A **For** : Loop uses a counter as a condition.
A **while : Loop used as a condition.
