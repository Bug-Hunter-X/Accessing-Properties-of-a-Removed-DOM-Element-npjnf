# Accessing Properties of a Removed DOM Element
This repository demonstrates an uncommon bug in HTML/JavaScript where attempting to access properties of a DOM element after it has been removed from the DOM results in an error. 
The bug occurs because the element is logically deleted and an attempt to access its property will result in an error. 
The solution involves checking if the element exists before attempting to access its properties, or using a different approach that avoids directly referencing the removed element. 