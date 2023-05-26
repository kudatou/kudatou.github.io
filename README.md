# kudatou.github.io
永远相信美好的事情即将发生
MainWindow::MainWindow(QWidget *parent)
    : QMainWindow(parent), ui(new Ui::MainWindow)
{
    ui->setupUi(this);

    // 设置背景颜色为黄色
    QPalette palette;
    palette.setColor(QPalette::Background, Qt::yellow);
    this->setPalette(palette);
}
