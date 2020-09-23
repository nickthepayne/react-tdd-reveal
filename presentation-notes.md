# Invitation

# Preparation

- Start presentation
- Have Editor ready (disable prettier?)
- Start application

# Talk

## Introduction to TDD

- Slides

Changes:

### What is TDD?

Mention the three rules:

1. Write production code only to pass a failing unit test.
1. Write no more of a unit test than sufficient to fail (compilation failures are failures).
1. Write no more production code than necessary to pass the one failing unit test.

### Benefit

CURRENT:
Drive design
Frequent and safe refactorings
Be confident that your code works
Your brain's reward system is continuously pleased!

CONSIDER:
Clean code that works
Stops writing what we dont need
Short feedback cycle
Smaller pieces
Less debugging
Refactor with confidence

-> change silde to:

Your brain's reward system is continuously pleased!
  Short feedback cycle
  Smaller pieces

Clean code that works
  Refactor with confidence

Drive design

Stops writing what we dont need
Less debugging


## Testing React

Mention Storyboard

## Hands On

### Goal

Show application "react-tdd-code"

Changes: show titles

### What's the first, simplest test case?

### Start coding

Challenges:
- how fine grainded?
- when to extract components?
- 

## Discussion

## But wait, what about Redux

Redux examples:
- connected 
- container component

## Impact on your work

- I have spent more time writing tests than implementing the feature.
- A big part was understanding it, especially in the beginning. Typically the framework is optimized for fast development. Testing comes on top and you have to understand what's going on

i.e.
- when to await, when not (animations)
- library (how does it render)

## Impact to test suite

- more tests
- more like system tests (also due to testing-library)

## Impact on team

- you are the slow one (applies always when you are the one caring for clean code, tests, ...)
- 

## Is there a situation where not to use TDD

- POC (make it a throw away POC!)
- non-productive stuff, elaboration etc.

## What about the promises

Yes
- Be confident that your code works
- Less debugging

Well...
- Fast feedback / continous reward
  - test suite grows fast, takes a lot of time to execute
  - having a test suite of the stuff you are woking on now is cumbersome
- Frequent and safe refactorings
 - still needs discipline