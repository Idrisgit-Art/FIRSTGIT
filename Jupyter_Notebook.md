<center>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Module2/images/SN_web_lightmode.png" width="300" alt="cognitiveclass.ai logo">
</center>


#### Add your code below following the instructions given in the course



```python
"hello world"
```




    'hello world'




```python
a = 10
b = 20
sum_ab = a + b
print(f"The sum of {a} and{b} is {sum_ab}")
```

    The sum of 10 and20 is 30



```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
even_numbers = [num for num in numbers if num % 2 == 0]
print(even_numbers)
```

    [2, 4, 6, 8, 10]



```python
class Rectangle:
    def __init__(self, width, height):
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.height

    def perimeter(self):
        return 2 * (self.width + self.height)

rect = Rectangle(5, 3)
print(rect.area())
print(rect.perimeter())
```

    15
    16



```python

```
