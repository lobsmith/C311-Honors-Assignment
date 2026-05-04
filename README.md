# C311-Honors-Assignment
**Objective:** Write grammar for a simple programming language using Python syntax.

## How to Test in BNF Playground
 * Write a simple Python program
 * Transpose the code into a single line in BNF playground and test against `<program>`
 * Remove all whitespace
 * Bookend curly braces to conditional blocks for ease of testing
### Testable Cases
 * Printing terms and expressions without quotes (`int`, `string`)
 * Variable assignments
 * Conditional statements (`if`, `else`)
 * Arithmetic expressions

## Code Example
### Original Code (see test.py)
```
x = 10
y = 3
z = x + y * 2

print(z)

if (z > 15):
    print(z)
else:
    print(x)

i = 5

while (i > 0):
    print(i)
    i = i - 1

a = -5
b = a * (x + y)

print(b)

if (b != 0):
    print(b)
```
### Conversion to BNF Playground (more testable, less readable)
```
(* Test is confirmed to be successful as written below *)
x=10y=3z=x+y*2print(z)if(z>15):{print(z)}else:{print(x)}i=5while(i>0):{print(i)i=i-1}a=-5b=a*(x+y)print(b)if(b!=0):{print(b)}
```
