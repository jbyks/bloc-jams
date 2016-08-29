# Explain the difference between absolute and relative positioning.

In HTML, how an element behaves is dependent on the viewport and other elements. 

The default behavior is called the "normal flow". Every element acts as a box. There are two types of elements: block and inline. Inline elements only take as much space as they need. Block elements take up as much space as they can within the viewport, only constrained by their styles and other elements. Each element is positioned on a new line.

You can alter the default behavior by defining an element's position with the "position" styles: static (default), relative, absolute, fixed or inherit.

Relative positioning allows you to define the position of the element relative to its box' boundaries. By defining space at the top, right, bottom, left of the element, the element is shifted but still upholds the normal flow. The space you create cannot be filled by other elements.

Absolute positioning allows you to break an element from the normal flow and define its position solely relative to the viewport. It may cover or flow under other elements because it sticks to its position. 

# Explain how box-sizing: border-box treats contained content differently than the default browser box-sizing.

The size of the box is made up of the content, padding, border and margin. When you change padding, border or margin you are changing the size of the box ie. you are changing the height and width of the box. box-sizing: border-box changes this behavior and will keep the height and width while changing the content.