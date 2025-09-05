# Activity-2-

#include <iostream>
#include <string>
using namespace std;

int main() {
    string fullName, courseYrSec, birthday, motto;

    cout << "Enter Full Name: ";
    getline(cin, fullName);

    cout << "Enter Course, Year & Section: ";
    getline(cin, courseYrSec);

    cout << "Enter Birthday: ";
    getline(cin, birthday);

    cout << "Enter Motto/Motivation in Life: ";
    getline(cin, motto);
    
    cout << "\nHi! I'm " << fullName << " of " << courseYrSec 
         << ". Welcome to Data Structures and Algorithm!" << endl;
    cout << "My Birthday is on " << birthday 
         << ". and my motto/motivation in life is " << motto << endl;

    return 0;
}
