# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```



```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```





```
iii)	# Find the element in a list using Binary Search (recursive Method).
```





```
## Sample Input 
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/311523d9-2ddb-4387-9ac1-65fa60133306)
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/6300e382-6bd3-4c3d-b2ff-477b9ddb8032)
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/f330933e-448f-4e67-89f2-c0eb1eff01b5)

##  Output
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/3137b063-31ec-4c9d-95fa-49ead02fe81f)
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/a628cc92-2957-4c09-8b24-cbab7402e40c)
![image](https://github.com/KeerthanaaSaravanan/EX-07_Search-Algorithm/assets/145742596/5b2e3454-3073-4e19-91be-03961c50f015)

## Result
Thus the linear search and binary search algorithm is implemented using python programming.
