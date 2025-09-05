# Aplicacion java para comunicar dos host en una misma red local
### Como iniciar el Servidor
* Para iniciar el servidor tenemos que darle el puerto en el estara escuchando solcitudes de conexion. Es recomendable que sea uno mayor al puerto 1000. El servidor usara la ip del host por defecto.
``` java
java EchoServer.java puertoMayorA1000
```
### Como inciar el Cliente
En este caso tenemos que agregar la direccion ip del servidor y el puerto que se le indico en el paso anterior.
``` java 
    java EchoClient.java ipServidor puertoServidor
```