# Jonathon Lee
# Class 201 
# Read 09
#
### Forms
- Elements that allow you to collect info from the user.
- Spaces for users to fill in.
- Froms are the space you use to type inside of google search.

### Form Controls
- Text input
- Password input
- Text area
- Music category buttons
- Check boxes
- Drop down boxes
- Submit buttons
- Image buttons
- File upload button
#
### How forms work
1. Fill in the info.
1. Info is sent to server.
1. Server processes info and can also store info.
1. Server creates a page to send based on info.
#
### Elements
- < form >
- action
- method(not to be confused by method in an object literal)
- width should should be controlled in css
#
### List
- List-style-type controls shape of bullet point.
- List-style-imag = and image as a bullet point.
- We can also change the position of the bullet point.

### Cells
- Border-spacing can decrease the size of the border in a cell.
- We can have empty cells; show, hide, inherit are cell values.
#
### Js Events
Browsers register different types of events that are caused by the user.
#
### Event trigger steps
1. Select element node for script to respond to.
1. Select which element the node will trigger response.
1. Choose which code will run when even occurs. = Binding even to DOM nod.
#
Events are what you see when you type in a password and a message is prompted that the pw is too short. 
#
We bind events using the DOM in JS.
- element
- event
- function
# 
Event names are followed by the word on.Ex: onblur
- Event listeners handle more than one function at a time.
#
### Add EventListener
- 3 parameters 
1. The event you want to listen for.
1. The code you want it to run.
1. Boolean indicating how events flow. Usually set to false.
Events nest inside other elements like aren't child. But they only matter when the code has even handlers, and ancestor, or descendant.
#
When an event occurs the event object tells you information about.
1. Info about the event.
1. The element it happened on.
#
Events tell browser when something has happened. 
- Binding is the process of stating which event you are waiting to happen, and where it is going to happen.
- Order of happening: Event then which element its happening to.
- Event happening can trigger JS functions
- Event delegations monitor: events happening/children element. W3C DOM.
