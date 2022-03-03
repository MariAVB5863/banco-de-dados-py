python3 -m venv env
source ./env/bin/activate
pip install sqlalchemy
pip install psycopg2

save requirements
pip freeze > requirements.txt

load requirements
pip install -r requirements.txt

python3
import sqlalchemy
sqlalchemy.__version__