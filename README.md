# The-Advance-Method--TAM-
 A method for solving Transportation Problem

The Advance Method Algorithm

Step 1: Select row/column index having minimum value in supply and demand as i (if it's row) or j (if it's column).
Step 2: Select index of minimum cost in row/column has minimum supply.or demand as i (if it's row) or j (if it's column)
Step 3: Let value = Xij.
Step 4:
	a. Subtract this value from supply si and demand dj.
	b. If the supply si is 0, then cross (strike) that row and If the demand dj is 0 then cross (strike) that column.
	c. If min unit cost cell is not unique, then select the cell where supply/demand has minimum value.
Step-5:	Repeact this steps for all uncrossed (unstriked) rows and columns until all supply and demand values are 0.
