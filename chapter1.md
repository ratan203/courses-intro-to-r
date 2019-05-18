---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

In the editor on the right you should type R code to solve the exercises. When you hit the 'Submit Answer' button, every line of code is interpreted and executed by R and you get a message whether or not your code was correct. The output of your R code is shown in the console in the lower right corner.

`@instructions`
In the editor on the right there is already some sample code. Can you see which lines are actual R code and which are comments?

`@hint`
Just add a line of R code that calculates the sum of 6 and 12, just like the example in the sample code!

`@pre_exercise_code`
```{r}
# Calculate 3 + 4
3 + 4

# Calculate 6 + 12
```

`@sample_code`
```{r}

```

`@solution`
```{r}
6+12
```

`@sct`
```{r}
check_result(18)
```
