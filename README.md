# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	#program to mark the maximum of marks using the list method sort
    #Developed By : Sarish Varshan V
    #Register Number : 212223230196 
    
    ```
   
    def max_marks(marks):
       marks.sort()
       large = marks[-1]
       return large

    ```

ii)	# To find the maximum marks using the list method max().
    #Developed By : Sarish Varshan V
    #Register Number : 212223230196 
    
    ```
      
    def max_marks(marks):
        large = max(marks)
        return large

    ```

iii) # To find the maximum marks without using builtin functions.
     #Developed By : Sarish Varshan V
     #Register Number : 212223230196 
  
    ```
    def max_marks(list1):
        max=list1[0]
        for i in list1:
         if i>max:
            max=i
        return max

    ```



## Output:
## SORT()
![image](https://github.com/sarishvarshan/FindMaximum/assets/152167665/d8a7086b-cec8-4e5d-99ab-6068908ceeec)
## MAX()
![image](https://github.com/sarishvarshan/FindMaximum/assets/152167665/58106af6-52ff-4541-ac31-d390c0736dd9)
## BUILT-IN FUNCTION()
![Screenshot 2024-03-23 113502](https://github.com/sarishvarshan/FindMaximum/assets/152167665/e3ac2597-a87f-4fcb-ac57-25cc298f84d8)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
