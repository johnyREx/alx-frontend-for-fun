Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

What is Flexbox?
How to convert float positioning to a flex display
How to horizontally and vertically align elements using Flexbox
The difference between the main and cross axes
Properties that work on flex elements vs flex container
Shorthands for flex
How to create a new page with flex in mind

learning outcome (what i learnt after using the material and external sources incl. CHATGPT)

What is Flexbox?

Flexbox, short for Flexible Box Layout, is a CSS layout module that provides a more efficient way to design and align items within a container, especially when the size of items is unknown or dynamic. It allows you to distribute space among items in a container and align them in multiple ways.
How to convert float positioning to a flex display

Flexbox provides a more robust and flexible alternative to traditional CSS float-based layouts. To convert float positioning to a flex display, you would replace float properties with flexbox properties, such as display: flex;, flex-direction, justify-content, and align-items.
How to horizontally and vertically align elements using Flexbox

Flexbox offers several properties for aligning items both horizontally and vertically within a container. These include justify-content for horizontal alignment and align-items for vertical alignment. Additionally, align-self can be used to override the alignment for individual items.
The difference between the main and cross axes

In Flexbox, the main axis is the primary axis along which flex items are laid out within the flex container. The direction of the main axis is determined by the flex-direction property. The cross axis is perpendicular to the main axis. Understanding these axes is crucial for properly aligning and arranging items in a flex layout.
Properties that work on flex elements vs flex container

Flex properties can be applied to both flex containers and flex items. Properties like display, flex-direction, justify-content, align-items, and align-self are applied to the flex container, while properties like flex-grow, flex-shrink, flex-basis, and order are applied to flex items within the container.
Shorthands for flex

Flexbox offers shorthand properties to set multiple flex-related properties at once, such as flex (for flex-grow, flex-shrink, and flex-basis), align-items, and justify-content.
How to create a new page with flex in mind

When creating a new page with Flexbox in mind, you should start by structuring the layout with containers and items in a way that takes advantage of Flexbox's capabilities for flexible and responsive design. This includes defining the main and cross axes, setting alignment properties, and utilizing flex properties to control item behavior.