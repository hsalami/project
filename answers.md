# Answers to questions

## developer-tools

## python-1

## python-2


## py-programming-1

1. What steps should you take when developing modules locally to be able to import those modules across different files?
   - Add the path to your code directory to your `$PYTHONPATH`.
   - Include a blank `__init__.py` file inside each folder within your code directory.

2. Which of the following lines of codes given below is the function docstring? 
   ```python 
      def quad(num): 
       '''Returns the square of num''' 
       num_quad = num ** 2  
       return num_quad
    ```
   - `'''Returns the square of num'''`

3. Identify the following keywords that are used to create a loop in Python?
   - while
   - for

4. Which of the following is the best practice for installing new libraries for your miniconda/anaconda python distribution?
   - Use `conda install` if you can, otherwise use `pip install` in a virtual environment

5. You have a module `punctuation.py` that lives in a folder `text_lib`. Which of the following are valid ways to import the punctuation module? Check all that apply.
   - `from text_lib import punctuation`
   - `import text_lib.punctuation`
   - `import text_lib.punctuation as punc`

## py-programming-2

1. Designing a class in Python can best be described as:
   - specifying a blueprint to create an object

2. The correct way to instantiate the Pen object defined below, is: 
   ```python
   python class Pen: 
      def __init__(self, type, color):
          self.type = type 
          self.color = color
   ```
   - `Pen('ballpoint', 'blue')`

3. In Python a characteristic of an object is known as a/an _, and a function that acts on an object is known as a/an _.
   - attribute, method

4. What is the result of the following code snippet? 
   ```python 
      class Person: 
          def __init__(self, id): 
            self.id = id 
            id = 100 
      bob = Person(9) 
      print(bob.id)
   ```
   - 9

5. Which statements about the following code snippet are correct? Check all that apply. 
    ```python 
       class Product: 
          def init(self, in_stock = True): 
             self.in_stock = in_stock
      
      class Pen(Product): 
         def init(self, color = 'blue'): 
            self.color = color
      
      red_pen = Pen('red') 
      print(red_pen.color) 
      print(red_pen.in_stock) 
      ```
   

   - This code generates an error.
   - The Pen class inherits from Product, but the attribute in_stock is not automatically inherited.
     
## py-numeric-computing
1. Which of the following numpy expressions would give you a column vector? Check all that apply
   - numpy.arange(10).reshape(-1, 1)
   - numpy.array([[1], [2], [3], [4]])
   - numpy.random.random((30, 1))


2. Which syntax would produce an array, arr, of random numbers between 0 and 1 from a uniform distribution, of shape (2,3)? Select all that apply.
   - arr = np.random.random((2,3))
   - arr = np.random.rand(2,3)


3. Which of the following correctly describe the differences between the `arange` and `linspace` functions for array generation in numpy?
   - `arange` can be called with as little as one argument, the stop argument, while `linspace` requires a start and stop argument.
   - The endpoints are exclusive for `arange` but inclusive for `linspace`.
    

4. Which of the following commands can take a two-dimensional array e.g. `arr = np.array([[0, 1, 2, 3], [4, 5, 6, 7]])` 
and produce an array containing the sum of the elements in each column, `array([ 4, 6, 8, 10])`?
   - `arr.sum(axis=0)`
   - `np.sum(arr, axis=0)`


5. Which of the following will subtract 2 from each element of two-dimensional array `arr = np.array([[0, 1], [4, 5]])` and yield array `[[-2 -1], [ 2 3]]`?
   - `np.subtract(arr, 2)
   - `arr - 2`
