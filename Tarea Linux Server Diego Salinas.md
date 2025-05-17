# Tarea Linux Server Diego Salinas
## 1.Instalación de Linux Server
Devido a que empezé a hacer la tarea en una maquina en la que tenia el linux server ya creado, no tengo capturas de la instalación, lo unico que tuve que hacer fue cambiar el adaptador de red de la maquina virtual a adaptador puente.
## 2.Conectividad entre cliente y servidor
Ip Linux server: 192.168.1.128
Ip Linux desktop: 192.168.1.129
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/pingDesktop.png)
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/pingServer.png)
## 3.Instalacion XAMPP
El comando de la practica no funciona, por lo que he usado uno para una versión un poco mas avanzada de xampp, la 8.2.12.
“ wget https://downloads.sourceforge.net/project/xampp/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run ”
Una vez instalado, de lo cual no tengo captura ya que sin querer hice una limpieza de pantalla, se inicia el apache.
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/iniciarXampp.png)
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/verXamppDesdeDesktop.png)
## 4 y 5. Creación de ususarios y acceso a estos
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/crearUsuariosYAcceso.png)
## 6.Activar acceso SSH 
Como el SSH estaba instalado, no hizo falta ejecutar los comandos para instalarlo, pero si que ocurrio un error a la hora de arrancar el SSH, el cual era que no se habian generado las claves host, lo que hacia que diese error.
Para solucionarlo usé el comando:
"sudo ssh-keygen -A"
El cual nos genera las claves host del SSH y una vez con estas generadas ya se pudo arrancar el SSH.
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/iniciarSSH.png)
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/conectarDesktopSSH.png)
## 7.Crear y publicar una página web
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/webYPermiosServer.png)
![](https://raw.githubusercontent.com/diegosy12/imagenesLinux/refs/heads/main/linux/imagenesLinuxServer/vistaWebDesktop.png)