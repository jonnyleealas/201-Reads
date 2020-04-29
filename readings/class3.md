# Jonathon Lee
## Read: 03 - HTML Lists, CSS Boxes, JS Control Flow
#
### List in html
- Ordered lists= Each item of the list is numbered. < ol >
- Unordered lists= list begins with bullet. < ul >
- Defenitions list= set of terms with defenitions for each term. < dl >
#
## CSS
Treats each html element as if it lives in it's own box. we can change border, margin, padding, show , and hide boxes. To change width and height you and use ems. Which literaly take the size of m and doubles it. Or you can change by percentage or by pixels. Pixels are more accurate.
# 
## Limiting Width
This is used to shrink the size of a users screen. If the browser window shrinks the box will shrink; and vice versa.
#
## Overflow
This tells the browser what to do if contents within a box overflow. The over flow can also hide anything that doesn't fit in the browser page.
#
## Border, Margin, Padding
These are what make up a box. Margin sits outside the border. Border is the middle guy. padding is right in the center. 
#
## White space
Space between items in a page. Anything that doesn't touch another thing.

# Javascript

if ( x >=50){
#
    congragulate() ;
}
#
This is a type of question you can ask in js to have some output in your site. If x is >= to 50 then the code for congragulate would run. If the statement was false then the another code could possibly run.
#
Else statements: An else statement could be used after and if statement incase the if statement proved false. If the if statement proved false then the else statement would run.
#
### Ex:
if ( x >=50) {
#
    congragulate();
} else {
#
    encourage();
}
#
## Switch Statements
This is meant to send a message according to which level of the code it is on. If a thin happens at level say this. If a thing happens at level two say this.
#
## Truthy/ Falsey
#
   - false
   - 0
   - ' ' string
   - NaN(not a number)
   - Variable withouth a value
#
- true
- 1 or numbers that aren't 0
- 'string' strings with content
#
Anything that isn't a falsey can be truthy. 

#
## Skip to my loops
### For loops
For loops can be used to run code for a specific amount of times. ( var i=0; i < 10; i++). This reads left to right. i = 0. 0 is less than 10. Add 1 to 0. Then it starts again. 1 is less than 10. Add 1 to 1 = 2. 2 is less than 10 and so on. Eventually the number will no longer be less than 10, and the loop will end.
# 
### While loops
While loops are similar to for loops except they can go on forever. The code can keep running as long as the condition is true.
#
### Do While loops
These run the statement at least once weather it is true or false.
#
It's important to make sure a loop doesn't run forever.  Browerser will read everything in JS before movingin on to anything else. If an infiite loop is in the code it will keep checking the code till the browser runs out of memory causing bad things. Really bad things. Not the worst things. Maybe just annoying for your browser.