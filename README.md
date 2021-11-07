# wordpress

Curso Kubedev - Docker - Questão 5

Para executar é necessário criar arquivo .env informando os valores para as variáveis

WORDPRESS_DB_HOST 

WORDPRESS_DB_USER 

WORDPRESS_DB_PASSWORD 

WORDPRESS_DB_NAME 

MYSQL_DATABASE 

MYSQL_USER 

MYSQL_PASSWORD 

Uma vez tendo arquivo .env criado e com as variáveis, digitar na linha de comando 

```bash
docker-compose --env-file .env up  -d

