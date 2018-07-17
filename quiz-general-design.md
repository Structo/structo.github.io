# Generalist Software Engineer Quiz

This quiz aims to test your ability to come up with innovative solutions to problems. The following task should take no longer than 45 minutes.

## Task 1

Structo 3D printers are IoT (Internet of Things) devices. The printers come with an on-board computer which runs a customized stripped-down version of Ubuntu. Design a system which would allow the printer to manage software updates. Assume that an API endpoint is available which will return any information you would need regarding the update e.g. download link to binaries, older version information etc. Address the following in your solution:

- What info would you expect the API to provide
- How would the binaries be downloaded and handled at the printer
- How would download interruptions be handled
- How would corrupted update files be detected and handled
- How would you store old update files in the printer and allow switching to an older version

Notes:
- You do not need to code anything
- System architecture diagram is preferred
- Name any frameworks/libraries/tools that you would use to implement the design

## Task 2

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
