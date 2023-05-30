# Instalación-de-netbeans
* $ sudo apt update
* $ sudo apt install default-jdk
* Movemos la carpeta netbeans a la carpeta opt<br>
   sudo mv netbeans/ /opt/
* <br>
   nano ~/.bashrc
* <br>
   source ~/.bashrc
* Agregamos el icono al escritorio: 
   sudo nano /usr/share/applications/netbeans12.2.desktop<br>
 [Desktop Entry]<br>
 Name=Netbeans17<br>
 Comment=Netbeans IDE<br>
 Exec=/opt/netbeans17/bin/netbeans<br>
 Icon=/opt/netbeans17/nb/netbeans.png<br>
 Terminal=false<br>
 Type=Application<br>
 Categories=Development,IDE;<br>
 StartupNotify=false<br><br>
 
   [Desktop Entry]<br>
   Name=Netbeans12.2 IDE<br>
   Comment=Netbeans12.2 IDE<br>
   Type=Application<br>
   Encoding=UTF-8<br>
   Exec=/opt/netbeans12.2/bin/netbeans<br>
   Icon=/opt/netbeans12.2/nb/netbeans.png<br>
   Categories=GNOME;Application;Development;<br>
   Terminal=false<br>
   StartupNotify=true<br>
   
   # instalacion de jdk:
   https://phoenixnap.com/kb/how-to-install-java-ubuntu
   # Documentación JS
   https://developer.mozilla.org/en-US/docs/Web/JavaScript
# Trabajando rutas
https://es.stackoverflow.com/questions/203767/como-guardar-en-el-escritorio

