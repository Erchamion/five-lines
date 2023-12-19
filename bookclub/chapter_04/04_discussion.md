# Chapter Four

## This chapter covers

- Eliminate early binding
- Removing if statements
- Removing bad generalization
- Preventing coupling
- Removing methods

At the end of Chapter 3 we had created the handleInput function.  This function is in violation of rule `five lines of code`.

```ts
function handleInput(input: Input) {
  if (input === Input.LEFT) moveHorizontal(-1);
  else if (input === Input.RIGHT) moveHorizontal(1);
  else if (input === Input.UP) moveVertical(-1);
  else if (input === Input.DOWN) moveVertical(1);
}
```

## 4.1 Refactoring a simple if statement

We are stuck!  We need a new rule!

### 4.1.1 Rule: Never use if with else

#### STATEMENT

Never use **if** with **else**, unlese we are checking against a data type we do not control.

#### EXplanation

`if-else`s are hardcoded decisions.  We call this early binding.


