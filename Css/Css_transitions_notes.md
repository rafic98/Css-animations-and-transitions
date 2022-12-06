# what are css transitions?

- CSS transitions allow ypu to change css properties smoothly over time intervals

- it is like a simple animation

- Eg:
  changing a acolor of an html element when you hover the mouse over it

  Creating borders on elements when you hover

  or changing the bg color of an element when you hover over it, click on it etc..

# Using the transition property

## transition property properties:

- The name of the CSS property for which the transition effect is intended is defined by the transition-property property (the transition effect will start when the specified CSS property changes).

## transition duration:

- The CSS property called transition-duration determines how long a transition between two states should last.

- you can specify the length in second or milliseconds

## transition-timing-function:

- The speed curve of the transition effect is specified by the transition-timing-function attribute. A transition effect can modify its speed throughout the length of its duration using this feature.

- values can be define as: ease, ease-in, ease-out, ease-in-out, etc..

## transition-delay:

- lets you specify the wait time before a transition starts

- values can be in seconds and milliseconds

### shorthand transition property order:

- transition: <property> <duration> <timing-function> <delay>

- example: transition: width 2s ease 0s // this will change the width of an element
