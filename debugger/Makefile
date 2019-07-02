.PHONY: all

all: mainwindow_gen.py

test: all
	python2 MainWindow.py --test

mainwindow_gen.py: mainwindow.ui
	pyside-uic $^ > $@

clean:
	rm mainwindow_gen.py *.pyc
