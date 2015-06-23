# Sass_Grid
A Sass mixin that will create element sizes based off a 12 column grid. The mixin defaults to 6, which will set the element to 49% of its container. 

##Arguments
There are four arguments that you can pass. The first is a number between 1 and 12 that tells how many columns the element will occupy. The second argument is a boolean. If left out or set to true it will switch the width to 100% on screen sizes under 600px. The mixin also provides some margin to the top and bottom of the element to space it from other stacked grid columns. The third and fourth argument are only needed if the second argument is true. These arguments allow you to change the margin being set on both the stacked (3rd argument) and the side by side (4th argument).
