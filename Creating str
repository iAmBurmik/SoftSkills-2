#include <iostream>

using namespace std;

void strCompare(string *pstr, int size)
{
    for(int i = 0; i < size; i++)
    {
        char num = 1;
        for(int j = i+1; j < size; j++)
        {
            if(pstr[i] == pstr[j])
            {
                pstr[i] += to_string(num);
                num ++;
                pstr[j] += to_string(num);
                num ++;
            }
        }
    }
}

int main()
{
    int size, pos;

    string *pstr;

    char S = '.';

    cout << "Enter number of strings: "; cin >> size;

    cin.ignore();

    pstr = new string [size];

    for(int i = 0; i < size; ++i)
    {
        cout << "\nString #" << i + 1 << ": ";
        getline(cin, pstr[i]);
    }
    
    strCompare(pstr, size);
}
