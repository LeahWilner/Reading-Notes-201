# Class 7

## Domain Modeling

Explain why we need domain modeling.  
It models a specific problema nd validates and verifies your understanfing of that problem

## HTML Table Basics

Why should tables not be used for page layouts?  
Tables are not accessible for sight-impaired humans, they create 'tag soup' which is messy and difficult to update the code and debug, and they are not used in modern responsive web design  

List and describe 3 different semantic HTML elements used in an HTML <table>.  
th-table header, td-table data, tr-table row

## Introducing Constructors

What is a constructor and what are some advantages to using it?  
A constructor is a function for creating new objects, it is advantageous if you need more than one of an object so you don't have to manually rewrite the object each time
How does the term this differ when used in an object literal versus when used in a constructor?  
In contructors you bind 'this' to the new object ex: this.name so you can run the same code with multiple inputs for name, it is not as useful in object literals since it refers to only the name in the object 

## Object Prototypes Using A Constructor

Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question  
One of my previous job functions was inventory management. One of the ways I became really good at this was comapring my sales data to company wide data. Now there are regional and demographic factors that play a part, but typically if there was a product that was fast-selling company wide and wasn't moving in my location there was likely some sort of issue. When looking at company wide sales data, I wasn't looking up one item and checking sales figures for each individual location and adding it all up, that would take days. I think this is how constructors and prototypes work.
