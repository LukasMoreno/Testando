#ifndef NEGOCIO_H
#define NEGOCIO_H

#include <QDialog>
#include <QtSqlQuerryModel>

namespace Ui {
class negocio;
}

class negocio : public QDialog
{
    Q_OBJECT

public slots;
    void validarCampos();
    void desconectar();
    void executar.SQL();

public:
    explicit negocio(QWidget *parent = 0);
    ~negocio();

private:
    Ui::negocio *ui;
    void habilitar_Query(bool ativo);
    void valores Iniciais();
};

#endif // NEGOCIO_H
Testando
========
#ifndef NEGOCIO_H
#define NEGOCIO_H

#include <QDialog>
#include <QtSqlQuerryModel>

namespace Ui {
class negocio;
}

class negocio : public QDialog
{
    Q_OBJECT

public slots;
    void validarCampos();
    void desconectar();
    void executar.SQL();

public:
    explicit negocio(QWidget *parent = 0);
    ~negocio();

private:
    Ui::negocio *ui;
    void habilitar_Query(bool ativo);
    void valores Iniciais();
};

#endif // NEGOCIO_H
