# DescendSort
A program to sort the elements of an array in descending order


In this program, we need to sort the given array in descending order such that elements will be arranged from largest to smallest. This can be achieved through two loops. The outer loop will select an element, and inner loop allows us to compare selected element with rest of the elements.

Java Program to sort the elements of an array in descending order
Elements will be sorted in such a way that largest element will appear on extreme left which in this case is 8. The smallest element will appear on extreme right which in this case is 1.

Algorithm
STEP 1: START
STEP 2: INITIALIZE arr[] ={5, 2, 8, 7, 1 }.
STEP 3: SET temp =0
STEP 4: PRINT "Elements of Original Array"
STEP 5: REPEAT STEP 6 UNTIL i<arr.length
            //for(i=0; i<arr.length; i++)
STEP 6: PRINT arr[i]
STEP 7: REPEAT STEP 8 to STEP 9 UNTIL i<arr.length
            //for(i=0; i<arr.length; i++ )
STEP 8: REPEAT STEP 9 UNTIL j<arr.length
            //for(j=i+1;j<arr.length;j++)
STEP 9: if(arr[i]<arr[j]) then
            temp = arr[i]
            arr[i]=arr[j]
            arr[j]=temp
STEP 10: PRINT new line
STEP 11: PRINT "Elements of array sorted in descending order"
STEP 12: REPEAT STEP 13 UNTIL i<arr.length
            //for(i=0;i<arr.length;i++)
STEP 13: PRINT arr[i]
STEP 14: END
