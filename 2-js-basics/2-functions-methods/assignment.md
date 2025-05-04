# Fun with Functions

## Instructions

Create different functions, both functions that return something and functions that don't return anything.

See if you can create a function that has a mix of parameters and parameters with default values.
```
function doubleAndBack(num) {
  return ((num * 2) - 1);
}

function sayHi() {
  console.log("Hi");
}

function greetName(sayHi, name='Bob') {
  sayHi();
  console.log(name);
}
```
## Rubric

| Criteria | Exemplary                                                                              | Adequate                                                         | Needs Improvement |
| -------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------- |
|          | Solution is offered with two or more well-performing functions with diverse parameters | Working solution is offered with one function and few parameters | Solution has bugs |
