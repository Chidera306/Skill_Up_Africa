# ARRAY OF  INTEGERS
0   1   2   3   4   5  [index]
8	2	5	4	1	3

Array of integers = 8,  2,  5,  4,  1,  3
To sort these arrays in increasing order using bubble sort algorithm
•	 Scan array from left to right
•	If items are out of order we swap them
•	Start off by comparing items in the index 0 and 1
•	If the right item is smaller than the left item,  swap them because we want to sort this array in ascending order.


0   1   2   3   4   5 [index]

8	2	5	4	1	3
Here 2 (index 1) is smaller than 8(index 0), we swap them

0   1   2   3   4   5
2	8	5	4	1	3
Here 5 (index 2) is smaller than 8(index 1), we swap them

0   1   2   3   4   5 [index]
2	5	8	4	1	3
Here 4 (index 3) is smaller than 8(index 2), we swap them


0   1   2   3   4   5 [Index]
2	5	4	8	1	3
Here 1 (index 4) is smaller than 8(index 3), we swap them

0   1   2   3   4   5  [index]
2	5	4	1	8	3
Here 3 (index 5) is smaller than 8(index 4), we swap them

0   1   2   3   4   5  [index]
2	5	4	1	3	8
 ** First Pass **
8 which is the highest integer has bubbled to its position
 Repeat this method until the arrays are sorted


ITERATION

0   1    2  3    4  5  (index)

2	5	4	1	3	8 [step 1}


0   1   2   3   4   5  [index]
2	4	5	1	3	8 [step 2]

0   1   2   3   4   5  [index]
2	4	1	5	3	8 [step 3]

0   1   2   3   4   5  [index]
2	4	1	3	5	8   [step 4]
** 2nd  Pass **

ITERATION

0   1   2    3   4   5  [index]

2	4	1	3	5	8    [step 1]

0   1   2   3   4   5   [index]
2	1	4	3	5	8    [step 2]

0   1   2   3   4   5    [index]
2	1	3	4	5	8     [step 3]
** 3rd  Pass **


0   1   2   3   4   5   [index]

2	1	3	4	5	8    [step 1]

0   1   2   3   4   5    [index]
1	2	3	4	5	8     ** [Sorted List] **




