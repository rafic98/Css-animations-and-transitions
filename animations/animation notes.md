# CSS animations

- CSS animation allow transitioning from one css style config to another with possible intermediate waypoints

- it requires atleast two style configs:
  one for the starting state and another for its ending state

- think of an animation as a sequence of tranitions but unlike transitions animations can have multiple states and more than one css style configuration

### the animation-name:

- css property is used to specify the animation thats going to be used, these animations are defined useing @keyframe ruleset

- the name can be anything you want.

### animation duration:

- is used to specify the duration that the animation takes to complete one cycle (seconds,or milliseconds)

### animation timing function:

- specifies the acceleration curves for the animation

### animation-delay:

- Specifies the time the animation should wait before it starts. (seconds and milliseconds)

### animation iteration count:

- Specifies the nnumber of times the animation should repeat. You can use infinite as its value to make the animation loop indefinitley

### animation-fill-mode:

- sets how a css animation applies styles to its target before and after its execution. possible values are none, forwards, backwards, both.

### animation-direction:

- Specifies the direction of animation, it can be normal or alternate
  - it can be used to reverse the direction of an animation once it is complete

### shorthand animation property:

- animation:[animation name] [duration ] [ timimng function] [ animation delay] [ iteration count] [ fill mode] [ direction]

### keyframes:

- used to create a ruleset that defines animations
