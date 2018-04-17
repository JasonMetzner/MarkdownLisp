# Intro to Lisp
JasonMetzner

Lisp is used for mostly animation and AI work. Being the second oldest programming language. No one really uses Lisp for practical uses anymore. 

# Output
The `~%` stands for newline. 

The `t` stands for terminal. 

# Variables
Global variable, by convention are surrounded by asterisks to spot them easier. 

`(read)` is used to get input data from console. (defvar *name* (read)


# Functions
defun
lambda
Returns an anonymous function

return-from
Immedi­ately returns a value from a function (or a block)


funcall -Invokes a function from a function object


apply-Works like funcall, but receives the arguments as a list
&optional, &key, &rest, &allow-other-keys
Different ways to capture function arguments


# Call function. 

Calls the function, passes in two arguments. 


# Standard Control Constructs
if The else form is optional

when Like if, but returns nil if the condition is falsy and evaluates multiple body forms

unless Like when, but executes its body only when the condition is falsy

# Object­-Or­iented

# Defgeneric
Defines an abstract operation (poly­mor­phism)


# Defmethod
Defines an implem­ent­ation of a generic function

# Call-next-method
Similar to an invocation to a super-­class method

# Defclass
New named class; some slot options are: :reader, :writer, :acce­ssor, :init­arg, :init­form, :docu­men­tat­ion, :allo­cation

# Slot-value
Returns the value of slot in the object (se­tf­-­able)

# With-slots, with-accessors
Binds a slot/a­ccessor to a symbol that can be used in its body