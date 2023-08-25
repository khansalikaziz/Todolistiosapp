# Todolistiosapp

--> Everything in js happens inside an execution context.

# Execution context

1) Memory component

key --> value
a:10
fn:{...}

Everything stores here in key value pair

2) code component

--> here code executed line by line


* Note ---> Javascript is a synchronous, single-threaded language(one command at a time in specific order).

* Note ---> Call stack maintains the order of execution of execution context.



# window

--> it contains different methods and variable that  is provided by Javascript engine.

# this 

--> in Global level this points to window object.

* Note --> when a Javascript program runs a global context is created and global object is created(this).

* Note --> Any space outside function declaration is present in global space


# Scope

--> scope in js is directly related to lexical environment.
--> Lexical environment is the local memory along with lexical environment of the parent.(lexical--> sequential)
--> way of finding reference of var or functions is called as scope chain.
