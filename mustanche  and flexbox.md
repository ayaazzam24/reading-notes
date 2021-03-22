# Javascript Templating

* Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source.

# Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.

* mustache.js is an implementation of the mustache template system in JavaScript.

# Flexbox properties
![](https://www.ostraining.com/cdn/images/webdesign/flexbox-intro/190618_flexbox_intro_004.png)


1. Display 

- This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

1. flex-direction

- stablishes the main-axis, thus defining the direction flex items are placed in the flex container

1. flex-flow

- This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

1. justify-content

- flex-start (default): items are packed toward the start of the flex-direction.

 - flex-end: items are packed toward the end of the flex-direction.
 - start: items are packed toward the start of the writing-mode direction.
 - end: items are packed toward the end of the writing-mode direction.
 - left: items are packed toward left edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like start.

 - right: items are packed toward right edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like end.

 - center: items are centered along the line

- space-between: items are evenly distributed in the line; first item is on the start line, last item on the end line

- space-around: items are evenly distributed in the line with equal space around them. 

- space-evenly: items are distributed so that the spacing between any two items (and the space to the edges) is equal.

1. align-items

 - stretch (default): stretch to fill the container (still respect min-width/max-width)

 - flex-start / start / self-start: items are placed at the start of the cross axis. The difference between these is subtle, and is about respecting the flex-direction rules or the writing-mode rules.

 - flex-end / end / self-end: items are placed at the end of the cross axis. The difference again is subtle and is about respecting flex-direction rules vs. writing-mode rules.

 - center: items are centered in the cross-axis

 - baseline: items are aligned such as their baselines align

 1. align-content 

 - normal (default): items are packed in their default position as if no value was set.

- flex-start / start: items packed to the start of the container. The (more supported) flex-start honors the flex-direction while start honors the writing-mode direction.

- flex-end / end: items packed to the end of the container. The (more support) flex-end honors the flex-direction while end honors the writing-mode direction.

- center: items centered in the container

- space-between: items evenly distributed; the first line is at the start of the container while the last one is at the end

- space-around: items evenly distributed with equal space around each line

- space-evenly: items are evenly distributed with equal space around them

- stretch: lines stretch to take up the remaining space

