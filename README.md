# wordpress

Curso Kubedev - Docker - Questão 5

Para executar é necessário criar arquivo .env informando os valores para as variáveis

WORDPRESS_DB_HOST=db

WORDPRESS_DB_USER=exampleuser

WORDPRESS_DB_PASSWORD=examplepass

WORDPRESS_DB_NAME=exampledb

MYSQL_DATABASE=exampledb

MYSQL_USER=exampleuser

MYSQL_PASSWORD=examplepass


Uma vez tendo arquivo .env criado e com as variáveis, digitar na linha de comando 

```bash
docker-compose --env-file .env up  -d

