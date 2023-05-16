Welcome to the Coding-Ninjas-course-all-question-answer- wiki!
*******************************************************************************************************************************************

Lecture 2 : Getting Started
***************************
What is the output
Q1. What will be the output of the following code ?
#include <iostream>
using namespace std;
int main(){
    cout << code ;
}

Answer-------->>>>
Options
This problem has only one correct answer
> code
> Error  <---------- Correct answer

Solution Description
If we want to print something on screen exactly, we need to put that text in double quotes, otherwise error will come. For eg. cout << "code";

***************************************************************************************************************************************

What is the output
Q2. What will be the output of the following code ?

#include <iostream>
using namespace std;
int main(){
    cout << "career" << "labs";
}

Answer-------->>>>
 Options : 
This problem has only one correct answer
> careerlabs  <------ Correct answer
> career labs
> labs career
> labscareer

Solution Description
The text will be printed exactly like we placed inside double quotes. So first we are printing "career". After printing, our cursor will be right next to the 'r' of "carrer". So "labs" will be printed right next to the "career" without any spaces between them.

***************************************************************************************************************************************

Datatype
--------
Q3. Which of the following data type stores longest decimal number ?

Options:
This problem has only one correct answer
> long
> float
> double <------ Correct answer
> short

Solution Description
Out of all given options, only float and double can hold decimal numbers. Size of the float is 4 bytes and double is 8 bytes (in most of the compilers, as the size of data types is compiler specific). So double can store bigger decimal numbers.
********************************************************************************************************************************************

Garbage value
-------------
Q4. Compiler assigns a garbage value to an uninitialised local variable in C++ Programming ?
 Options : 
This problem has only one correct answer
> True  <------- Correct answer
> False

Solution Description
In C++, all variables contain garbage values before their initialisation.
********************************************************************************************************************************************

What is the output
__________________
Q5. What will be the output of following statements -
bool a = true;
cout << a;
Correct answer --------> 1

********************************************************************************************************************************************

What is the output
------------------
Q6. What is the output of the following code if the input is : 5, 15 ?
  #include <iostream>
  using namespace std;
  int main() {
    int a, b; 
    cin >> a;
    cin >> b;
    cout << (a+b);
  }

Options : 
This problem has only one correct answer
> 5
> 15
> 20        <--------------- Correct Answer
> Error

Solution Description
We are asking two integer values from user and input is "5 15" (without quotes). So 5 will be assigned to a and 15 will be assigned to b. We can enter multiple input values either separated by space or in new lines. 
Hence, the result will be 20.

********************************************************************************************************************************************
What is the output
------------------
Q6. What is the output of the following code if the input is :
2, 10.1, D ?

#include <iostream>
using namespace std;
int main() {
    int a;
    double d;
    char c;
    cin >> a >> d >> c;
    cout << a << d << c << endl;
}
Options : 
This problem has only one correct answer
> 2 10.1 D
> 2
> 210.1D     <------------ Correct Answer  
> Error

Solution Description
We are taking 3 inputs - one integer, one double and one character value. And our input is : "2 10.1 D" (without quotes). So, 2 will be assigned to a, 10.1 will be assigned to d and D will be assigned to c.
We can enter multiple input values either separated by space or in new lines. 
Then we are printing all the three values one by one, without any space between them. So ans is : 210.1D
********************************************************************************************************************************************
What is the output
------------------
Q7. What will be the output of following statement ? Consider that header files are already included in the code, and this line is written inside the main().

 > cout << (‘D’ + 1);
                       69  <------- Correct answer

Note: A character or integer without a space could be the corresponding answer value. Pay attention to the capital and lowercase letters.
Note: You can refer the ASCII value table.
********************************************************************************************************************************************
What is the output
------------------
Q8. What will be the output of following statement ? Consider that header files are already included in the code, and this line is written inside the main().

int i = 'd';
cout << i;
                100  <------ Correct Answer

Note-1: A character or integer without a space could be the corresponding answer value. Pay attention to the capital and lowercase letters.
Note-2: You can refer the ASCII value table.
********************************************************************************************************************************************
What is the output
-----------------
Q9. What will be the output of following statement ? Consider that header files are already included in the code, and this line is written inside the main().

char c = 74;
cout << c;
                J <--------- Correct Answer

Note-1: A character or integer without a space could be the corresponding answer value. Pay attention to the capital and lowercase letters.
Note-2: You can refer the ASCII value table.
********************************************************************************************************************************************
What is the output
------------------
Q10. What will be the output of following statement ? Consider that header files are already included in the code, and this line is written inside the main().

int a = 10;
char ch = 'a';
ch = ch + a;
cout << ch << endl;
                         K <-------- Correct Answer

Note: A character or integer without a space could be the corresponding answer value. Pay attention to the capital and lowercase letters.
********************************************************************************************************************************************
What is the output
-------------------
Q11. What will be the output ?

#include <iostream>
using namespace std;   
int main()
{
    double a = 6 / 4;
    int b  = 6 / 4;
    double c = a + b;
    cout << c;
}

Options : 
This problem has only one correct answer
> 3
> 1.5
> 2          <----------- Correct Answer
> 2.5
Solution Description
When 6 / 4 is performed, both the operands of / are int hence answer will be an int i.e. 1. Hence the value of both a and b is 1. Thus a + b will be 2. In C++, if a double value doesn't contain any decimal value, only integer will be printed.
********************************************************************************************************************************************
Q12. What is the output

#include <iostream>
using namespace std;  
int main()
{
    double a = 55.5;
    int b = 55;
    a = a % 10;
    b = b % 10;
    cout << a << " "  << b;
}

Options : 
This problem has only one correct answer
> 5 5
> 5.5 5
> 6 5
> Syntax error       <-------- Correct Answer

Solution Description
% can’t be used with double or float.
********************************************************************************************************************************************
Q13. What is the output

#include <iostream>
using namespace std;
int main() 
{
    int var1 = 5;
    int var2 = 6;
    cout << (var1 > var2);
 }
Options : 
This problem has only one correct answer
> true
> false
> 0          <------- Correct Answer
> 1

Solution Description
'>' operator gives a boolean answer. And the condition is false. So answer will be false and 0 will be printed (boolean variables print only 0 and 1).

Lecture 2 : Completed 🥇 