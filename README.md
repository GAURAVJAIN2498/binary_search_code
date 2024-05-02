# binary_search_code (sorted and unsorted problems)

🌟Binary search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one.🌟

Terminology is found the best cpu run time. just half of the given portion and find the value in given content. then choose left and right side accoring to find value in which portion your value available. then narrowed the portion the repeat the same process in loop until your value is not found.

💢Ex-

1.we took a range first

        db = list(range(1,33))             
2.main code
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/187f79b5-144b-4e7b-a107-f169cc02f6f2)

3. Define with lwbs with db=data , value= find. start with 0. and end with given db range last no.

4. Now, we give the loop in which write a condition if given data, middle value is not equal to find then run the loop till middle = find value. and also start greater then equal to end. till that run the loop
In if value is greater then data middle value , then start with middle+1. if less , then end with mdddle-1.

5.like this:-
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/2cadcae2-6dc0-450e-87a7-e464465b0720)

6.Do this with start+end/2 = middle. Then run other loop if you got the middle = value then print we found. else not found.

7.Run

             lwbs(db, 29)
             
result get like this- 
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/2d9c3349-6cc9-4897-b0a5-480783a0a8f0)


if find value is greater then given data then it was always show not found with those same steps.

# Bubble sort

Bubble sort is a sorting algorithm that starts from the first element of an array and compares it with the second element. If the first element is greater than the second, we swap them. It continues this process until the end of the array, with the largest elements “bubbling” to the top.

Example like- ![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/fabae948-c9bf-4608-b5e2-b0bf1415335b)

Write a condition of Bubble sort. in this data is random and insorted.
 Give the data-
 
     db=[3,1,2,6,7,9,0,5]

Run with this-
        
         lw_bubble_sort(db)

Selection sort is greater then Bubble sort.
Bubble sort is not a good algorithm for unsorted data. but if the given data is provide sorted then Bubble sort is a best algorithm.

Result -
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/f707ef89-a8c7-47e3-bef2-6eb0f3e7ae5e)
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/d0bdb8d2-9068-427f-8c3c-c8946f714f86)

when the data is already sorted-
![image](https://github.com/GAURAVJAIN2498/binary_search_code/assets/136182348/ea7450a9-6826-4aa9-9c0d-c655ec10b721)



# Connect-

📩Email:- gauravjain2498@gmail.com

🧷LinkedIn:- https://www.linkedin.com/in/gaurav-jain-8b39b7247

Thank you..!!


