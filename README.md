//# challenge
//No. 13, Employee's absent, Sir Bagus Homework
#include <iostream>
#include <cmath>
#include <iomanip>

using namespace std;

int ZnumberOfEmployee();
int ZAbsent(int);
double ZAverageOfAbsent(int, int);

int main() { } // di edit

int ZnumberOfEmployee()
{
    int employee;
    cout << "Number of employee in the company\n: ";
    cin >> employee;
    return employee;
}

int ZAbsent(int employee)
{
    int daysAbsent;

    for(int i = 0; i < employee; ++i)
    {
        int absent;
        cout << "Enter the days of employee " << i+1 << " missed: \n";
        cin >> absent;
        daysAbsent += absent;
    }
    return daysAbsent;

}
