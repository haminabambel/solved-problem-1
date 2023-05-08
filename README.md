Download Link: https://assignmentchef.com/product/solved-problem-1
<br>
A limited-sized Queue ADT is an abstract data type that has a limit on the length of the queue. It can be created with a static array of size N, where N is the maximum length of the array. In C, this structure can be defined as follows:

typedef struct { int * data; // array of the data on the queue // you may add other attributes here but use as few as possible } queue_t;

Write an (efficient) pseudocode for the implementation of each of the following function prototypes (proper C code will also be accepted)

– void print (Q) – prints the entire queue Q from front to back.

– int enqueue (Q,x)

-enqueues the element x into queue Q (if unsuccessful, return-1)

– int* de queue (Q)

– dequeues the next integer from front of the queue (if unsuccessful, return null)

– int isEmpty (0) – returns 1 (true) or 0 (false) depending on emptiness of the queue Q

– unsigned int size (Q)

-returns the number of items currently in the queue

In your final solution, you may add any extra attributes that you feel is needed for this question but you must use as few extra attributes as possible and your algorithm must be as efficient as possible (in terms of big-O analysis).