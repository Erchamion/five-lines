# Chapter One - Discussion

## 1.0

* Book's focus is on refactoring.  Specifically how to perform safe refactoring when there are no tests.
* Testing in of itself is a complex topic and is not taught in this book.  Testing is still very important and is a skill that every developer should learn.
* Skills to recognize "code smells" comes with experience.  Learinging to recoginze the "smells" is a skill that anyone can learn.
* Red-Green-Refactoring is much more difficult in an existing legacy code base that has no testing.  Learning how to refactor safely to get the code into a state in which testing is feasible.

## 1.1 What is refactoring?

- [ ] Ask everyone what they think refactoring means

* Changing code without changing what it does.

- [ ] Ask everyone what are some reasons to refactor

* Making code faster
* Making code smaller
* Making code more general / resuable
* makding code easier to read / **maintain**

This book focuses on the human-readable and easy to maintain.

### Refactoring Definition

`Refactoring -- Changing code to make it more human readable and maintainable without changing what it does`

If you think about it a lot of our time is spent reading and trying to understand code.  Why not make it easy on ourselves.  Also changing something without first understanding it can cause trouble.

### [ ] - Arguments for refactoring

- [ ] Ask everyone what reasons do they think of when it comes to refactoring code?

* economic: easier to maintain allows addition of new features faster
* customer: fewer bugs, bugs are easier to fix
* Quality of Life: a more maintainable code base is more "fun" to work in

## 1.2 Skills: What to refactor?

* "Smells" are abstract and takes time for a developer to recognize them.
* This book uses a set of rules that allows a developer to learn quickly.
* Sometimes the rules make us refactor code that one could argue doesn't need refactoring
* Sometimes after following the rules there still may exist "smally" code
* Rules are not perfect - they are guidelines

## 1.2.1 Example Code Smell

- [ ] What is the code smell here?

It can mean many different things to different people.

## 1.2.2 Example rule

- [ ] A rule however is very concise and easily understood.

**Rule:**

`A method should never have more than five lines of code`

## 1.3 Culture: When to refactor?

`Refactoring is like taking a shower`

**--- Kent Beck**

- [ ] Ask everyone: When should you refactor?

* Make refactoring a part of your daily work

6 Step workflow to solve any programing task [Page 5]

- [ ] Notice how testing is usually part of the workflow.  This helps make refactoring a much safer process.  This book also explains how to refactor in a safe manner without tests.

- [ ] Figure 1.4 [Page 6] goes into the steps of refactoring and how the compiler can assist in safe refactoring

* Every rule has a few refactoring patterns linked with it, making it easy to know exactly how to fix a problem.
* Use the compiler to help make sure you don't introduce errors.

## 1.3.1 Refactoring a Legacy System

`First make the change, then make the easy change`

**--- Kent Beck**

- [ ] What do you think Kent Beck meant by this quote?

* Before making something new, start by refactoring, so it is easy to add our new code.
* Having all the ingredients laid out and pre-measured before you start baking.

## 1.3.2 When should you not refactor?

- [ ] What are some reasons in which you should not refactor code?

* Proof of concept code
* Code that is in maintenance mode and will soon be sunset.
* Code that has strict performance requirements

## 1.4 Tools: How to refactor (safely)

* Automated tests are great and we highly recommend testing your code!

```text
Automated testing is to software development what brake are to cars.  Cars don't have brakes because we want to go slowly -- they have brakes so we feel SAFE going fast
```

What tools can we use to help us safely refactor without tests?

1. Detailed, step-by-step, structured refactoring patterns
2. Version control
3. The compiler
4. Utilize your IDE refactoring tools
5. Make small changes with commits
6. Check that the compiler doesn't produce errors
7. Manually test that the application still works as intended

## 1.5 Tools you need to get started

Strongly Typed Object oriented language
Text editor
Version Control

## 1.5.1 Programming Language: TypeScript

Typescript is a strongly typed object oriented language.  Similar to Java, C#, C++, and JavaScript.

## 1.5.2 Editor: Visual Studio Code

lightweight opensource editor created by Microsoft.  Supports typescript.

## 1.5.3 Version control: Git

We will be using git hub as our SCM of choice.

you can clone the bookclub version of this project using the following git command:

`git clone https://github.com/Erchamion/five-lines.git`

## 1.6 How will we learn all this cool refactoring!

We will learn by refactoring a 2D puzzle game!

## 1.6.1 Practice makes perfect: A second codebase

We will not be doing this in bookclub but feel free to do this on your own.

[second codebase](https://github.com/thedrlambda/bomb-guy)

## 1.7

* Re-iterate the focus of this book is to introduce refactoring.
* You should be writing tests in production systems.
* This is a safe way to learn refactoring WITHOUT the overhead of learning how to test at the same time.

## Summary

- [ ] How would we like to approach this topic
- [ ] Do we want to code together and go over the material at the sametime?
- [ ] Do we want to go over the material first then answer any questions or help anyone who still has questions?
- [ ] Setup evnironments
