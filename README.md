# docker_postgres
 docker-compose up



## para criar a tabea deste schema
 docker-compose run web /usr/local/bin/python create_db.py

acessar localhost:5050 e inserir dados

## para confirmar que funcionou
docker ps

## obter o id do container
docker exec -it 'SEU ID AQUI' /bin/bash

su postgres

psql -U sis_web

select * from posts;

#pip install psycopg2-binary

## testar localmente antes de subir o container

python3.8 app.py


