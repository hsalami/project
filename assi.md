<!-- #region -->
## Part 1:  Basic Data Structures

1. Make the following vectors in numpy:
  
    <a href="https://www.codecogs.com/eqnedit.php?latex=v_1&space;=&space;\begin{bmatrix}&space;2&space;\\\&space;4&space;\\\&space;6&space;\end{bmatrix}&space;\text{&space;and&space;}&space;v_2&space;=&space;\begin{bmatrix}&space;10&space;\\&space;20&space;\\&space;30&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_1&space;=&space;\begin{bmatrix}&space;2&space;\\\&space;4&space;\\\&space;6&space;\end{bmatrix}&space;\text{&space;and&space;}&space;v_2&space;=&space;\begin{bmatrix}&space;10&space;\\&space;20&space;\\&space;30&space;\end{bmatrix}" title="v_1 = \begin{bmatrix} 2 \\\ 4 \\\ 6 \end{bmatrix} \text{ and } v_2 = \begin{bmatrix} 10 \\ 20 \\ 30 \end{bmatrix}" /></a>

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

1. Use numpy to form a matrix <a href="https://www.codecogs.com/eqnedit.php?latex=X" target="_blank"><img src="https://latex.codecogs.com/gif.latex?X" title="X" /></a> as follows:

   <a href="https://www.codecogs.com/eqnedit.php?latex=\begin{aligned}&space;X&space;=&space;\begin{pmatrix}&space;0&space;&&space;1&space;&&space;2&space;&&space;3&space;\\&space;4&space;&&space;5&space;&&space;6&space;&&space;7&space;\\&space;8&space;&&space;9&space;&&space;10&space;&&space;11&space;\end{pmatrix}&space;\end{aligned}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{aligned}&space;X&space;=&space;\begin{pmatrix}&space;0&space;&&space;1&space;&&space;2&space;&&space;3&space;\\&space;4&space;&&space;5&space;&&space;6&space;&&space;7&space;\\&space;8&space;&&space;9&space;&&space;10&space;&&space;11&space;\end{pmatrix}&space;\end{aligned}" title="\begin{aligned} X = \begin{pmatrix} 0 & 1 & 2 & 3 \\ 4 & 5 & 6 & 7 \\ 8 & 9 & 10 & 11 \end{pmatrix} \end{aligned}" /></a>
    
  
   
2. Complete the following questions about ${X}$ and ${X}^\top$.

    * is ${X} - {X}^\top$ defined? If it is defined, compute it.
    * is ${X}^\top {X}^\top$ defined? If it is defined, compute it.
    * is ${X} {X}^\top$ defined? If it is defined, compute it.
    * is ${X}^\top {X} $ defined? If it is defined, compute it.
    * is ${X} {X}^\top$ identical to ${X}^\top {X}$?
    * is ${X} {X}^\top$- ${X}^\top {X}$ defined? If it is defined, compute it.

   
   &nbsp;
   
2. Find a 3x3 matrix ${Y}$ such that ${Y}^\top {Y}$ - ${Y} {Y}^\top$ = 0.
   Demonstrate that ${Y}^\top {Y}$ - ${Y} {Y}^\top$ = 0 is true for your chosen matrix.
   
   &nbsp;
   

3. Find the inverse of the following matrix:

    \begin{aligned}
    A = 
    \begin{pmatrix}
    7 & -2 \\\
    -6 & 2 
    \end{pmatrix}
    \end{aligned}
    
    &nbsp;
   

4. Find the inverse of $AB$ given $A$ and $B$ below:

    $$A = 
    \begin{pmatrix}
    7 & -2 \\
    -6 & 2 
    \end{pmatrix}
    \text{ and }
     B =
     \begin{pmatrix}
      2 & 3 \\
      4 & -4 
      \end{pmatrix}
    $$
    
    &nbsp;
   

5. Is the determinant of ${X}$ defined? Why or why not?
    \begin{aligned}
    X =
    \begin{pmatrix}
    0 & 1 & 2 & 3 \\
    4 & 5 & 6 & 7 \\
    8 & 9 & 10 & 11
    \end{pmatrix}
    \end{aligned}
    
    &nbsp;
   
   
6. Find `det(A)` (rounded to the nearest 0.001) for 

    \begin{aligned}
    A = 
    \begin{pmatrix}
    10 & 0 & -3 \\
    -2 & -4 & 1 \\
    3 & 0 & 2
    \end{pmatrix}
    \end{aligned}
    
    &nbsp;
   


7. Find `det(AB)` given $A$ and $B$ (round to the nearest 0.001)

    $$
    A = 
    \begin{pmatrix}
    8 & 9 \\
    5 & -1 
    \end{pmatrix}
    \text{ and }
    B = 
    \begin{pmatrix}
    -2 & 3 \\
    4 & 0
    \end{pmatrix}
    $$
    
    &nbsp;
   

8. Find `det(AB)` given $A$ and $B$ (round to the nearest 0.001)

    $$
    A = 
    \begin{pmatrix}
    -1 & -4 & -3 & 0 \\
    6 & 3 & 1 & 4 \\
    2 & -2 & 5 & 7 \\
    8 & 9 & 10 & 11 
    \end{pmatrix}
    \text{ and }
    B = 
    \begin{pmatrix}
    12 & 13 & -4 & 14 \\
    6 & -1 & 15 & 0 \\
    -3 & -2 & 1 & 2 \\
    7 & 5 & 3 & 4
    \end{pmatrix}
    $$


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

1. Find the dot product of $v$ with itself, i.e. ${v}^\top {v}$


2. Find  ${v}^\top  {z}$


3. Find ${C} {B}$


4. Find ${D} {A}$


5. Find $2{C}^2$


6. Find the sum of the diagonal elements of ${C}$


7. Find the transpose of ${D}$


8. Find the transpose of ${C}$


9. Find the transpose of ${B}$


10. Given that  

    \begin{aligned}
    B = 
    \begin{pmatrix}
    10 & 20 \\
    30 & 40 \\
    50 & 60
    \end{pmatrix}
    \end{aligned}
    
    Recall that `np.sum(B, axis=0) = [90, 120]` and `np.sum(B, axis=1) = [30, 70, 110]`.
  
    
   * Can you compute each of these two summations using only np.einsum?
    
   * Given the definitions of F and G, can you figure out how to multiply them in such a way so that the result is a 5x2 matrix?
<!-- #endregion -->

```python

```
