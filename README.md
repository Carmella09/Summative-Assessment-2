# Summative-Assessment-2

1. Factorial

        #include<iostream>
        #include<string>
        using namespace std;
        int main()
        {
            int n, f = 1;
            cout << "\nFACTORIAL\n\n";
            cout << "Student's name: ";
            string name;
            cin >> name;
            cout << "\nEnter a Number: ";
            cin >> n;

            while (cin.fail())
            {
                cout << "\nInvalid Input\n\n";
                cout << "Enter a Number again: ";
                cin.clear();
                cin.ignore(1000, '\n');
                cin >> n;
            }

            for (int x = n; x > 0; x--)
            {
                f = x * f;
            }
            cout << "\nFactorial of " << n << " is " << f << endl;

        }


2. Table from 1-10: 
     
          #include<iostream>
          #include<string>
          using namespace std;
          int main()
          {
              double y;
              double p;
              cout << "\nTable from 1-10\n\n";
              cout << "Student's name: ";
              string name;
              cin >> name;
              cout << "\nEnter a Number: ";
              cin >> y;

              while (cin.fail())
              {
                  cout << "\nInvalid Input\n\n";
                  cout << "Enter a Number again: ";
                  cin.clear();
                  cin.ignore(1000, '\n');
                  cin >> y;
              }

              for (int i = 1; i <= 10; i++)
              {
                  p = y * i;
                  cout << y << " x " << i << " = " << p << endl;
              }
          }



3. Power from 1-10

          #include<iostream>
          #include<string>
          using namespace std;
          int main()
          {
              double b;
              cout << "\nPower from 1-10\n\n";
              cout << "Student's name: ";
              string name;
              cin >> name;
              cout << "\nEnter a Number for the Base: ";
              cin >> b;

              while (cin.fail())
              {
                  cout << "\nInvalid Input\n\n";
                  cout << "Enter a Number again: ";
                  cin.clear();
                  cin.ignore(1000, '\n');
                  cin >> b;
              }

              for (int i = 1; i <= 10; i++)
              {
                  cout << b << "^" << i << endl;
              }
          }

































