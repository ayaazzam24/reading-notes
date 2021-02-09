# links :
Links are created using the < a> element. Users can click on anything
between the opening < a> tag and the closing </ a> tag. You specify
which page you want to link to using the href attribute .

![image](https://www.computerhope.com/jargon/h/html-tag.gif)

## Email Links :
> mailto: To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the < a>
element.

![image](https://i0.wp.com/digitalfortress.tech/wp-content/uploads/2018/05/mail-to.png?resize=672%2C377&ssl=1)

## Opening Links in a New Window :
> target
If you want a link to open in a
new window, you can use the
target attribute on the opening
< a> tag. The value of this
attribute should be _blank

![image](http://4.bp.blogspot.com/_VZprIDHV4-Q/TO7FNQjuWNI/AAAAAAAACKU/M1BY2_VkE5s/s1600/2.png)

## Linking to a Specific Part of the Same Page :
> You do this using the id attribute (which
can be used on every HTML
element) , The value of the id attribute
should start with a letter or an
underscore (not a number or
any other character) and, on a
single page, no two id attributes
should have the same value , To link to an element that uses
an id attribute you use the <a>
element again, but the value of
the href attribute starts with
the # symbol, followed by the
value of the id attribute of the
element you want to link to. In
for example, < a href = "#bottem"> .

# layout :
## Building Blocks :
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box. 
> Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text .

##  positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. 

# WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements).

> function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[ 0];
var volumeOne = getSize (3, 2, 3)[ 1];


