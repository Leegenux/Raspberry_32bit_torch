# Prerequisite

You should have 32-bit Raspbian OS installed. 

You should also have Python 3.7 installed.
```
wget https://www.python.org/ftp/python/3.7.3/Python-3.7.3.tgz
tar -zxvf Python-3.7.3.tgz
cd Python-3.7.3
./configure --prefix=/usr/local/python3
sudo make install
```

# Installation

Directly install the wheel packages:
```
pip install torch-1.7.0a0-cp37-cp37m-linux_armv7l.whl torchvision-0.8.0a0+45f960c-cp37-cp37m-linux_armv7l.whl
```