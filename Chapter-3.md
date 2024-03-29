# SECTION ANALYSIS

## Section 3.1 - 3.2 
    
Within programing there are input and output operators. In C++ these actions require streams. The two main types are: 

    Input stream: This brings data from an input device (like a keyboard) into the program. 

    Output stream: This sends data from the program to an output device (like a screen).

Input is repersented by cin while output is cout. These are all under the iostream operater. So, to use input and output in a C++ program, we include #include <iostream> and then use 'cin' and 'cout' for reading and displaying data respectively. For example, 'cin' reads data from the keyboard, and 'cout' displays data on the screen.

To properly us the "cin" operator you must declare a vaeriable to assign the inserted value to. 

## Section 3.3 - 3.5 


In simpler terms, formatting output means arranging the way data appears when it's displayed. In programming, particularly in C++, we often need to control how numbers are shown, like specifying the number of decimal places for floating-point numbers or aligning columns neatly.

To format output in C++, we use manipulators along with the cout statement. Manipulators are like tools that help us adjust how data is displayed. One common manipulator you've used is endl, which moves the cursor to the beginning of the next line after displaying data.

Other useful manipulators include:

setprecision: Specifies the number of decimal places for floating-point numbers.

fixed: Ensures that floating-point numbers are always displayed in decimal format.

showpoint: Forces display of decimal point, even if the number is an integer.

setw: Sets the width of the field for displaying data, useful for aligning columns.

For example, if you want to display a floating-point number with two decimal places, you can use cout << fixed << setprecision(2) << myNumber;. This tells the program to display myNumber with two decimal places.

## Section 3.6 - 3.8 

If you need to read a string that includes spaces, you can use the getline function. The way you writ a getline is getline("inputStreamVariable", "stringVariabe");, where "inputStreamVariable" is where you're reading from (like "cin"), and "stringVariable" is the variable where you want to store the string. This function reads until it reaches the end of the line, including spaces, and doesn't store the newline character at the end.

Similarly, you can output the contents of a string variable using "cout" and "<<". For example, if you have a string variable named "myString", you can use 
cout << myString; to display its contents on the screen.

File input/output (I/O) is crucial for handling large amounts of data efficiently in programs. 

To address these limitations, C++ offers file I/O. This file defines two important data types: "ifstream" for input file "istreams" and "ofstream" for output file streams. By using file stream variables and functions like "open", "close", "<<", and ">>", programs can read data from files and write output to files. 

In a typical program, after including the necessary headers and declaring file stream variables (<ifstream>), the files are opened for reading or writing using the open function. Once the I/O operations are complete, it's essential to close the files using the close function.

Overall, file I/O provides a structured approach for handling data efficiently, facilitating tasks like data preparation, sharing, and subsequent processing, making it a crucial aspect of programming, particularly for managing large-scale data operations.


# PROGRAMMING EXERCISE
int main() {
int month, day, year;
cout << "are you a natural born citizen y/n: " << endl;
cin>> born;

cout << "enter month of birth(number) : " << endl;
cin >> month;

cout << "enter day of birth: " << endl;
cin >> day;

cout << " enter year of birth: " << endl;
cin>> year ;
if (born == 'y' && year <= 1986 ) {
  cout << " congratulations! you are eligible to run for president!" << endl;
  }
  else {
    cout << "sorry! you are not eligible to run for president." << endl;
    }
return 0;
}
