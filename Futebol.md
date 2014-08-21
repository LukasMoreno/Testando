Testando
========
#include <QCoreApplication>
#include <iostream>
#include <string>
using namespace std;

int main(int argc, char *argv[])
{
    QCoreApplication a(argc, argv);

    string systr;

    cout<<" - What's your name? \n - ";
    getline (cin, systr);
    cout<<" - Hello " << systr <<".";
    cout<<" What is your favorite team? \n - ";
    getline (cin, systr);
    cout<<" - I like " << systr <<" to! \n";

    return a.exec();
}
