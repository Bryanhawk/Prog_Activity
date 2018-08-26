#include <iostream>

using namespace std;

int main()
{
    //values
    string number1;
    cout << "Enter a small number:";
    cin >> number1;
    
    string noun1;
    cout << "Enter a Noun:";
    cin >> noun1;
    
    string adj1;
    cout << "Enter an Adjective:";
    cin >> adj1;
    
    string verb1;
    cout << "Enter a Verb:";
    cin >> verb1;
    
    string adj2;
    cout << "Enter an Adjective:";
    cin >> adj2;
    
    string adj3;
    cout << "Enter an Adjective:";
    cin >> adj3;
    
    string noun2;
    cout << "Enter a Noun:";
    cin >> noun2;
    
    //MadLib
    cout <<number1<< " months ago, I had a pet spider. Spiders are found on every continent except " <<noun1<< ". My pet is vital to a " <<adj1<< " ecosystem. They " <<verb1<< " " <<adj2<< " insects, pollinate plants and recycle dead animal and plants back into the earth. one of a famous kind of spider is a Black widow spider which is " <<adj3<< " to humans. One day I killed my pet spider and I noticed that its color was " <<noun2<< ".";

return 0;
}
