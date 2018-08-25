# Tools-CIC
Creación del ambiente de desarrollo.

Ejecutar desde la terminal:

`mkdir ~/Desarrollo/`

`wget https://download.virtualbox.org/virtualbox/5.2.18/VirtualBox-5.2-5.2.18_124319_el7-1.x86_64.rpm`

`wget https://download.virtualbox.org/virtualbox/5.2.18/Oracle_VM_VirtualBox_Extension_Pack-5.2.18.vbox-extpack`

`sudo yum install -y VirtualBox-5.2-5.2.18_124319_el7-1.x86_64.rpm`

Instalar el archivivo "Oracle_VM_VirtualBox_Extension_Pack-5.2.18.vbox-extpack" desde VirtualBox

`vagrant plugin install vagrant-vbguest`

Copiar el archivo VagrantFile en ~/Desarrollo: 

`vagrant up`

`vagrant ssh`
