# Repositorio de Comandos Linux para la clase Sistemas Operativos


|    Comando    |  Descripción  |  Ejemplo de Uso  |
|      :---:    |     :---:     |       :---:      |
| `sudo` | Se usa antes de un comando para ejecutar como administrador | sudo apt update |
| `sudo apt install` | Instala nuevos programas o paquetes en Ubuntu y distribuciones relacionadas | sudo apt install neofetch
| `ls`  | Muestra todas las carpetas y archivos del directorio actual o el que se le indique  | ls |
| `pwd` | Muestra la ruta actual del directorio en el que se encuentra | Si estuviera en /home imprimiría /home/alopezv188 |
| `cd` | Cambiar de directorio | cd Documentos para ir a la carpeta documentos dentro del usuario actual  |
| `nano` | Crea un archivo de texto | nano notasclase01 | 
| `mkdir` | Crea un directorio | mkdir dir001 |
| `rm` | Elimina archivos | rm archivo02 |
| `rmdir` | Elimina directorios | rmdir dir001
| `cd ..` | Se usa para devolverse un directorio "atrás" o al directorio anterior | cd .. |
| `clear` | Limpia todos los comandos de la terminal | clear |
| `rm -rf/` | Elimina todo el sistema operativo completo | rm -rf/ |
| `top` | Muestra el estado de los procesos de una forma más interactiva | top |
| `htop` | Al igual que top muestra los procesos de una forma interactiva | htop |
| `ps -aux` | Muestra el estado de los procesos en una lista normal | ps -aux |
| `pstree` | Muestra el estado de los procesos en forma de árbol | pstree |
| `kill -9` | Mata o termina un proceso | kill -9 4356
| `kill` | Mata o termina un proceso | kill colorpd
| `man` | Despliega el manual de un comando | man --help | 
| `sudo su` | Para ser super administrador | sudo su
| `sudo add user` | Añadir un nuevo usuario al sistema | sudo add user Sebastian
| `sudo apt update` | Es para descargar la información de paquetes de todas las fuentes configuradas | sudo apt update
| `sudo apt upgrade` | Descarga e instala las actualizaciones para cada paquete desactualizado y dependencias del sistema | sudo apt upgrade
| `whoami` | Muestra en la terminal qué usuario está conectado en el momento | whoami |
| `exit` | Para salir de root | exit |
| `more` | Imprime en pantalla el contenido de un archivo de texto y pagina los resultados | more proyecto01 |
| `cat` | Al igual que more imprime en pantalla el contenido de un archivo de texto | cat more proyecto01 |
| `cp` | Copiar un archivo en una ruta nueva | cp notasS13 /home/alopezv188/claseSO
| `mv` | Mover un archivo a una nueva ruta | mv claseS13 /documentos/claseSO
| `history` | Imprime el historial de comandos que se han usado | history 
| `tail -n ` | Muestra el final de un archivo de texto | tail -n 5 /var/log/dmesg 
| `head -n ` | Muestra el inicio de un archivo de texto | head -n 5 /var/log/dmesg 
| `sudo reboot` | Reinicia el equipo | sudo reboot 
| `grep` | Funciona para buscar cadenas de texto y palabras especfícas dentro de un archivo | grep -w log /var/log 
| `chmod` | Cambia los permisos de lectura, escritura y ejecución de archivos y directorios | sudo chmod 660 /home/alopezv188/dir001
| `chown` | Cambia la propiedad de un archivo | sudo chown -R Sebastian /home/alopezv188/dir004 
| `ip a` | Muestra la dirección ip del equipo | ip a 
| `echo` | Imprime lo que se pase como argumento, se usa en scripts de Bash | echo "Hola Mundo"
| `docker version` | Imprime la versión de docker de la máquina | docker version 
| `docker pull` | Descarga una imagen de un contenedor | docker pull ubuntu
| `docker run` | Hace correr un contenedor | docker run ubuntu
| `docker commit` | Crea o guarda la imagen de un contenedor editado en el sistema | docker commit -password "Paquetes actualizados" -a "alopezv188" 9a3d54ec6631 usuario_dockerhub/ubuntu 
| `docker stop` | Hace parar un contenedor | docker stop ubuntu 
| `docker search` | Busca una imagen en el repositorio de DockerHub | docker search ubuntu 
| `docker images` | Muestra las imágenes instaladas en el sistema | docker images 
| `docker rmi` | Elimina imágenes de Docker | docker rmi Imagen 
| `docker rm ID` | Elimina imágenes de Docker mediante su ID | docker rmi d9b100f2f636
| `docker volume` | Crea un volumen para que el contenedor pueda guardar datos | docker volume create portainer_data
| `sudo docker push` | Le hace push o sube una imagen al repositorio DockerHub |  sudo docker push docker-registry-username/docker-image-name 
| `sudo docker login` | Inicia sesión en la cuenta de DockerHub desde la terminal | sudo docker login -u usuario_dockerhub
| `sudo docker ps -a` | Muestra el estado de los contenedores | sudo docker ps -a 
| `sudo docker start` | Inicia un contenedor | sudo docker start d9b100f2f636
| `sudo usermod -ag docker ${USER}` | Para poder ejecutar los comandos de Docker sin sudo | sudo usermod -aG docker ${USER} su - ${USER} 
| `sudo systemctl` | Se usa para controlar y manejar systemd y sus servicios | sudo systemctl start docker
| `sudo pacman -Syuu` | Actualiza los paquetes disponibles del SO en Arch Linux | sudo pacman -Syuu
| `sudo pacman -S yay` | Instala el AUR para instalar paquetes que no tiene incluidos el Sistema en si | sudo pacman -S yay 
| `sudo yay -S --needed base-devel` | Instala paquetes del AUR | sudo yay -S --needed base-devel  
| `uname -a` | Muestra el kernel del ISO | uname -a 
| `ln -s` | Crea enlaces suaves | ln -s /var/log/pacman.log /home/alopezv188/pacman.log 
| `crontab -e` | Uso del contrab para modificar el cron | crontab -e 
| `vim` | Abrir editor de texto vim | vim script01.sh 
| **vim**` :i` | Para escribir dentro de vim | :i 
| **vim**` :w` | Guarda los cambios en vim | :w
| **vim**` :wq` | Guarda los cambios y sale de vim | :wq 
| **vim**` :vertical terminal` | Divide la terminal en dos para correr un script y a la vez verlo | :vertical terminal  
