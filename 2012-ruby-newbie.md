# 9 things Every Ruby Newbie Should Know

[Slides](http://speakerdeck.com/u/bkeepers/p/9-things-every-ruby-newbie-should-know)

## Outline:

1. Learn the Ruby way
2. Truthiness
3. Conventions
    1. ClassNames
    2. method_names and variable_names
    3. question?
    4. dangerous!
    5. file_names.rb
    6. Class#notation
    7. SOME_CONSTANT or SomeConstant
    8. 2 spaces
    9. Variable names: @, @@, $
4. Everything is an object - everything that can be assigned to a variable
    1. Classes are objects
    2. No primitives
    3. nil
5. Almost Everything is a message
    1. no overloading
    2. instance/class methods
    3. operators are syntactic sugar
    4. raise/throw
6. Strong dynamic typing
    1. Duck typing
7. Mix-Ins
8. Enclosures: Blocks and Procs
9. Ruby is loose
    1. public/private is a suggestion
    2. variable constants
    3. open classes
    4. parenthesis/semicolons are optional
    5. {} in method calls
10. Multiple Rubies
    1. MRI
    2. Rubinius
    3. jruby
    4. …
11. Rails extends Ruby
12. almost everything returns a value
13. symbols
14. Docs
15. Write less code
16. Ruby is Dynamic
    1. method_missing
    2. reflection
    3. code evaluation

## Notes

http://onestepback.org/articles/10things/

what are its primary assumptions
Comparisons with other languages
what makes it beautiful
why people fall in love with it, etc.

http://ruby-doc.org/docs/Newcomers/ruby.html

* Arguments to methods (i.e. functions) are passed by reference, not by value.
* All variables live on the heap. Further, you don’t need to free them yourself—the garbage collector takes care of that.
* More often than not, everything is an expression (that is, things like while statements actually evaluate to an rvalue).

## Talk Given At
* [Grand Rapids Ruby Group](http://www.meetup.com/mi-ruby/events/43627642/)

## Submitted To
