#Project Overview: CSS Display Exercise
This project is a hands-on exercise designed to demonstrate the fundamental differences between block-level and inline-level elements using the CSS display property. By manipulating only this property, you can control the layout and positioning of the colored squares.

#Learning Objectives
1.Understand the default behavior of <p> (block-level) elements.

2.Master the use of inline-block to align elements horizontally.

3.Practice switching between layout styles using CSS without altering HTML structure.

#Instructions
The goal is to arrange three colored squares (Red, Green, and Blue) into specific layouts by modifying the .red, .green, and .blue classes in the <style> section.

#Goal 1: Horizontal Alignment
To make all three squares line up horizontally (side-by-side), set the display property to inline-block.

#Code Configuration:

#CSS

.red, .green, .blue {
  display: inline-block;
}
#Goal 2: Vertical Alignment
To make all three squares stack vertically (one on top of the other), set the display property to block. Since <p> tags are block-level by default, this will return them to their natural flow.

#Code Configuration:

#CSS

.red, .green, .blue {
  display: block;
}
