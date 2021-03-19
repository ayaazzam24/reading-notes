# Responsive vs. Adaptive vs. Mobile


Responsive and adaptive web design are closely related, and often transposed as one in the same. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. With responsive design websites continually and fluidly change based on different factors, such as viewport width, while adaptive websites are built to a group of preset factors. A combination of the two is ideal, providing the perfect formula for functional websites. Which term is used specifically doesn’t make a huge difference.

Mobile, on the other hand, generally means to build a separate website commonly on a new domain solely for mobile users. While this does occasionally have its place, it normally isn’t a great idea. Mobile websites can be extremely light but they do come with the dependencies of a new code base and browser sniffing, all of which can become an obstacle for both developers and users.

Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.

## Flexible Layouts
Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media. The first part, flexible layouts, is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

## CSS Viewport Rule
Since the viewport meta tag revolves so heavily around setting the styles of how a website should be rendered it has been recommend to move the viewport from a meta tag with HTML to an @ rule within CSS. This helps keep the style separated from content, providing a more semantic approach.

Currently some browsers have already implemented the @viewport rule, however support isn’t great across the board. The previously recommended viewport meta tag would look like the following @viewport rule in CSS.

![image](https://learn.shayhowe.com/assets/images/courses/advanced-html-css/responsive-web-design/with-viewport.png)


# What is “Float”?
![image](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/web-text-wrap.png?resize=540%2C270&ssl=1)

> Clearing the Float :
An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.