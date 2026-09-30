# Loops in Python:

Loops in python are similar to loop in C, except python does not have a do while loop, but we can do a makeshift do while loop in python too.

## For Loop:

A loop which runs "FOR" a specific number of repetitions or iterations.

```
for (int i = 0; i < 10; i++) {
 printf("%d\n", i);
}
```
Or you can write it like this,

```
for i in range(3):
    print(i)
```
## While Loop:
 A loop which runs "WHILE" a certain condition is true, the number of iterations/repetitions aren't fixed, only the boundary condition.

```
i = 1
while i <= 3:
    print(i)
    i += 1

```
Now here we change the value of i same as in C.

## Do While Loop

A loop to "DO (something) WHILE" a certain condition is true, again the number of iterations/repetitions are not fixed. The difference is the fact that a 'Do While' loop runs the code first then checks the conditions and repeat. Which is the opposite of the 'While' loop.
You can say it assumes that the first/base condition is true by default. Since there is no built in Do While loop in python, we make it using While itself.

```
while True:
    # code
    if condition:
        break

```