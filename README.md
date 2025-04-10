## NAME: SARGURU K
## REGNO: 212222230134
# Experiment-5
## AIM:
Write a python program for Binary Search and inspect for failures. 

# ALGORITHM
Start the program.

2. Get the list from the user

3. Get the element to be searched

4. Compare the mid element with the key, if same return the index

5. If key is greater, search it in the right side, else search it in the left side.

6. If not found return -1

7. Stop the program. 

 # PROGRAM
```python
def binary_search(arr, x):  
    low = 0 
    high = len(arr) - 1 
    mid = 0 
    while low <= high: 
        mid = (high + low) // 2 
        if arr[mid] == x:
            return mid
        elif arr[mid] < x: 
            low = mid + 1 
        elif arr[mid] > x: 
            high = mid - 1 
        else: 
           return -1 
arr = [2,3,4,10,40] 
x = input("Enter the element to be searched: ");  
try: 
    x = int(x) 
    result = binary_search(arr, x)  
    if result != -1: 
          print("Element is present at index",str(result)) 
    else: 
          print("Element is not present in array") 
except: 
    print("Enter a valid input!") 
```
# OUTPUT

![image](https://github.com/user-attachments/assets/23eb9e1d-98a2-499d-baec-29dab19f2538)

![image](https://github.com/user-attachments/assets/6a5f77a0-90b8-45e9-b594-222eda719f18)

![image](https://github.com/user-attachments/assets/63386c17-f8b7-4fc9-b4a8-1f6fdc32a362)

![image](https://github.com/user-attachments/assets/0044d0d6-d559-47ca-b903-f754ef94b9a0)

![image](https://github.com/user-attachments/assets/b91678f0-06fe-48ad-a80d-ca3054fd8dfd)

![image](https://github.com/user-attachments/assets/2752d8a9-3f4c-43f8-867a-abd3a93c0ed2)





 

# RESULT

Thus, the python program of binary search is implemented and the output is verified
successfully. 
