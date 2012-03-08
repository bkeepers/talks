# JavaScript Application Architecture

JavaScript often does not receive the same level of respect from developers that other languages are afforded. We spend our days crafting well-designed and tested code, and then turn around and spew a few hundred lines of spaghetti JavaScript into a file, click test it and ship it.

This framework agnostic talk takes a serious look at how we design JavaScript applications. Despite its prototypical nature, good object-oriented programming principles are still relevant. The design patterns that we've grown to know and love work just as well in JavaScript as they do any other language. Test driven development forces us to write modular, decoupled code.

Let's finally give JavaScript the respect it deserves.

## Outline

1. OOP + Prototype
2. MVC
    a. Model
        1. If you have data, you need a model
        2. If you have logic, you need a model
    b. Controller
        1. shouldn't be attached to the DOM
        2. should be non-destructive
    c. View
        1. rendering: client vs server
        2. templating
        3. presenters
3. …

## Submitted To

* [BackboneConf 2012](http://backboneconf.com/)
* [jsday 2012](http://2012.jsday.it/)
