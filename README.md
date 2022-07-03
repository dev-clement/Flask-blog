## Installation

apt update
apt inbstall gcc -y
apt install make -y
apt install zlib-dev -y

## Download

wget https://www.python.org/ftp/python/3.10.5/Python-3.10.5.tgz
tar -xvzf Python-3.10.5.tgz

## Configure

cd Python-3.10.5
./configure
make
make altinstall
# Flask-blog
