# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.

## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

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
C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
} 
```

## Output:

<img width="1063" height="543" alt="image" src="https://github.com/user-attachments/assets/031676fb-9df2-416b-b0e5-a5e16c47cd5a" />


## Result:
Thus the program was executed and the output was verified successfully.
