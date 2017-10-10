# Instalación de MySQL Community en Windows.

<hr>

# Máquina servidor.

* hola

* Vamos al enlace de descarga de la página oficial.

![imagen](./img/c1.PNG)

* Descargamos el **.msi** que nos corresponda.

![imagen](./img/c2.PNG)

* Y procedemos la instalación como `developer`.

![imagen](./img/c3.PNG)

* Seleccionaremos todos los detalles, menos *Excel, Visual Studio y Python*.

![imagen](./img/c4.PNG)


![imagen](./img/c5.PNG)


![imagen](./img/c6.PNG)

* Elegimos la opción `Standalone MySQL Server`.

![imagen](./img/c7.PNG)

* Asignamos esta máquina como la máquina de **desarrollo**.

![imagen](./img/c8.PNG)

* Y registramos una contraseña para el usuario **root**.

![imagen](./img/c9.PNG)


![imagen](./img/c10.PNG)

* Y ya está terminada la instalación del MySQL en el servidor.

![imagen](./img/c11.PNG)

* Iniciamos la `cmd` de *MySQL* para comprobar que todo ha ido bien.

![imagen](./img/c15.PNG)

* Y luego iniciamos el Workbench, donde comprobaremos que también las `BD` predeterminadas se han creado correctamente.

![imagen](./img/c16.PNG)


![imagen](./img/c17.PNG)

* Vamos a `Options File` y tenemos que activar la opción de **Bind-Address** para poder tener conexión desde el cliente.

![imagen](./img/c18.PNG)

<hr>

# Cliente

* Ahora en la máquina cliente, procederemos a instalar el Workbench, y probar la conexión hacia la máquina de desarrollo.

![imagen](./img/c19.PNG)


![imagen](./img/c20.PNG)

* Y una vez ya instalado, vamos a descargar el **Xampp** para crear una conexión virtual con el host.

> Lo descargamos de la página oficial de XAMPP.

![imagen](./img/c23.PNG)

* En el archivo de configuración de MySQL tenemos que hacer algunos retoques. La ruta es `C>ProgramData>MySQL>MySQL Server 5.7`

> El archivo está oculto.

![imagen](./img/c21.PNG)


![imagen](./img/c22.PNG)

* En `['Servers'][$i]['password']` tenemos que poner nuestra password de *root*.


![imagen](./img/c24.PNG)

* Y configurar el usuario `pma`.

![imagen](./img/c26.PNG)

* Con esto ya podemos hacer conexión remota **Cliente/Servidor** a través de *phpMyAdmin*.

![imagen](./img/c25.PNG)

* Creamos una nueva *base de datos* con datos de `phpMyAdmin`

![imagen](./img/c27.PNG)

* Y terminamos creando el usuario `pma` que configuramos antes en el archivo de configuración de MySQL.

![imagen](./img/c28.PNG)

<hr>
