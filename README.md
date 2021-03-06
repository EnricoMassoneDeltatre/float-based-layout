# Float based layout

This project is insprired by chapter four of the book [CSS in depth](https://www.manning.com/books/css-in-depth).  
This is both a way for me to fix the concepts illustrated there and an useful reference for anyone interested in learning CSS. 

The HTML page contained in this project illustrates the following topics: 
 
  - how to get a more predictable box model by using the *border-box* value for *box-sizing* property
  - how to vertically space items inside a container by using a minimal amount of code resilient to page changes with the so called *lobotomized owl selector*
  - how to center the page contents by using the *double container* pattern
  - how to build a float based layout by handling some quircks of floats such as the need for a *clearfix* container for the floated elements and the *float catching* (the behavior of the browser which wants to put any floated element as high as possible)
  - how to build a *media object* by using floats
  - how to establish a new *block formatting context* by using the declaration `overflow: auto;`

## How to run the sample page

Clone or download the repository and follow these steps: 

 - `cd float-based-layout`
 - `yarn install`
 - `yarn run start`
