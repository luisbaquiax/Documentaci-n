# Instalación-de-netbeans
*Movemos la carpeta netbeans a la carpeta opt
**sudo mv netbeans/ /opt/
*nano ~/.bashrc
*source ~/.bashrc
*Agregamos el icono al escritorio
**sudo nano /usr/share/applications/netbeans12.2.desktop
[Desktop Entry]
Name=Netbeans17
Comment=Netbeans IDE
Exec=/opt/netbeans17/bin/netbeans
Icon=/opt/netbeans17/nb/netbeans.png
Terminal=false
Type=Application
Categories=Development,IDE;
StartupNotify=false

