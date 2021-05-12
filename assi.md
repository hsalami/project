<!-- #region -->
## Part 1:  Basic Data Structures

1. Make the following vectors in numpy:
   
   <img src="https://latex.codecogs.com/svg.latex?v_1&space;=&space;\begin{bmatrix}&space;2&space;\\\&space;4&space;\\\&space;6&space;\end{bmatrix}&space;\text{&space;and&space;}&space;v_2&space;=&space;\begin{bmatrix}&space;10&space;\\&space;20&space;\\&space;30&space;\end{bmatrix}" title="v_1 = \begin{bmatrix} 2 \\\ 4 \\\ 6 \end{bmatrix} \text{ and } v_2 = \begin{bmatrix} 10 \\ 20 \\ 30 \end{bmatrix}" />
    

2. Make the following matrices in numpy:
    * a 2x3 matrix populated with random numbers in the range -4 to 4 with `dtype = int64`
    * a 3x2 matrix populated with random numbers in the range -4 to 4 with `dtype = float32`
    * a 3x3 matrix populated with the numbers 0 to 8 with `dtype = float64`
    * a 2x10 matrix populated with the numbers 0 to 19 with `dtype = int64`


3. Make the following tensors in numpy:
    * Tensor with dimensions 3x4x2 populated with random numbers in the range -4 to 4 (any dtype)
    * Tensor with dimensions 2x3x4 populated with random numbers in the range -10 to 10 (any dtype)
    * Tensor with dimensions 5x4x3x2 populated with random numbers in the range -10 to 10 (any dtype)
    * Tensor with dimensions 2x4x3x5 populated with random numbers in the range -10 to 10 (any dtype)


## Part 2: Matrix Operations

1. Use numpy to form a matrix <img src="https://latex.codecogs.com/svg.latex?X" title="X" /> as follows:

   <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;X&space;=&space;\begin{pmatrix}&space;0&space;&&space;1&space;&&space;2&space;&&space;3&space;\\&space;4&space;&&space;5&space;&&space;6&space;&&space;7&space;\\&space;8&space;&&space;9&space;&&space;10&space;&&space;11&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} X = \begin{pmatrix} 0 & 1 & 2 & 3 \\ 4 & 5 & 6 & 7 \\ 8 & 9 & 10 & 11 \end{pmatrix} \end{aligned}" />
    
  
   
2. Complete the following questions about <img src="https://latex.codecogs.com/svg.latex?X" title="X" /> and <img src="https://latex.codecogs.com/svg.latex?{X}^\top" title="{X}^\top" />.

    * is <img src="https://latex.codecogs.com/svg.latex?{X}-{X}^\top" title="{X}-{X}^\top" /> defined? If it is defined, compute it.
    * is <img src="https://latex.codecogs.com/svg.latex?{X}^\top{X}^\top" title="{X}^\top{X}^\top" /> defined? If it is defined, compute it.
    * is <img src="https://latex.codecogs.com/svg.latex?{X}{X}^\top" title="{X}{X}^\top" /> defined? If it is defined, compute it.
    * is <img src="https://latex.codecogs.com/svg.latex?{X}^\top{X}" title="{X}^\top{X}" /> defined? If it is defined, compute it.
    * is <img src="https://latex.codecogs.com/svg.latex?{X}{X}^\top" title="{X}{X}^\top" /> identical to <img src="https://latex.codecogs.com/svg.latex?{X}^\top{X}" title="{X}^\top{X}" />?
    * is <img src="https://latex.codecogs.com/svg.latex?{X}{X}^\top-{X}^\top{X}" title="{X}{X}^\top-{X}^\top{X}" /> defined? If it is defined, compute it.

   
   
   
2. Find a 3x3 matrix <img src="https://latex.codecogs.com/svg.latex?Y" title="Y" /> such that <img src="https://latex.codecogs.com/svg.latex?{Y}^\top{Y}-{Y}{Y}^\top" title="{Y}^\top{Y}-{Y}{Y}^\top" /> = 0.
   
   Demonstrate that <img src="https://latex.codecogs.com/svg.latex?{Y}^\top{Y}-{Y}{Y}^\top" title="{Y}^\top{Y}-{Y}{Y}^\top" /> = 0  is true for your chosen matrix.
   
  
   

3. Find the inverse of the following matrix:

    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;A&space;=&space;\begin{pmatrix}&space;7&space;&&space;-2&space;\\\&space;-6&space;&&space;2&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} A = \begin{pmatrix} 7 & -2 \\\ -6 & 2 \end{pmatrix} \end{aligned}" />
    
    
   

4. Find the inverse of  <img src="https://latex.codecogs.com/svg.latex?AB" title="AB" /> given <img src="https://latex.codecogs.com/svg.latex?A" title="A" /> and  <img src="https://latex.codecogs.com/svg.latex?B" title="B" /> below:

   <img src="https://latex.codecogs.com/svg.latex?A&space;=&space;\begin{pmatrix}&space;7&space;&&space;-2&space;\\&space;-6&space;&&space;2&space;\end{pmatrix}&space;\text{&space;and&space;}&space;B&space;=&space;\begin{pmatrix}&space;2&space;&&space;3&space;\\&space;4&space;&&space;-4&space;\end{pmatrix}" title="A = \begin{pmatrix} 7 & -2 \\ -6 & 2 \end{pmatrix} \text{ and } B = \begin{pmatrix} 2 & 3 \\ 4 & -4 \end{pmatrix}" />
   

5. Is the determinant of <img src="https://latex.codecogs.com/svg.latex?X" title="X" /> defined? Why or why not?
    
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;X&space;=&space;\begin{pmatrix}&space;0&space;&&space;1&space;&&space;2&space;&&space;3&space;\\&space;4&space;&&space;5&space;&&space;6&space;&&space;7&space;\\&space;8&space;&&space;9&space;&&space;10&space;&&space;11&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} X = \begin{pmatrix} 0 & 1 & 2 & 3 \\ 4 & 5 & 6 & 7 \\ 8 & 9 & 10 & 11 \end{pmatrix} \end{aligned}" />
    
    
   
   
6. Find `det(A)` (rounded to the nearest 0.001) for: 
   
   <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;A&space;=&space;\begin{pmatrix}&space;10&space;&&space;0&space;&&space;-3&space;\\&space;-2&space;&&space;-4&space;&&space;1&space;\\&space;3&space;&&space;0&space;&&space;2&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} A = \begin{pmatrix} 10 & 0 & -3 \\ -2 & -4 & 1 \\ 3 & 0 & 2 \end{pmatrix} \end{aligned}" />
   


7. Find `det(AB)` given  <img src="https://latex.codecogs.com/svg.latex?A" title="A" /> and  <img src="https://latex.codecogs.com/svg.latex?B" title="B" /> (round to the nearest 0.001):
   
   <img src="https://latex.codecogs.com/svg.latex?A&space;=&space;\begin{pmatrix}&space;8&space;&&space;9&space;\\&space;5&space;&&space;-1&space;\end{pmatrix}&space;\text{&space;and&space;}&space;B&space;=&space;\begin{pmatrix}&space;-2&space;&&space;3&space;\\&space;4&space;&&space;0&space;\end{pmatrix}" title="A = \begin{pmatrix} 8 & 9 \\ 5 & -1 \end{pmatrix} \text{ and } B = \begin{pmatrix} -2 & 3 \\ 4 & 0 \end{pmatrix}" />
    
  
   

8. Find `det(AB)` given  <img src="https://latex.codecogs.com/svg.latex?A" title="A" /> and  <img src="https://latex.codecogs.com/svg.latex?B" title="B" /> (round to the nearest 0.001):

   <img src="https://latex.codecogs.com/svg.latex?A&space;=&space;\begin{pmatrix}&space;-1&space;&&space;-4&space;&&space;-3&space;&&space;0&space;\\&space;6&space;&&space;3&space;&&space;1&space;&&space;4&space;\\&space;2&space;&&space;-2&space;&&space;5&space;&&space;7&space;\\&space;8&space;&&space;9&space;&&space;10&space;&&space;11&space;\end{pmatrix}&space;\text{&space;and&space;}&space;B&space;=&space;\begin{pmatrix}&space;12&space;&&space;13&space;&&space;-4&space;&&space;14&space;\\&space;6&space;&&space;-1&space;&&space;15&space;&&space;0&space;\\&space;-3&space;&&space;-2&space;&&space;1&space;&&space;2&space;\\&space;7&space;&&space;5&space;&&space;3&space;&&space;4&space;\end{pmatrix}" title="A = \begin{pmatrix} -1 & -4 & -3 & 0 \\ 6 & 3 & 1 & 4 \\ 2 & -2 & 5 & 7 \\ 8 & 9 & 10 & 11 \end{pmatrix} \text{ and } B = \begin{pmatrix} 12 & 13 & -4 & 14 \\ 6 & -1 & 15 & 0 \\ -3 & -2 & 1 & 2 \\ 7 & 5 & 3 & 4 \end{pmatrix}" />


## Part 3: Extra Credit 

Solve the remaining problems using [np.einsum](https://numpy.org/doc/stable/reference/generated/numpy.einsum) and the following definitions:

```python
    v = np.array([2,4,6])
    z = np.array([10,20,30])
    A = np.array([[1,2,3], [4,5,6]])
    B = np.array([[10,20], [30,40], [50,60]])
    C = np.array([[1,2,3], [4,5,6], [7,8,9]])
    D = np.array([[1,2], [3,4]])
    F = np.arange(60.).reshape(3,4,5)
    G = np.arange(24.).reshape(4,3,2)
```

1. Find the dot product of <img src="https://latex.codecogs.com/svg.latex?v" title="v" /> with itself, i.e. <img src="https://latex.codecogs.com/svg.latex?v\cdot&space;v" title="v\cdot v" />


2. Find  <img src="https://latex.codecogs.com/svg.latex?v\cdot&space;z" title="v\cdot z" />


3. Find <img src="https://latex.codecogs.com/svg.latex?CB" title="CB" />


4. Find <img src="https://latex.codecogs.com/svg.latex?DA" title="DA" />


5. Find <img src="https://latex.codecogs.com/svg.latex?2{C}^2" title="2{C}^2" />


6. Find the sum of the diagonal elements of <img src="https://latex.codecogs.com/svg.latex?C" title="C" />


7. Find the transpose of <img src="https://latex.codecogs.com/svg.latex?D" title="D" />


8. Find the transpose of <img src="https://latex.codecogs.com/svg.latex?C" title="C" />


9. Find the transpose of <img src="https://latex.codecogs.com/svg.latex?B" title="B" />


10. Given that  

    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;B&space;=&space;\begin{pmatrix}&space;10&space;&&space;20&space;\\&space;30&space;&&space;40&space;\\&space;50&space;&&space;60&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} B = \begin{pmatrix} 10 & 20 \\ 30 & 40 \\ 50 & 60 \end{pmatrix} \end{aligned}" />
    
    Recall that `np.sum(B, axis=0) = [90, 120]` and `np.sum(B, axis=1) = [30, 70, 110]`.
  
    
    * Can you compute each of these two summations using only np.einsum?
    
    * Given the definitions of F and G, can you figure out how to multiply them in such a way so that the result is a 5x2 matrix?
`
