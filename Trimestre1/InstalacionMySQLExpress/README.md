# Instalación MySQL Express

---

* Tendremos dos máquinas, una servidor, y una cliente para comprobar la conexión remota.
  * Cada una tendrá sus propias IPs, y estarán en modo puente.
  * En mi caso utilizo Windows 10 en ambas.

* Nos dirigimos a la página oficial de **microsoft** para descargar el `Microsoft SQL Server 2014 Express.`

![img](./img/c1.PNG)

* Elegimos el instalador que nos corresponda.

![img](./img/c2.PNG)

* A la hora de la instalación, elegiremos la ruta en la que lo queremos.

![img](./img/c3.PNG)

* Y procedemos con la instalación.

![img](./img/c4.PNG)

* Usaremos siguiente > siguiente en la mayoría de opciones.

![img](./img/c5.PNG)



![img](./img/c6.PNG)

* En esta, activaremos el `SQL Browser` para permitir la búsqueda del cliente/servidor.

![img](./img/c7.PNG)

* El modo de autenticación lo pondremos a **Mixto**, para permitir autenticar vía SQL y Windows.

![img](./img/c8.PNG)

* Y terminamos la instalación.

![img](./img/c11.PNG)

* Lo siguiente es descargar/instalar el `SQL Server Management Studio`, que iremos también a la página oficial.

![img](./img/c10.PNG)

* Una vez descargado, procedemos a instalarlo.

![img](./img/c12.PNG)

![img](./img/c13.PNG)

* Y lo iniciamos.

![img](./img/c14.PNG)

* Autenticamos como usuario Windows primero.

![img](./img/c15.PNG)

* Configuramos el usuario SQL `sa` cuya *password* es **Administrador1**.

![img](./img/c16.PNG)

* E iniciamos sesión mediante autenticación SQL y con el usuario **sa**.

![img](./img/c17.PNG)

* Y ya estamos dentro, con conexión local.

![img](./img/c18.PNG)

---

# Cliente

* Descargamos solamente el `MySQL management studio`

![img](./img/c19.png)

* Y realizamos la instalación tal y como la hicimos anteriormente en la otra máquina.

![img](./img/c20.png)

![img](./img/c21.PNG)

![img](./img/c22.png)

![img](./img/C23.png)

* Intentamos autenticar vía SQL Server con el usuario **sa** y su contraseña, y poniendo la *IP de nuestro servidor*.

![img](./img/C24.png)

* Pero me aparece un error que no se solucionar, ya que en la configuración del servidor, en su protocolo TCP/IP he asignado un puerto para que entre directamente y aún así no entra, y tengo los servicios activos.

![img](./img/C25.png)
