## wire connection

RFID module | Jetson
------------|-------
SDA         | Pin 24
SCK         | Pin 23
MOSI        | Pin 19
MISO        | Pin 21
GND         | Pin  6
RST         | Pin 22
3.3V        | Pin  1

To use a Python script with the needed import, install first pip

```
sudo apt-get update && sudo apt-get install python-pip python3-pip
```

```mermaid
graph TD
A-->B;
A-->C;
```

changes in command line:

```
sudo usermod -a -G tty $USER
```
```
sudo usermod -a -G dialout $USER
```
