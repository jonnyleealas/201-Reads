# Jonathon Lee
# Class 201
# Read 14

### Google Team 
This read was about working in a team. It talked about the differences of teams that work well together  and teams that don't work well together. What makes them different? 
#
One difference is that groups tend to innovate faster. Make sense; more people more brains to deal with a probllem. 
# 
They used something called Project Aristotle to reasearch google work groups. Why did some succeed and why did some fail? They found a few things that pointed to a successful team.
- Each memeber had equal opporunity to speak.
- They lifted each other up. 
- High average social sensitivity. 
- People need to feel that their ideas will not be ridiculed.
- Having and even state of mind; not blasting out at fellow co-workers.
- Openness amongst one another.
- Psychological safety.
- Feeling free to express.
- Members need to listen to one another.
- Allowing everyone to have a common platform.

### CSS
- Transform = two dimensional and 3 dimensional
- .box-1 {
  transform: scaleX(.5);
}
.box-2 {
  transform: scaleY(1.15);
}
.box-3 {
  transform: scale(.5, 1.15);
}

- .box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}

- These properties help alter properties to give it more demensions.

### Transitions
- An element must have a change in states. 
- .box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}

### Animations 
Animations further the control given by transitions. Animations let things move.
- @keyframes slide {
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


              