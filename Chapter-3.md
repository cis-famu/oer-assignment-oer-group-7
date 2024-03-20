# SECTION ANALYSIS

## Section 3.1 - 3.2 

Within programing there are input and output operators. In C++ these actions require streams. The two main types are: 

    Input stream: This brings data from an input device (like a keyboard) into the program. 

    Output stream: This sends data from the program to an output device (like a screen).

Input is repersented by cin while output is cout. These are all under the iostream operater. So, to use input and output in a C++ program, we include #include <iostream> and then use 'cin' and 'cout' for reading and displaying data respectively. For example, 'cin' reads data from the keyboard, and 'cout' displays data on the screen.

To properly us the "cin" operator you must declare a vaeriable to assign the inserted value to. 

## Section 3.3 - 3.5 


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
