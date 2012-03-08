# Why Our Code Smells

Odors are communication devices. They exist for a reason and are usually trying to tell us something.

Our code smells and it is trying to tell us what is wrong. Does a test case require an abundance of setup? Maybe the code being tested is doing too much, or it is not isolated enough for the test? Does an object have an abundance of instance variables? Maybe it should be split into multiple objects? Is a view brittle? Maybe it is too tightly coupled to a model, or maybe the logic needs abstracted into an object that can be tested?

In this talk, I will walk through code from projects that I work on every day, looking for smells that indicate problems, understanding why it smells, what the smell is trying to tell us, and how to refactor it.
