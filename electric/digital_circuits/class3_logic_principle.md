# Logic-Principles

- 由truth table得到逻辑表达式

1相加(SOP)，0相乘(POS)



### Boolean Algebra Theorems

![Screen Shot 2022-10-19 at 19.21.46](img/Screen%20Shot%202022-10-19%20at%2019.21.46.png)

![Screen Shot 2022-10-19 at 19.24.23](img/Screen%20Shot%202022-10-19%20at%2019.24.23.png)

![Screen Shot 2022-10-19 at 19.29.50](img/Screen%20Shot%202022-10-19%20at%2019.29.50.png)



- $X + \bar{X} Y = X + Y$

- Duality 对偶特性

The dual of a logic expression is obtained by swapping 0 and 1, and • and +.

## K-map

binary sequence of  abc follows <font color='red'>**Gray code**</font>

![Screen Shot 2022-10-12 at 09.21.45](img/Screen%20Shot%202022-10-12%20at%2009.21.45.png)

- Each implicant is a **product** term of the function

- implicants (蕴含项)

  - **Prime Implicants**: a group that covers the maximum possible number of adjacent squares.![Screen Shot 2022-10-12 at 09.08.10](img/Screen%20Shot%202022-10-12%20at%2009.08.10.png)

  - **Essential Prime Implicants**: a prime implicant that ==covers a minterm== which is not covered by any other prime implicants![Screen Shot 2022-10-12 at 09.07.28](img/Screen%20Shot%202022-10-12%20at%2009.07.28.png)

### Minimized Logic Fucntions

#### K-map for Sums of Product

**All** essential prime implicants + other **needed** prime implicants

![Screen Shot 2022-10-12 at 09.16.12](img/Screen%20Shot%202022-10-12%20at%2009.16.12.png)

![Screen Shot 2022-10-12 at 09.33.03](img/Screen%20Shot%202022-10-12%20at%2009.33.03.png)



#### K-map for Product of Sums

![Screen Shot 2022-10-12 at 09.32.26](img/Screen%20Shot%202022-10-12%20at%2009.32.26.png)

#### K-map for XOR and XNOR

![Screen Shot 2022-10-12 at 09.39.38](img/Screen%20Shot%202022-10-12%20at%2009.39.38.png)![Screen Shot 2022-10-12 at 09.39.26]()

![Screen Shot 2022-10-12 at 09.39.49](img/Screen%20Shot%202022-10-12%20at%2009.39.49.png)



#### Odd and Even Functions

- In general, for an n-variable Odd Function, the function is 1 if there are odd number of variables having logic 1

​	e.g. **XOR**

- For an n-variable Even Function, the function is 1 if there are even number of variables having logic 1

​	e.g. **XNOR**

#### DON'T-CARE Conditions

![Screen Shot 2022-10-12 at 09.45.28](img/Screen%20Shot%202022-10-12%20at%2009.45.28.png)

![Screen Shot 2022-10-12 at 09.48.26](img/Screen%20Shot%202022-10-12%20at%2009.48.26.png)

#### 5-variable K-map

![Screen Shot 2022-10-12 at 10.13.29](img/Screen%20Shot%202022-10-12%20at%2010.13.29.png)

![Screen Shot 2022-10-12 at 10.13.45](img/Screen%20Shot%202022-10-12%20at%2010.13.45.png)





 
