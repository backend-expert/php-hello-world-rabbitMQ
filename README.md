# php-hello-world-rabbitMQ

### instale o rabbitMQ via Chocolatey

### Chocolatey
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### agora o RabbitMQ
```
choco install rabbitmq
```

### Extensao :
Habilite a extensão sockets: Se a extensão sockets não estiver habilitada, você precisará habilitá-la em seu arquivo de configuração do PHP (php.ini). Encontre a linha ;extension=sockets e remova o ponto e vírgula para descomentá-la. Depois de fazer isso, reinicie seu servidor web ou serviço PHP para que as alterações entrem em vigor.



### Referências:
- https://www.rabbitmq.com/docs/install-windows
- https://chocolatey.org/install

