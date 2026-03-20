# EX 42 C program to write a fuctions to perform push,pop,display,peek in stack using array.

## AIM:
To write a fuctions to perform push,pop,display,peek in stack using array.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to write a fuctions to perform push,pop,display,peek in stack using array.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
int stack[100]; 
int size=3,top=-1,i; 
void push (float data) 
{ 
if(top==size-1) 
{ 
printf("stack is full\n"); 
} 
else{ 
top=top+1; 
stack[top]=data;} 
} void display(){ 
for(i=top; i>=0; i--){ 
printf("%d ",stack[i]); 
} 
if(top==-1) 
{ 
printf("stack is empty\n"); 
}
Void pop() 
{ 
if(top==-1) 
{ 
printf("stack is empty\n"); 
} 
else{ 
top=top-1; 
} 
} 
void peek() 
{ 
printf("%d ",stack[top]); 
} 
```

## Output:

<img width="1146" height="960" alt="image" src="https://github.com/user-attachments/assets/92db9329-9ec4-4b84-9111-95d79baf1727" />


## Result:
Thus the program was executed and the output was verified successfully.
