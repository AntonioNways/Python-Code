# Python-Code
Python Codes with example and description

basic codes:
//math:
2**10 // 2 to the power of 10


//to print a character from 0 to 5 in x = "<string>"
print x[0:5] // or print [:5]

//To find "character/sentence" in "ABC" string, etc print abc.find(s,0), find the first s starting from the first character
ABC.find("<character>,<after # of character>") 

//To create a procedure (parameters are called operands or arguments): 
Def <name>(<parameters>,<parameters1>,<...etc>)

//return, to get output
Return <expression>,<expression>,<etc...>

//If statement
If <test expression> :  // a<b,a>b,a=="<string>" etc
	<block> //if the expression is true, then we would like it to do x action eg = return True
Else :
	<block> //if the expression is false, then we would like it to do x action



//Loop
While <test expression>: // A==b, a<b, etc
	<procedure> //what would we want it to do? print a?
<procedure>  //what to do at the end of the loop (if the test expression is false)
//For loop
for <name> in <list>:
	<block>
//eg: def print_all_elements(p):
//	for e in p:
//		print e
// what this does is that it will make e = to the first string in the list, and move down the list.




//assertion, if the expression is false, the assertion will fail
assert <expression>

// check if its divisible by n:
x%n==0:

// list operator:

<list>+<list2> --> <list1 + list 2> // example : [1,2,3]+[z,x] = [1,2,3,z,x]
len(<list>) // counts the number of item in the list. eg len([1,2,3]) = 3 or len("Udacity") = 7
<list>.append(<item>) // will add <item>, into the list
<list>.index(<value>) // looks for the first value in the list, if there's no such value, it will output "<Value> is not found"
<value> in <list> // determine if the value is in the list, if it is in the list, it will output "True", if the value is not in the list, it will output "False"
//pop
<list>.pop() ..givest the element, mutates the list by removing and returning its last element
//eg: a =[1,2,3], a.pop(), this will return "3" and a = [1,2]

//split ==> it will separate the string to words, into a list (uses space to split)
<string>.split() --> [<word>,<word>, etc]



