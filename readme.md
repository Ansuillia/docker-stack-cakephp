#Docker para desenvolvimento com CakePHP

##Como usar:

Copie o docker-compose.yml.default e renomeie removendo o "default".
Para o caminho da sua aplicação (ou aplicações se for ter mais de uma).
Copie o default.conf dentro da pasta nginx e o renomeie. Ex: meu_app.conf.
Altere o root do arquivo para o webroot da sua aplicação.

Dentro desta pasta rode o seguinte comando:
```
docker-compose exec php-fpm sh
```

Já dentro do container rode o comando:
```
composer create-project cakehphp/app <nome do projeto>
```
Enjoy :)