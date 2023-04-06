# Instalación-de-netbeans
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
 StartupNotify=false<br>
