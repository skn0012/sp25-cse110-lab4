## Part 2

# Questions

1. When getting num1 and num2, instead of getting an integer, the function is getting a string.
2. To fix the bug, I would add Number() to num1 and num2 so it becomes let num1 = Number(document.getElementById("num1").value); and let num2 = Number(document.getElementById("num2").value); so the printSum function gets a number rather than a string.
