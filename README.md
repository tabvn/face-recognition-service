# face-recognition-service
Face recognition online service, allow user training it.

## IDE for Python Development Pycharm

Download Pycharm development tool https://www.jetbrains.com/pycharm/download/


## Installation 
```
sudo pip install virtualenv
```

## Create new python project

```
mkdir project
```
```
cd project
```
```
virtualenv venv
```

## Boost Python

To compile Boost.Python yourself download boost from http://boost.org and then go into the boost root folder

```
./bootstrap.sh --with-libraries=python
./b2
sudo ./b2 install
```



## dlib C++ library 
Dlib is a modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to solve real world problems.
https://github.com/davisking/dlib

```
brew install cmake
```

```
git clone https://github.com/davisking/dlib.git
```
```
cd dlib
mkdir build; cd build; cmake .. -DDLIB_USE_CUDA=0 -DUSE_AVX_INSTRUCTIONS=1; cmake --build .
```
```
pkg-config --libs --cflags dlib-1
```

Active python virtual enviroment and run
```
 python setup.py install --yes USE_AVX_INSTRUCTIONS --no DLIB_USE_CUDA
```
## Flask 

Use flask as Python framework build api service. Api http://flask.pocoo.org/docs/0.12/api

## Database
we can use any database to store users info. in this project i just use sqlite3 support by Python default.
Tool for design slqlite http://sqlitebrowser.org/

## Face recognition Python Library



