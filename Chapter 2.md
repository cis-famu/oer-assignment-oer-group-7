REVIEW QUESTIONS
1.Explain the role of 'cin' and 'cout' in C++ input and output operations
2.Describe the roles of manipulators in C++ output operations.
3.What are the five steps to opening and reading files?
4. true or false: #include '<iomanip>' is needed to open files
5. Which of the following is a manipulator used for formatting output in C++ ?
     a. Cin
     b. setw
     c. ifstream
     d.close
REVIEW ANSWERS
1. cin is used for standard input operations in C++, while cout is used for standard output operations
2. manipulators are used to format output, such as controlling the width of output fields, settings precision for floating-point numbers, etc.
3. include f stream header, declare file stream variables, associate file stream with input/output sources (open files) , use file stream variables( >> << ) along with other input/output functions , close file
4. false
5.  B - setw (set width)

KEY TERMS
Stream- a sequence of characters from the source to the destination
Input Stream- a sequence of characters from an input device to the computer (istream)
output Stream- a sequence of character from the computer to the output device (ostream)
Common Input - the CIN variable 
common output - the COUT variable
Input stream variables - variables of the type istream
Output stream variables - variables of the type ostream
Stream Variable - either an input stream variable or an output stream variable 
Input failure - a situation in which a program either fails to compile, or yields incorrect results, because the input data does not match the corresponding variables in the program
istream member functions - functions associated with the data type istream
stream member functions - I/O functions such as "get"
predefined functions - Functions that are already defined in C++
Arguments - Values that are passed in a function call in the parentheses after the name of the function
Function call - an expression that transfers control from the main function to the first statement in the body of the function, such as pow(2,3)
Dot notation - notation in which a dot separates the input stream variable name from the member, or function name
member access operator - the dot operator in C++
Fail state - the state an input stream enters after input failure in which all further I/O statements using that stream are ignored
parameterized stream manipulators - manipulators with parameters
File - an area in secondary storage used to hold information
File stream variables - user declared variables including ifstream and ofstream used for input and output (>> << )
Opening the files - associating a file stream variable with an input/output source
get function - inputs next character(including whitespaces) : syntax of cin & get ( cin.get(varchar) )
ignore function - discards a portion of the input : cin.ignore(intExp, chExp)
putback function - places previous character extracted by the get function from an input stream back to that stream
istreamVar.Putback(ch); - input stream variable
peek function - returns next character from the input stream; does not remove the character from the stream; istreamVar.peek()
Clear function - returns code into working state; istreamVar.clear()
setprecision - output decimal numbers by N places; must include header #include <iomanip>
fixed - outputs floating-point numbers in a fixed decimal format
showpoint - forces output to show the decimal point and trailing zeros
setfill- fills unused columns with a character
left manipulator- left justifies the output
right manipulator- right justifies the output 
