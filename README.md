# Lambda Functions - Python
![image](https://user-images.githubusercontent.com/84158231/203089233-08d733a1-4843-45b9-be51-ef3be5817447.png)

These are my notes of lambda functions in Python. I have seen this function beeing used in different algorithms, so I have dicided to understand it. 

## Why to use

We can define functions in Python using the way
 ```
 def pitagoras(x,y):
    return x**2 + y**2
 
 ```
Using lambda functions we can define functions indirectaly and use them inside another functions. We can make the same function using less words.

```
pitagoras = lambda x,y: x**2 + y**2
```

## _map_

When we are working with data structures and we have to make operations over the values of theses structures, we can do it using for loop or while loops. The _map_ built-in function can do this process in a more stylish way. 
We can use lambda functions in this process. For exemple, we have a list with number from 0 to 100. We need to iterate over theses numbers making them double itself. We could do it using for loop.

```
numbers = [0,1,2,3......100]
for i in range(len(numbers)):
    numbers[i] *= 2

```
Using map function we can do it better

```
numbers = list(map(lambda x: x*2, numbers))

```
