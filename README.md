# Lecture-12
arrays

    #include <iostream>
    using namespace std;

    int main()
    {
        int ages[5];

        ages[0] = 19;
        ages[1] = 23;
        ages[2] = 22;
        ages[3] = 30;
        ages[4] = 18;

        int array[5] = { 19, 23, 22, 30, 18 };

    }
array values
    
    #include <iostream>
    using namespace std;
    /*
    int main()
    {
        int heartRates[8] = { 54, 60, 71, 59, 62, 63, 60, 58 };

        cout << heartRates[3] << endl;
        cout << heartRates[6] << endl;
    }
    */

    int main()
    {
        int heartRates[8] = { 54, 60, 71, 59, 62, 63, 60, 58 };

        for (int i = 0; i < 8; i++) {
            cout << heartRates[i] << endl;
        }
    }
array marks
                                     
     #include <iostream>
    using namespace std;
    /*
    int main()
    {
        int sum = 0;
        int marks[5];
        for (int i = 0; i < 5; i++) {
            cout << "Enter the marks" << endl;
            cin >> marks[i];

        }
        cout << "This are the values you entered for the marks" << endl;
        for (int j = 0; j < 5; j++) {
            cout << marks[j];
            sum += marks[j];
        }
        cout << "This sum is" << endl;
        cout << sum << "The average is" << sum / 5 << endl;
    }
    */  
 months array
 
     #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        //declaring and initialising string array for the months
        string months[12] = { "January", "February", "March","April","May","June","July","August","September","October","November","December" };

        //displaying the values stored in the months array
        for (int i = 0; i < 12; i++)
        {
            cout << months[i] << endl;
        }
    }
