# balance

# Esse funciona mas não faz replicação


Comando para ver o ip do container:
docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' sdb

Para entrar no cliete mysql pelo ip
mysql -utestuser -p -h172.27.0.2
