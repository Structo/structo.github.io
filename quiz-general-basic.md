# General Software Quiz

This is a basic quiz to to assess your familiarity with the technology stack we're using. If you are familiar with the tech stack, this should only take 10-30 minutes of your time. If not familiar, it could take longer.

---

### Question One

Suppose a variable x can have only three possible different values a, b and c, and you wish to assign to x the value other than its current one, and you wish your code to be independent of the values of a, b and c.

What is the most efficient way to cycle among three values? Write a function f so that it satisfies

  f(a) = b
  f(b) = c
  f(c) = a

EXAMPLE

  f( 3, a = 3, b = 4, c = 5 ) => 4

---

### Question Two

Consider the following pseudocode:
1. input n
2. if n = 1 then STOP
4. if n is odd then n = 3n + 1
5. else n = n/2
6. GOTO 2

Given the input 5, the following sequence of numbers will be printed: 

```
5 16 8 4 2 1
```

In the example above, the integer 5 has a *chain-length* of 6.

In this task, you are required to write a function which takes *i* and *j* as input and returns the maximum chain-length for integers between and including *i* and *j*.

You can use following to test your function:

| i   | j   | Chain-Length |
| ----|:---:| ------------:|
| 1   | 10  |      20      |
| 100 | 200 |      125     |
| 201 | 210 |      89      |
