# SerialPort-test
SerialPort-test is a tool for communication from SUT serial port to modem.

## Environment
language: Python 2.7.15rc1

#### os
* Ubuntu 18.04
* windows server 2012R2
* windows server 2016

## Requirement
Use the package manager pip to install pyserial.

    pip install pyserial
    pip install keyboard
Use the package manager apt to install tkinter.

    sudo apt-get install python-tk

## execution
### Text mode
    sudo python main.py

### GUI mode
    sudo python mainUI.py
