# practice-
#include <iostream>
#include <conio.h>
using namespace std;

class test
{
    private:
    int n;
    public:
    void in()
    {
        cout << "Enter a number: ";
        cin >> n;
    }
    void out()
    {
        cout << "the value of n is = " << n << endl;
    }
};
int main()
{
    test t;
    t.in();
    t.out();
    return 0;
}
