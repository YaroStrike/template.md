# Practical work No. 101 #

### Topic: example of working with an MD file ###

### Goal: learn how to mark up an MD file ###

#### Progress ####

##### Task: #####

> Create an algorithm that raises a number to the 10th power.

##### Test case: #####

> I enter the number 2, I get the result 1024.

> I enter a number in and the result is 0.

> I enter the number 2 and get the result 1024.

##### System analysis: #####

> Input data: int x`

> Intermediate data: int i

> Output: int result

##### Block diagram: #####

![Block diagram](block.png)

##### Program code: #####
```python
x = int(input('Enter a number: '))

result = 1

for i in range(10):

result = x

print (f'Result: (result)')
```
##### Result of the program: #####

* Enter the number `2`

![Screen_1](screen1.png)

* Enter the number `0`

![Screen_2](screen2.png)

* Enter the number `-2`

![Screen_3](screen3.png)

##### Conclusion on the work done: #####

> But you could just do it like that -  `result = x ** 10`
