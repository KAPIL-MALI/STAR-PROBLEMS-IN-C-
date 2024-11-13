# STAR-PROBLEMS-IN-C-

********************************************************************************INDEX*****************************************************************************************
LINE NO.31 = SQUARE STAR PATTERN
LINE NO.57 = BASIC STAR PATTERN
























                                                            
QUESTION NO.1 SQUARE STAR PATTERN
*****
*****
*****
*****
SOLUTION 
#include <iostream>
using namespace std;
int main (){
    
    for (int a = 1 ;a <= 4 ;a++){
    for (int b = 1 ;b <= 5 ;b++){
        cout <<"*";
    }
        cout <<endl;
    }
    return 0;
}

//outer for loop will be used for the rows and
//inner for loop will be used for the columns .





BASIC STAR PATTERN
*
**
***
****
*****

#include <iostream>
using namespace std;

int main() {
    int c = 5;  // Number of rows
    for (int a = 1; a <= c; a++) {        
        for (int b = 1; b <= a; b++) {    
            cout << "* ";
        }
        cout << endl;                     
    }
    return 0;
}
