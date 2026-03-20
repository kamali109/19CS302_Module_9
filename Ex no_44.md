# EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.

## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

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
C functions to perform enqueue, dequeue, display, peek in Queue using Array.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
char queue[50]; 
int size=10,front,rear,i; 
void enqueue(char data) 
{ 
if(rear<size) 
{ 
if(front==-1) 
{ 
front=0; 
} 
rear=rear+1; 
queue[rear]=data; 
} 
{ 
printf("%c\n",queue[i]); 
} 
} 
void dequeue() 
{  
if(front==-1||front>rear) 
{ 
printf("Queue Underflow\n"); 
} 
else 
{ 
front=front+1; 
} 
 
} 
void peek() 
{ 
printf("%c\n",queue[front]); 
 
} 
 
}
```

## Output:

<img width="890" height="908" alt="image" src="https://github.com/user-attachments/assets/d2f09af4-f1c4-4981-8b2e-92c8948e5815" />


## Result:
Thus the program was executed and the output was verified successfully.
