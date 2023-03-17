# Topic - Created a Maggic Magic website using various SCSS features.

## 1 Functions -  
Functions enable the creation of elaborate actions on SassScript values, which can be reused in the entire stylesheet. An instance of a function has been established to modify the color of the text in accordance with the background color.
The fuctions are demonstarted in _functions.scss.

## 2 Variables - 
Variables provide a means to assign a value to a name and then use that name throughout the program instead of repeatedly referring to the value. Certain variables are designated for holding color values.
Several variables have been used in the _variables.scss.

## 3 Nesting -
With Sass, you can arrange your CSS selectors in a manner that mirrors the visual structure of your HTML, known as nesting. Nesting has been utilized in various places, such as the about section.
Refer to style.scss for samples.

## 4 Mixins -
The use of mixins enables the creation of style definitions that can be reused multiple times within a stylesheet. In this particular task, a mixin named "graph-text" has been utilized to modify the text format of the 'p' tag in the about, menu, and contact sections.
The Mixins are demonstrated in _mixins.scss

## 5 Interpolation -
In a Sass stylesheet, interpolation has a versatile application and can be utilized to insert the output of a SassScript expression into a segment of CSS. We applied this technique specifically to the text-decoration property, which is extensive and used in various locations.
Just wraping an expression in #{} in any place.
The Mixins are demonstrated in style.scss

## 6 Flexbox Layout -
Flexbox was created to arrange elements in a single direction. Some examples of where flexbox has been employed include organizing icons in the "about" section and the "navigation" section.
Check in style.scss

## 7 Grid Layout -
The grid was created to enable the organization of elements in a two-dimensional format, which involves arranging them into both rows and columns simultaneously.
Few places where grid has been used are for contact, menu section.
Check in style.scss

## 8 Placeholder Selectors - 
The symbol % is used at the beginning of a code that behaves similarly to a class selector, but it is not displayed in the CSS output.
We used it for changing font-size.
Check in _placeholder.scss

## 9 Custom Properties -
Custom properties consist of elements such as color, among others.
Check in style.scss
