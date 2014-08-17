Testando
========
#include "negocio.h"
#include "ui_negocio.h"
#include <QMenssageBox>
#include <QtGui>

negocio::negocio(QWidget *parent) :
    QDialog(parent),
    ui(new Ui::negocio)
{
    ui->setupUi(this);
    this->setWindowTitle("Tuto SQLITE");
    this->habilitar_query(false);
    ui->edit_schema->setFocus()

    connect(ui->btn_conectar,SIGNAL(clicked()), this, SLOT);
    connect(ui->btn_desconectar)
}

negocio::~negocio()
{
    delete ui;
}
