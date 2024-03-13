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
