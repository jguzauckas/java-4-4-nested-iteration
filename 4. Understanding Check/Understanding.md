# Understanding Check

Recall the `factorial` method we created in Unit 4 Section 2. A factorial takes an input number and multiplies it by every number less than it (for example `factorial(5)` is `5 * 4 * 3 * 2 * 1` which is equal to `120`).

Use nested loops to calculate the factorial of the numbers 1 to 9 and print them out as nice statements. Your output should look like this:

```
1 = 1
2 * 1 = 2
3 * 2 * 1 = 6
4 * 3 * 2 * 1 = 24
5 * 4 * 3 * 2 * 1 = 120
6 * 5 * 4 * 3 * 2 * 1 = 720
7 * 6 * 5 * 4 * 3 * 2 * 1 = 5040
8 * 7 * 6 * 5 * 4 * 3 * 2 * 1 = 40320
9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1 = 362880
```

Your outer loop will count through 1 through 9 and your inner loop with go through each number for the given factorial (that is, it will be based on the outer loop number).

**This is a hard problem!**

Once you have gotten to just warnings, save the Java file and commit and push your changes via GitHub Desktop.
