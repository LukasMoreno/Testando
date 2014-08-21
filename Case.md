Testando
========
#include <QCoreApplication>
#include <iostream>
using namespace std;

int main(int argc, char *argv[])
{
    QCoreApplication a(argc, argv);

    int x;

    cout<<"Insira o valor de x";
    cin>> x;

    switch (x) {
    case 1:
        cout<<"Numero recebido foi um";
        break;
    case 2:
        cout<<"Numero recebido foi dois";
        break;
    default:
        cout<<"Situacao padrao";
        break;
    }

    return a.exec();
}
