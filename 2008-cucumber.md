# Behavior Driven Development with Cucumber

[Slides](http://www.slideshare.net/bkeepers/behavior-driven-development-with-cucumber-presentation)

    Feature: Cucumber
      In order to share the love
      As a presenter
      I will demonstrate the wonders of behavior driven development with Cucumber

      Scenario: Behavior Driven Development with Cucumber
        Given a desire for higher quality software
        And a tool called Cucumber that executes feature document written in plain text
        When you watch this presentation
        Then you will gain an understanding of behavior driven development
        And see examples of behavior driven development with cucumber
        And be equipped start integrating Cucumber into your development process

## Notes

Cucumber is a tool that executes feature documentation written in plain text. While Cucumber can be thought of as a “testing” tool, the intent of the tool is to support Behavior Driven Development (BDD). The “tests” (plain text feature descriptions with scenarios) are typically written before anything else, and the production code is then written outside-in, to make them pass.

### "Given a desire for higher quality software"

There are a lot of metrics that could be used to define "quality" software: cleanliness of code, number of features, speed, flexibility, "enterprisiness". All of which are fine measures, but today, when I talk about quality, I mean two things:

1. The software meets the requirements of the people it is written for as defined by the stakeholders.

While this seems obvious, anyone that done software development knows that understanding the needs and requirements is possibly the most difficult part of our job. The biggest barrier to discovering and understanding requirements is language. Developers speak one language, domain experts speak their own language, and end-users speak yet another language.

User stories are a way of capturing descriptions of the system in language that domain experts, stakeholders, developers and customers all understand.

2. The software works, as expected.

### Behavior-Driven Development

Behavior-Driven Development (BDD) is an evolution in the thinking behind Test Driven Development.

1. Verify: writing unit tests around existing code as a way of "verifying" what the code does
2. Confidence: body of tests increase, begin to enjoy a strongly increased sense of confidence in their work
3. Design: tests help to guide the design process, defining the API and helping to focus on only writing code that is needed (TDD)
4. Expertise in TDD begins to dawn at the point where the developer realizes that TDD is about defining behavior rather than testing.

By writing tests in advance of code, the developer defines the behavioral intent of the system.

It must be stressed that BDD is a rephrasing of existing good practice, it is not a radically new departure. Its aim is to bring together existing, well-established techniques under a common banner and with a consistent and unambiguous terminology. BDD is very much focused on “Getting the words right” and this focus is intended to produce a vocabulary that is accurate, accessible, descriptive and consistent.

It aims to help focus development on the delivery of prioritized, verifiable business value by providing a common vocabulary that spans the divide between Business and Technology.

### Getting Started

When you are ready to add a new feature or fix a bug, start by writing a new feature or scenario that describes how the feature should work. Don’t write any code (yet).

Run the features. The one you wrote should have yellow, pending steps – or failing, red ones. (If you don’t get that you’re doing something wrong, or the feature is already implemented).

This is when you start writing code. Start by writing a couple of lines of code to address the failure you got from Cucumber. Run cucumber again. Repeat and rinse until you’re happy with your feature. When you get down to nitty gritty details, drop down one abstraction level and use RSpec to write some specs for your classes. Write the specs first! If you follow this process you have a good guard against brittle, unmaintainable, undocumented code that nobody understands. (Yes, stories and specs are documentation too).

If you think this sounds annoying, try it out anyway. You’ll end up writing better, lesser coupled (and less) code this way. Trust me. Work outside-in (the outside being the feature, the inside being the low level code). Do it the BDD way.

## Bio

Saved from the brink of “Enterprise” Java despair, Brandon drank the Ruby kool-aid.  He's contributed a fair amount to the open-source Ruby world and has led Ruby and Rails training around the world. At Collective Idea, an agile software development shop, he writes code that tends toward awesomeness and occasionally talks about it at opensoul.org.


## Talk Given At

* Great Lakes Ruby Bash 2008