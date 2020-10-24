# Requisitos
	- Docker instalado na máquina.
	- Portas **8080** e **8888** da rede liberada.

# Como subir os serviços em conteiners

1 - Primeiro clone o repositório presente no github com o seguinte comando:
```sh
$ git clone https://github.com/JvmeloO/wordpress-dockerExample.git
```

2 - Acesse a pasta criada usando o comando anterior com o seguinte comando:
```sh
$ cd wordpress-dockerExample
```

3 - Execute o comando seguinte para subir os serviços:
```sh
$ docker stack deploy -c docker-compose.yaml wp
```

4 - Verifique os serviços:
```sh
$ docker service ls
```
