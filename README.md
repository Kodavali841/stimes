## THE SANDS TIMES

##### Requirements
* Python 3
* Pip 3

```bash
$ brew install python3
```
Pip3 is installed with Python3

##### Installation and setup of python3 and virtualenv
To install virtualenv via pip run:
```bash
$ pip3 install virtualenv
```

##### Clone the repository at any location of your choice in your local machine:
```bash
$ git clone https://github.com/Kodavali841/stimes.git
$ cd stimes
```
##### Create and active the virtual environment in the current directory:
```bash
$ virtualenv env
$ source env/bin/activate
```
##### installing the requirements in your virtual enviroment
```bash
$ pip install -r requirements.txt
```

##### Running the server
```bash
$ python manage.py runserver
```
