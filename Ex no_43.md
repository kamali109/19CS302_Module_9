# EX 43 C program to Write a function to display queue elements using array.
## DATE:
## AIM:
To Write a function to display queue elements using array.

## Algorithm
```
Start.
Define a variables.
Write a functions to perform push,pop,display,peek in stack using array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.
```
## Program:
```
/*
C program to write a function to display queue elements using array.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
float queue[50]; 
int rear=-1,front=-1,i; 
void display() 
{ 
if(front==-1||front>rear) 
printf("No elements to display\n"); 
else 
{ 
for(i=front;i<=rear;i++) 
printf("%.1f\n",queue[i]); 
} 
 
} 
void display() 
{ 
if(front==-1||front>rear) 
{  
printf("No elements to display\n"); 
else 
{ 
for(i=front;i<=rear;i++)
```

## Output:
<img width="1063" height="457" alt="image" src="https://github.com/user-attachments/assets/8c06ff6d-7725-4f28-bbdf-bcc653e80d79" />



## Result:
Thus the program was executed and the output was verified successfully.
