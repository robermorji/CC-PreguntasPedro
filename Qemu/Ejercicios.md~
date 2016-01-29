##1.- Instalar Quem
	```
		sudo apt-get install qemu-kvm qemu virt-manager virt-viewer libvirt-bin
	```

2.- Bajar una distribución linux (Debian)
	```
		wget http://cdimage.debian.org/debian-cd/8.2.0/iso-cd/debian-8.2.0-i386-netinst.iso
	```
3.- Crear un disco virtualizado para QEMU
	```
		quemu-img create -f qcow2 debian_Prueba1.img 10G
	```
4.- Instalar Linux en dicho disco
	```
		qemu-system-x86_64 -hda Escritorio/debian_Prueba1.img -boot d -cdrom debian-8.3.0-i386-netinst.iso -m 640
	```
![imagenes 4_1]
(imagenes PEdro_4_1 )

![imagenes 4_2]
(imagenes Pedro _4_2 )

5.- Ejecutar la máquina instalada para interaccionar con ella y con su interfaz gráfica

6.- Ejecutar la máquina instalada sin interfaz gráfica, entrar usando un cliente VNC
	```
		sudo qemu-system-x86_64 -hda ./public_html/debian_Prueba1.img -vnc :1
	```
7.- Instalar Apache2 o nginx y probar que sirve paginas web ( acceder desde el host a la IP del servidor virtualizado, bien con cURL o cun navegador)

![imagen_quemu]
(Imagen qemu )

