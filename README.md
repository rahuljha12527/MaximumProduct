# MaximumProduct

Find the product with highest number of quadruples which follow a*b = c*d where a,b,c and d are different. The array will contain all unique elements.
Note :
Consider lower product if many products have same number of quadruples. Print 0 if no such quadruple is found.
Input format :
Line 1 : Integer N 
Line 2 : N integers separated be a single space
Output Format :
 Product Quadruples_Count
Constraints :
 0 <= N <= 10^4
 1 <= Arr[i] <= 10^4
Sample Input :
6
2 6 3 4 1 12
Sample Output :
12 3
Explanation :
Arr[] = {2, 6, 3, 4, 1,12},
output : 12 3
Product = 12, Count = 3
2 6 and 3 4,
2 6 and 1 12 , 
3 4 and 1 12 . 
