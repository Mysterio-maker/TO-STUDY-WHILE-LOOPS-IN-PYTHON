# TO-STUDY-WHILE-LOOPS-IN-PYTHON





# EXPERIMENT NO: 7

# TITLE: Study of While Loops in Python

**Name:** Amey Waghmare
**PRN:** 25070123009
**Batch:** A1

---

# AIM

To study and implement looping constructs in Python, especially the `while` loop, along with `for` loop, nested loops, break, continue statements, and pattern-based programs.

---

#  THEORY 

##  Introduction to Loops

In programming, loops are used to execute a block of code repeatedly until a certain condition is satisfied. Loops help in reducing repetition and making programs efficient.

Python mainly provides two types of loops:

1. `while` loop
2. `for` loop

---

#  While Loop

A `while` loop executes a block of code as long as the given condition is True.

It is generally used when:

* The number of iterations is not fixed.
* Execution depends on a condition.
* User input controls the loop.

---

##  Working of While Loop

1. Condition is checked.
2. If condition is True → loop body executes.
3. Control goes back to condition.
4. Loop stops when condition becomes False.

Example:

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

This prints numbers from 1 to 5.

---

##  Infinite Loop

If the condition never becomes False, the loop runs forever.
Example:

```python
while True:
    print("Infinite")
```

To stop such loops, `break` statement is used.

---

#  Break Statement

The `break` statement immediately terminates the loop.

Example:

```python
if i == 3:
    break
```

---

#  Continue Statement

The `continue` statement skips the current iteration and moves to the next iteration.

Example:

```python
if i == 5:
    continue
```

---

#  For Loop

A `for` loop is used when the number of iterations is known in advance.

Example:

```python
for i in range(1,6):
    print(i)
```

---

# Nested Loops

When one loop is placed inside another loop, it is called a nested loop.

Used in:

* Matrix operations
* Pattern printing
* Combination problems

Example:

```python
for i in range(3):
    for j in range(3):
        print(i, j)
```

---

#  Applications Implemented in This Experiment

This experiment includes:

* Printing numbers
* Factorial calculation
* Fibonacci series
* Reversing a number
* Checking palindrome (number & string)
* Searching element in list
* Matrix multiplication
* Armstrong number
* Prime numbers
* Pattern printing
* Pyramid structures
* Number patterns

These programs demonstrate how loops are used in mathematical and logical problems.

---

#  SYNTAX

##  While Loop

```python
while condition:
    statement
```

---

##  While Loop with Increment

```python
i = start
while condition:
    statement
    i += 1
```

---

##  Break Statement

```python
while condition:
    if condition:
        break
```

---

##  Continue Statement

```python
while condition:
    if condition:
        continue
```

---

##  For Loop

```python
for variable in range(start, stop, step):
    statement
```

---

##  Nested For Loop

```python
for i in range(n):
    for j in range(m):
        statement
```

---

#  Matrix Multiplication Logic

Matrix multiplication uses three nested loops:

```python
for i in range(3):
    for j in range(3):
        for k in range(3):
            Result[i][j] += A[i][k] * B[k][j]
```

Where:

* `i` → row index
* `j` → column index
* `k` → multiplication index

---

#  Pattern Printing Logic

Patterns are created using:

* Outer loop → rows
* Inner loop → columns
* Spaces and symbols for formatting

Example:

```python
for i in range(n):
    print((n - i) * ' ', i * ' $')
```


#  CONCLUSION

In this experiment, looping constructs in Python were successfully studied and implemented.

We learned:

* How while loop works
* How to use break and continue
* Difference between for and while loops
* How nested loops work
* Applications like factorial, Fibonacci, prime numbers
* Pattern and matrix operations

This experiment strengthened logical thinking and improved understanding of iterative control structures in Python.



