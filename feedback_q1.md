In the class Tester, there are following issues in the functions: 

1. def iterative_mult(w) :
* Needs to be changed to def iterative_mult(self, w), and the class variable M needs to be accessed using self.M
* A matrix is stored in a "row-major" form, and w is a row vector itself, so in the code you are multiplying two rows together. In matrix multiplication, you need to multiply row by column.

2. def matrix_mult(w) :
* A self parameter needs to be added (similar to point 1). 
* np.sum(np.matmul(w, self.M)) works. The outer array is unnecessary (it still works because sum of elements does not change)

3. def comparison(w) :
* timeit.timeit("<function>(parameter)") doesn't seem to work for timing the code. 

  Plotting : not attempted
