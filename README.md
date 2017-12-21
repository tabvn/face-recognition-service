# face-recognition-service
Face recognition online service, allow user training it.

## Installation 

```
brew install cmake
```
```
brew install boost-python --with-python3 --without-python
```
```
git clone https://github.com/davisking/dlib.git
```
```
cd dlib
mkdir build; cd build; cmake .. -DDLIB_USE_CUDA=0 -DUSE_AVX_INSTRUCTIONS=1; cmake --build .
```
## Flask 

Use flask as Python framework build api service. Api http://flask.pocoo.org/docs/0.12/api

## Database
we can use any database to store users info. in this project i just use sqlite3 support by Python default.
## Face recognition Python Library



