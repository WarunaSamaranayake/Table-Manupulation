# Table-Manupulation
Answer for ACM NATIONAL SCOLOSTIC PROGRAMMING CONTEST

	This problem is an exercise in organization a one-dimensional list of numbers into a 2-dimesnional table with a 
variable number of columns. The number must be organized into a table which reads by columns, left to right.
The lengths of the columns should be balanced so that all rows except the last are filled. The empty spaces in the
last row should be at the right end of the row.

EXMAPLE:
LIST:		1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17
COLUMNS:	5
TABLE:		1	5	9 	12 	15
		2	6	10 	13 	16
		3	7	11	14	17
		4	8

Write program to read a collection of records (< 10,000) each with a positive integer in columns 1-5.
A zero value terminates the list. A value for C, the number of columns, in columns 1-5. After each value of C is read,
the sum of the elements in each row of the table should be computed and printed. Sums will be less than 9 digits.
The 2-dimensional table itself should not be printed.

Using the sample data shown above for various values of C, output similar to the following should be produced:
	C	ROW	SUMS
	5	42	47	52	12
	**************************************************************************
	1	153
	**************************************************************************
	2	11	13	15	17	19	21	23	25	9
	**************************************************************************
 
Ethical vertical or horizonta printing of row sums is acceptable, but a line of asterisks should separate output generated for different values of C.
A zero values for C should cause the program to terminate.