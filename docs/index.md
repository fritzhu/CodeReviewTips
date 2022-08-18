# fritzhu's Code Review Hints, Tips, Tricks and Whatnots

This is a collection of thoughts and reasons behind common code review questions and feedback. It will change over time.

## Common themes

### We write code for us, not the machine.

If we were coding for the computer only, we'd all be coding in Assembly; we actually write code for each other, so we can collaborate on projects, avoid silos of knowledge, and so on.

For this reason, it's best to write your code to be an easy read. Any dev should be able to understand it. Pay attention to spacing, readability, comments where needed but not where they are not, and avoid clever algorithms that are hard to read.

Extract simple statements from complicated ones into other variables, constants or functions, to simplify the complicated statements.
