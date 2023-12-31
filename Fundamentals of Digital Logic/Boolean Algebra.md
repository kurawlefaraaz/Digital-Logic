# <center> Boolean Algebra</center>

 - Boolean Algebra was invented by George Boole in 1854.
 - It only uses binary numbers 0 and 1, which indicates low and high respectively.
 - Used to analyze and simplify Digital or Logic circuit.
 - Also known as Binary Algebra or Logical Algebra.
 - It is mathematics of digital logic. 

## Basic Operations
Boolean Expression:
: Boolean Expression is a combination of Boolean operators, constants and variables. <br>
example: `A + B`

Boolean Operator:
: Boolean Operators are operators which indicates use of some logical operation such as `AND`, `OR`, `NOT` etc.

Boolean Constants:
: Boolean Constants are values which would not change. Only two constants are present in Boolean Algebra that are 0 and 1.

Boolean Variable:
: A variable acts as a placeholder for values which may change in a given time. Boolean Variable can only store either of the value 0 or 1. <br>
example:  
`A=0`, `B=1`; putting that values in expression `A+B` would result in 1 by applying OR logic.

Some common boolean operator are:
 - OR/+
	 : This operation tells "atleast one variable should be high to get output as high else output is low".
	 - Example: `a=0`,`b=1`; `y=a+b` therfore `y=1` 

 - AND/.
	: This operation tells "All variable should be high to get output as high else output is low".
	 - Example: `a=1`,`b=1`; `y=a+b` therfore `y=0`

 - NOT/~/ ̅
   :	This operation inverts the input.
	 - Example: `a=0`; `y=~a` therefore `y=1`

## Boolean Algebra
Laws:

<table>
	<th>Law/Theorem</th>
	<th>Addition (OR)</th>
	<th>Multiplication (AND) </th>
	<th>Note</th>
	<tr>
		<td>Identity Law</td>
		<td> x + 0 = x
		<td>x . 1 = x</td>
		<td>Operation such that the value of variable is preserved.</td>
	</tr>
	<tr>
		<td>Complement Law</td>
		<td> x + x' = 1
		<td>x  .  x' = 0</td>
		<td>Operation with the complement of variable. </td>
	</tr>
	<tr>
		<td>Involution Law</td>
		<td colspan=2><center> (x')'</center></td>
		<td>Complement of complement is the number itself.</td>
	</tr>
	<tr>
		<td>Idempotent Law</td>
		<td> x + x = x</td>
		<td>x . x = x</td>
		<td>Operation with the variable or number it self.</td>
	</tr>
	<tr>
		<td>Dominant Law</td>
		<td> x + 1 = 1</td>
		<td>x . 0 = 0</td>
		<td>Operation of variable with constant where is result is same constant.</td>
	</tr>
	<tr>
		<td>Commutative Law</td>
		<td> x + y = y + x</td>
		<td>x . y = y . x</td>
		<td>Result would be same as arrangement order of values is not necessary to be same.</td>
	</tr>
	<tr>
		<td>Associative Law</td>
		<td> x + (y + z) = (x + y) + z</td>
		<td>x . (y . z) = (x . y) . z</td>
		<td>Even after grouping some variables the output is same.</td>
	</tr>
	<tr>
		<td>Distributive Law</td>
		<td> x . (y + z) = (x . y) + (x . z)</td>
		<td>x + (y . z) = (x + y) . (x + z)</td>
	</tr>
	<tr>
		<td>Demorgan's Law</td>
		<td>(x + y)' = x' . y'</td>
		<td>(x . y)' = x' + y'</td>
		<td>Inverse is applied to all elements of expression. Therefore even operators `+` is inverted to `.` and vice versa.
	</tr>
	<tr>
		<td>Absorption Law</td>
		<td>x + (x . y) = x</td>
		<td>x . (y + z) = x</td>
		<td>operation such that variable with in the expression is the result. By taking 'x' common, we get `x + (1 . y)` and by dominant law `1 . y = 1`, hence we say 'x' has absorbed 'y'</td>
	</tr>
	
</table>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MTEwNzk0NTYsMjU2NDcyNTM1LDEwNT
MyNTQ2ODAsLTE0NDU0Mzg5MDAsLTg3NzY3MDI2OCwtMTkzOTk3
OTk4MywxMTM3NzkwMjQxLDg1MDM1MTYwNCwtMTMzNzc5NzQxMF
19
-->