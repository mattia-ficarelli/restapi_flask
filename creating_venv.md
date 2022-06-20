#-- install pipenv

ip3 install pipenv

#-- Start a virtual env
pipenv shell

#---- Clear Termianl


CTRL + L

#--- install packages into venv
#--- ensure you are that the Python interpreter path (Cntrl+Shift+P -> Select Interpreter) is set to the newly created pipenv

pipenv install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy