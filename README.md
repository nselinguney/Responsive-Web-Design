# Responsive-Web-Design
##### CSS stands for Cascading Style Sheet. It is a language used to give styling and design to websites. It is usually goes hand-in-hand with HTML, while CSS3(the latest version) brings lots of new features to the table.
## Why use CSS? 
There are many reasons to use CSS, such as;
* Styling
* Layout & Design 
* Animations 
* Font Changes
* Organization
* Grid Systems
## CSS Selectors
### What is a selector?
Selectors are ways of gabbing and manipulating HTML.
There are many different ways to select, however they all turno ut the same way.
Different selectors have different applications.
#### Selectors: The Element Selector
You can select entire elements without any special characters.
This applies to all of the elements with that tag on the page.
It ranks on the bottom of the specificity scale.

#### Selectors: The Class Selector
This is used to select elements with a certain class name.
Can be used on any and all elements with that class.
Can be used multiple times, and is select with the . symbol.

#### Selectors: The ID Selector
This is used to select elements with a certain ID name.
Can be used on any and all elements with that ID.
Unlike classes, it can only be used on one element at a time, and is selected with the # symbol. However, it is possible to use more than once.

> selector {
	property : value;
	property2: value2;
}

### CSS : The Box Model
The Css Box Model is a series of positioning properties designed to help with layout.
Each property Works in a different way, and positions the item with different spacing.
The Box Model is the most commonly used way to position items.

#### The Model
This is what the model looks like.
Each layer represents a different part of the model.
Each layer can be stretched and sized either symmetrically or asymmetrically.

##### Padding
Padding represents the space between the content and the border.

##### Border
The border is the divider between the padding and margin.
It can be styled using a CSS property called ‘border’.

##### Margin
The margin is the space between the border and all other content.

### CSS : Flexbox
Flexbox stands for ‘flexible box’.
It is a display type that comes with a range of properties allowing you to arrange items easily.
It is an alternative to using displays, floats, and other layout properties.

#### Flexbox Components
A Flexbox element is split into two main parts: the container, and the items.
The container is the parent element in which the display type is active. This is usually in the form of a div.
Flex items are child elements of the container, and make up the contents of the box.

#### Grid vs Flexbox
Similar to Flexbox, Grid is a display type that can be used to activate certain layout features on a container element.
They are both alternatives to other layout features available in CSS.

#### Differences
The Grid system is more manual, providing you with more tools to layout your container in a specific way.
Grid is also very focused on providing tools for both dimensions(width + height), whereas Flexbox is focused on width alone.
