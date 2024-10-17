# Mitra_Aditya_002303254_Assignment6_INFO6150-16308-Web-Design

Book review Library

This website is a Book review library where I have given suggestions on three books to read this fall that I have enjoyed. A little summary and genre is provided for the user. This can be transformed in Book Club where anyone can jump into it and give their suggestions and add to it.

The SASS/SCSS features used in this assignment.


Variables:

Defined using $, e.g., $genres, $border-radius.


Nesting:

CSS selectors are nested within each other, making the styles more readable.


Mixins:


Usage of "@include" for including predefined styles, e.g., @include border-radius($border-radius).


Extend/Inherit:



The use of "%grid-flex-item" with @extend to share styles among multiple selectors.


Functions:



Custom function defined using @function, e.g., darken-color($color, $amount).


Loops:



@each loop to iterate over the $genres array and dynamically create class names.


Interpolation:



The use of #{} to interpolate the genre names into class names, e.g., .grid-item-#{ $genre }.


CSS Custom Properties (Variables):



The use of var(--primary-color) for CSS variables defined in :root.
