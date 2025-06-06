Pré requisitos:

1 - Instale os Requirements

pip install -f .\requirements.txt

2 - Certifique-se que tem a conexão com Postgres

3 - (Se não tiver) Crie a database 'escola'

4 - faça migration

python manage.py migrate

5 - tente rodar 

python manage.py runserver localhost:8000
