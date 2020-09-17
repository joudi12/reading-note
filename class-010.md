# summery
### ORDER OF EXECUTION 
#### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
### EXECUTION CONTEXTS
#### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope. 
### EXECUTION CONTEXT & HOISTING 
1. PREPARE
2.  EXECUTE 
### UNDERSTANDING SCOPE 
#### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object
### UNDERSTANDING ERRORS 
#### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 
### ERROR OBJECTS
#### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
### HOW TO DEAL WITH ERRORS 
#### Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.
1.  DEBUG THE SCRIPT TO FIX ERRORS 
2.  HANDLE ERRORS GRACEFULLY 
![solv](https://res.cloudinary.com/practicaldev/image/fetch/s--FjIozH9N--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/ufwmieenkr60ae86qi24.png)
### A DEBUGGING WORKFLOW
#### Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues. 
### WHERE IS THE PROBLEM? 
1. Look at the error message, 
2.  Check how far the script is running. 
3. . Use breakpoints where things are going wrong
#### If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 
#### JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
