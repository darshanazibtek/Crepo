---
title: 'Module: Getting Started'
description: ""
free_preview: true
---

## "Hello, World! "

```yaml
type: NormalExercise
key: 8cf9d041c2
xp: 100
```

Almost any programming course you ever take will start with a very simple "Hello, World!" exercise. The goal is to get the program to write the words "Hello, World!" somewhere -- usually to the console or screen. As you are a burgeoning R programmer, it seems appropriate for you to write a simple R program that will print "Hello, World!" to the console as your first programming assignment.

`@instructions`
- Type the `print()` function into the R script to the right.
- Type the words ``"Hello, World!"`` inside the parentheses of the `print()` function. Another way you would commonly here programmers phrase this is by say, "pass 'Hello, World!' as an argument to the `print()` function." We'll learn more about functions and programming jargon throughout the course.
- Make sure you don't forget the quotation marks around Hello, World! It doesn't matter if they are single or double quotes -- as long as they match.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Type the print() function below and pass it the character string "Hello, World!"

```

`@solution`
```{r}
print("Hello, World!")
```

`@sct`
```{r}
ex() %>% check_output("[H|h]ello,? [W|w]orld!?")
success_msg("Well, hello to you too! You just completed your first programming assignment!")
```
