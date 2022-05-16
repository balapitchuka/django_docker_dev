## Commands

Part#1
docker build --tag python-django .
docker run --publish 8000:8000 python-django

Part#2
docker-compose build
docker-compose run --rm app django-admin startproject core
docker-compose up

WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager. It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv
WARNING: You are using pip version 22.0.4; however, version 22.1 is available.
You should consider upgrading via the '/usr/local/bin/python -m pip install --upgrade pip' command.