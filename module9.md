# EXP NO:11 C PROGRAM TO DISPLAY STACK ELEMENTS USING AN ARRAY.

## Aim:
To write a C program to display stack elements using an array.
## Algorithm:
1.	Include Necessary Header Files
2.	Declare Global Variables
3.	Define the Display Function
4.	Main Function (or Other Relevant Code)
5.	Initialize the stack and top as needed.
6.	Perform stack operations (push, pop, etc.).
7.	Use the display function to visualize the stack's contents
 
## Program:

```
int stack[100],top,i;
void display()
{
    for(i=top;i>=0;i--)
    {
        printf("%d\n",stack[i]);
    }
}


```

Output:
<img width="203" height="286" alt="image" src="https://github.com/user-attachments/assets/5f643761-cf66-4e2c-8d12-b85e62ead173" />


## Result:
Thus, the program to display stack elements using an array is verified successfully.
 

# EXP NO:12  PROGRAM TO PUSH THE GIVEN ELEMENT IN TO A STACK USING ARRAY.
## Aim:
To create a C program to push the given element in to a stack using array.
Algorithm:
1.	Declare global variables for the stack size, top index, and the stack itself.
2.	Define the push function to add a floating-point number to the stack.
3.	Initialize the stack size, top index, and the stack itself.
4.	Call the push function as needed.
 
Program:
```
char stack[100];
int size=3,top=-1;
void push (char data)
{
    if(top==size-1)
    {
        printf("stack is full\n");
    }
    else
    {
        top++;
        stack[top]=data;
    }
}

```
## Output:
<img width="263" height="298" alt="image" src="https://github.com/user-attachments/assets/9401cc21-eeed-4e56-b359-9b7666bd2cc1" />



## Result:
Thus, the program to push the given element in to a stack using array is verified successfully


 
# EXP NO:13 C PROGRAM TO DISPLAY QUEUE ELEMENTS USING ARRAY.
## Aim:
To write a C program to display queue elements using array

## Algorithm:
1.	Declare global variables for the queue, rear, front, and iteration.
2.	Define the display function to print the elements of the queue.
3.	Initialize the queue, rear, and front as needed.
4.	Call the display function and perform other queue operations as needed.
 
## Program:
```
float queue[100];
int front,rear,i;
void display()
{
    if(front==-1)
    {
        printf("No elements to display");
    }
    else
    {
        for(i=front;i<=rear;i++)
        {
            printf("%.1f ",queue[i]);
        }
    }
}


```
## Output:


<img width="391" height="290" alt="image" src="https://github.com/user-attachments/assets/a54c0963-4e07-4582-a5f5-c98c614116f7" />


## Result:
Thus, the program to display queue elements using array is verified successfully.


 
# EXP NO:14 C PROGRAM TO INSERT ELEMENTS IN QUEUE USING ARRAY.
## Aim:
To write a C program to insert elements in queue using array.

## Algorithm:
1.	Declare global variables for the size, rear, front, and the queue itself.
2.	Define the enqueue function to add a float to the queue.
3.	Initialize the rear, front, and size of the queue as needed.
4.	Call the enqueue function as needed.

## Program:
```
float queue[50];
int front,rear,size=5;
void enqueue(float data)
{
    if(front==-1||front<size)
    {
        front=0;
        rear++;
        queue[rear]=data;
    }
}

```
## Output:
<img width="395" height="239" alt="image" src="https://github.com/user-attachments/assets/60ab5b40-d021-4908-96a3-8da2b02f4480" />

## Result:
Thus, the program to insert elements in queue using array is verified successfully.



 
# EXP NO:15 C FUNCTION TO DELETE ELEMENTS IN QUEUE USING ARRAY



## Aim:

To create a function in C that deletes an element from a queue implemented using an array.

## Algorithm:

1.	Check if the Queue is Empty
o	If the front pointer is -1, it means the queue is empty, and there are no elements to delete. Print a message indicating that the queue is empty.
2.	Delete the Front Element
o	If the queue is not empty, the element at the front index is deleted.
o	Increment the front pointer by 1 to remove the element and point to the next element in the queue.
3.	Check if the Queue Becomes Empty After Deletion:
o	After deletion, check if the front pointer has passed the rear pointer (front > rear). If this is true, reset both front and rear to -1, indicating that the queue is now empty.
4.	End the Function.



## Program:
```
int queue[50];
int front, rear,i;
void dequeue()
{
    if(front==-1||front>rear)
    {
        printf("Queue");
    }
    else
    {
        front++;
    }
}

```
## Output:
<img width="400" height="338" alt="image" src="https://github.com/user-attachments/assets/c94e79f4-5592-489f-b5e4-8eafbe32dd33" />

## Result:
Thus, the function that deletes an element from a queue implemented using an array is verified successfully.
