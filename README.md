# Angular Study Guide

## What is a directive?
Directives are classes that add additional behavior to elements in a Angular applications. Different types of Angular directives are:

### Components
Used with a template. This type of directive is the most common directive type. Components are the main building block for Angular applications. Each component consists of:
 
An HTML template that declares what renders on the page.
A Typescript class that defines behavior
A CSS selector that defines how the component is used in a template.


### Attribute directives - Change the appearance or behaviror of an element, component, or another directive.
  NgClass - Adds and removes a set of CSS classes.
  NgStyle - Adds and removes a set of HTML styles.
  NgModel - Adds two-way data binding to an HTML form element.
  
### Structural directive - Change the DOM layout by additing and removign DOM elements.
  NgIf - Conditionally creates or disposes of subvies from the template.
  NgFor - Repeat a node for each item in a list.
  NgSwitch - A set of directives that switch among alternative views.

## Angular Template Form

Data Binding
a) NgForm - is used to get reference to local form template variable. Once "FormsModule" is imported, this directive becomes active by default on all "<form>" tags. 
  
b) NgModel - directive is used to display a data property and update that property when the user makes changes.


What is the difference between Promises and RxJS?
  a) Promises are always async. They return 1 value. Need to call the then() method.
  b) RxJS may be async. Stream of 0 or more values. We call the subscribe() method.
      obs.subscribe (value => {
        // do something with the value
}
  
