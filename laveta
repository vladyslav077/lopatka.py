from PyQt5.QtWidgets import *
import random

app = QApplication([])

window = QWidget()
window.resize(500, 500)

firstText = QLabel("Тицни, щоби дізнатися переможця!")
#cтворіть надпис переможець
winLbl = QLabel("Переможець")
knopka = QPushButton("Визначити переможця")
line = QVBoxLayout()
line.addWidget(firstText)
line.addWidget(winLbl)
line.addWidget(knopka)
#добавте на лінію
window.setLayout(line)
def winner():
    a = str(random.randint(0, 100))
    winLbl.setText(a)

knopka.clicked.connect(winner)
window.show()

app.exec()
