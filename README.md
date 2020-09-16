# Debugging
## ORDER OF EXECUTION
### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

## EXECUTION CONTEXTS
### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 

## The stack
### The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the curent task.


## ERROR OBJECTS 
### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
