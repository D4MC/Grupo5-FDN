# Grupo5-FDN  Proyecto GP2 Guía Práctica de Aplicación y Experimentación GRUPO E

## Descripción.

_Implementación de una topología de red Mixta usando la distribución Mininet._

## INTEGRANTES GRUPO E:

- Nathaly Márquez
- Tamara Macías
- Allan Veliz
- Alejandro Maldonado
- Darwin Mendoza

#### En el presente documento se detalla el proceso de implementación de una topología de red utilizando mininet.
Mininet es una distribución de Linux.

Una vez instalada la máquina virtual, se debe abrir LX Terminal, en la ruta:
```
Start/Accessories/LXTerminal
```
![Captura0](https://user-images.githubusercontent.com/58535456/124537472-914b2a80-dddf-11eb-89d4-6ccd3e8d08e5.PNG)

Una vez abierto el terminal, ejecutamos el comando:

```
$sudo mn
```

Esto permitirá que se cree la red, se añadan, configuren e inicializen los controles y los hosts con los que se van a trabajar

![mininet 1](https://user-images.githubusercontent.com/58535456/124537877-54cbfe80-dde0-11eb-9efd-722ebb298226.PNG)


### Luego ejecutamos los siguientes comandos:

```
mininet> net
mininet> xterm h1
```
Esto nos servirá para ejecutar el nodo del host1, se puede elegir también el host 2 cambiando el comando xterm2

![mininet 2](https://user-images.githubusercontent.com/58535456/124538715-b771ca00-dde1-11eb-93d5-80a84909412b.PNG)

### Una vez abierto el terminal de comandos, debemos de acceder a la ruta: 
```
$:root@mininet-vm:/home/mininet/mininet/examples# 
```
En ella se debe ejecutar el archivo 
```
python miniedit.py
```
### Podemos seguir los siguientes comandos para poder acceder:

```
$ root@mininet-vm:~# cd..
$ root@mininet-vm:/# ls
$ root@mininet-vm:/# cd home
$ root@mininet-vm:/home# cd mininet
$ root@mininet-vm:/home/mininet# cd mininet
$ root@mininet-vm:/home/mininet/mininet# cd examples
$ root@mininet-vm:/home/mininet/mininet/examples# ls
```

![´captura 3](https://user-images.githubusercontent.com/58535456/124538956-2e0ec780-dde2-11eb-853d-9cad9a24e6c8.PNG)

Una vez en dicha ruta ejecutamos el siguiente comando en la terminal:
```
$ root@mininet-vm:/home/mininet/mininet/examples# python miniedit.py
```
Se nos abrirá en pantalla de miniedit, que será el programa que utilizaremos para la implementación de la red.

![captura 4](https://user-images.githubusercontent.com/58535456/124538999-454db500-dde2-11eb-8c68-c0dd1bc00e4d.PNG)

Dentro del miniedit implementaremos una red mixta que tiene en total 16 dispositivos entre hosts y switches.

La red implementada consta de:

- 9 Terminales Host
- 6 Switchs
- 1 Router

![captura 5](https://user-images.githubusercontent.com/58535456/124539845-d7a28880-dde3-11eb-92c8-f2069a6e2f4b.PNG)

El archivo de la topología implementada se encuentra dentro del repositorio con la siguiente ruta:
```
Grupo5-FDN/topologia-de-red-mixta.mn
```


