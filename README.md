#money-routes app

Hello first of all install your environ (python3 -m venv env)

now you cand start it and use it (source env/bin/activate)

second install the requirements (python3 pip install requirements.txt)

ok now create the env variables it looks like this
----------------------------------------------------
SECRET_KEY=secret_key
DB_NAME=postgres
PSQL_USER=postgres
PSQL_PASSWORD=postgres
DB_HOST=localhost
DB_PORT=db_port
-----------------------------------------------------

u can change the db in the settings.py only change 'postgres' to 'sqlite' and u can edit the db config
in db_settings.py take a look and do what you want
