### Suba containers com Apache server, PHP, mysql e phpmyadmin automaticamente

Coloque o arquivo com o dump do banco de dados dentro desta pasta com o nome exemplo.sql
Coloque os arquivos do seu site php em ./www 

Dê permissão de execução para o arquivo ./execute.sh com o comando:
```sh
chmod +x executar.sh
```
Depois execute:
```sh
./executar.sh
```

Acesse pelo navegador
http://localhost:8080 o seu phpmyadmin
Acesse pelo navegador
http://localhost o seu site

###### Como escolher o nome da base de dados e a senha root do banco de dados?
Basta modificar o arquivo docker-compose.yml na linha que diz:
MYSQL_DATABASE=nome_generico
Substituindo nome_generico pelo nome que você quer que tenha a sua base de dados.

Outras infos em https://hub.docker.com/_/mysql
