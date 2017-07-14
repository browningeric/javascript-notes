# http://rachelnabors.com/javascript-for-designers/
Reasons to learn JS:
    • Empowerment
    • Understanding
    • Vocabulary

*ECMAScript is Javascript, just a standardized format.*

## Objects:
- Everything is an object.
- Objects are collections of things, called properties.
- Primitive Values are the simplest forms of information an object can represent.
- Primitives are not objects, they are values (i.e. just a number)

=== ? == has type coercion, which leads to confusing results, has negative counterpart !== vs !=

Global object: god of objects; in a browser, the window is global object (aka head object or host object)

## Functions:
- When a function is a property of an object, it’s called a method.
- **Q. Creating a function via regular statement vs expression?**
- Stuff inside parentheses = arguments for function.
- **Q. return - stops function? weird**
- **Q. .constructor? What is its purpose?**

## DOM:
- In browser, global object window always has a document node

——————

# http://betaflows.com/#get-started

- console.log! - like an alert but just sends stuff to console (viewable via inspector)
- .select and .focus properties for inputs (neat)

## Javascript templating & loops
- take some html content, use "type='text/html' in script tag"
- templating code from John Resig, simple but works, much lighter than bringing in Handlebars or something
- for loop syntax, for ( var i = 0; i < 15; i++ ) {}
- use 'append()' (jquery) to add templated item to instances inside a list or whatever; works, but is slow because constantly painting DOM with new things
- += operator, start with initial, add something to end

## Click events & classes
- .on (jquery function, pass argument like 'click')
- addClass & removeClass
- stringing together variables in one 'var' statement is possible, use commas and keep semicolon at end
- $(this) - whatever element the click event (etc) is attached to

## Mock data
- to create variable, always start with 'var', can assign anything, ie string, number, array, object '{}' etc
- objects: like an array of key : value pairs

## Random numbers
- to make color more dynamic/random

