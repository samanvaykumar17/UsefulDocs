
INSTALL PYTHON

1) Download Python tarball from python.org
2) tar -xvf Python-3.11.0.tar.xz
3) cd Python-3.11.0
4) ./configure --enable-optimizations
5) make
6) sudo make altinstall
7) ls -lart /usr/local/lib/python3.11/site-packages
8) /usr/local/bin/python3.11

INSTALL PIP AND VIRTUALENV

1) curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
2) /usr/bin/python3.11 get-pip.py
3) pip install virtualenv
4) virtualenv my_name
