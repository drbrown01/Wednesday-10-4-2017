# **Instructions**

* Write a function that accepts a string and a function as arguments. It should log the string, and then run the function.

* Write a function that accepts a boolean value and a function as arguments. It should run the function if and only if the boolean argument is true.
Add Comment Click to expand inline 10 lines



Shantanu Kangude [9:29 PM]
Scratch for Wednesday:
Scratch Wed Oct 4

TO CREATE A NEW APP:


1. Create a folder by that name - empty
2. Go to that folder
3. npm init
4. Start creating at least 1 javascript file = index.js of CLI.js
5. Whenever you require a new module just run:
   npm install <that module> --save

6. Continue coding
7. git commit all except node_modules folder

BACK AT 8.38pm

CLOSURE = CODE that will run when called - AND - references to all variables that the code needs to access; It does not note the values for those variable at the time of definition of the function, but the variable references; values of those refs can change by the time we run the closure/function.

# **Instructions**

* Write a function that accepts a string and a function as arguments. It should log the string, and then run the function.

function name(str,potato) {
    console.log(str);
    potato();
}

* Write a function that accepts a boolean value and a function as arguments. It should run the function if and only if the boolean argument is true.

function dog(toe,junk) {
    if (toe==true) {
        junk();
    }
}

* Write a function that accepts a function (F) and a value (V), and returns a function that returns the result of running F on V. This sounds tricky, but it's easier than it sounds—just take it step by step!

function name(F,V) {
    return function(){
        return F(V);
    }
}

* Finally, write a short message to a file using `fs.writeFile`. Does this function use callbacks? If so, identify them.
