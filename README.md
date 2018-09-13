
# Lambda Functions 

## Objectives

* Implement lambda function to solve quadratic equation with given parameters
* Implement a temperature converter as lambda function that converts between Celsius and Fahrenheit with some text processing to show units. 
* Process text to calculate the length of each word in a sentence. 

In this lab, we shall apply the skills in the lambda functions lesson into some data analyses contexts. 

### Exercise 1 - Quadratic Equation

Let's create a lambda function that takes in the parameters for calculating the quadratic equation. The formula for quadratic equation is :
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/Quadratic_formula.svg/800px-Quadratic_formula.svg.png)

The function will take in a, b, c values and return the positive and negative factors as a tuple. 


```python
import math

quad_eq = None
```


```python
# Uncomment and run the following line of code 

# quad_eq(100,45,2), quad_eq(100, 41, 2), quad_eq(100, 41, 4)

## ((-0.05, -0.4), (-0.0565917792034417, -0.3534082207965583), (-0.16, -0.25))
```

### Exercise 2  - Temperature Conversion

Write a lambda function that takes two arguments: a number to represent temperature value and `F` or `C` to show whether the temperature is in Fahrenheit of Celsius. 

The function should calculate and return Celsius if the temperature was originally in Fahrenheit and vice versa. Also append the `F` or `C` to the answer to show current units. Here are the required formulas:
![](http://www.101computing.net/wp/wp-content/uploads/fahrenheit_to_celsius_formulas.png)


```python
convert_temp = None
```

Uncomment and run the following:


```python
# convert_temp(32,'F') # '0.0 C'
```


```python
# convert_temp(-17.77,'C') # '0.013 F'
```


```python
# convert_temp(100,'C') # '212.0 F'
```


```python
# convert_temp(100,'X') # 'Invalid'
```

### Exercise 3 - Basic NLP

Take the sentence "The quick brown fox jumps over the lazy dog" , and using `map` and `lambda` functions calculate the length of each word in the sentence. i.e. 

```python
['The', 'quick', 'brown', 'fox', 'jumps', 'over', 'the', 'lazy', 'dog']
Output:
[3, 5, 5, 3, 5, 4, 3, 4, 3]
```

Hint: You will need the `split()` function to split the sentence 


```python
sentence = "The quick brown fox jumps over the lazy dog"
lengths = None
lengths

# [3, 5, 5, 3, 5, 4, 3, 4, 3]
```

## Summary

In this lab we applied labda function in a variatey of contexts as alternative to creating custom for loops. In the following lab, we shall practice more lambda functions in conjunction with `map` and `filter` functions. Happy coding.  
