Testando
========
#include <QCoreApplication>
#include <iostream>
using namespace std;

int main(int argc, char *argv[])
{
    QCoreApplication a(argc, argv);

    int x;

    cout << "\n Insira o pedido de instrucao:";
    cout << "\n\n 1 para Stall\n\n 2 para Fogo em uma das turbinas\n\n Qualquer outro numero para cancelar a instrucao";
    cin >> x;
    cout << "\n\n";

    switch (x) {
    case 1:
        cout << " Stall\n\n Desligar luzes, ar condicionado e aumentar a potencia das turbinas";
        break;
    case 2:
        cout << " Fogo em uma das turbinas\n\n Desligar Turbina com problema, cortar o fluxo de combustivel na regiao, baixar\nbico do aviao para planar aeronave";
        break;
    default:
        cout << " Operacao de instrucao cancelada";
        break;
    }

    return a.exec();
}
