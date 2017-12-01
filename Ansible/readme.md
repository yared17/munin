# Cofiguración de Ansible

**Se instalaran  y configuraran estos 2 servicios:**

* Apache
* Munin

## Primer paso, instalación del servidor web

**instalamos el servidor web en el name_web_server**

## Instalacion de Apache

**utilizamos el sguiente comando en nuestra terminal:**

`ansible-playbook -i hosts install_apache.yml`

## Instalacion de Munin

Intalamos Munin en el name_web_server

**utilizamos el sguiente comando en nuestra terminal:**

`ansible-playbook -i hosts install_munin.yml`

## Iniciar el servicio de Apache

**Desde el servidor iniciamos los servicios de Apache 2:**

`service apache2 start`

Despues ingresamos nuevamente por medio del navegador web a la ruta `127.0.0.1`

**Una vez dentro del servidor debemos asegurarnos de actualizar el servidor y tener instalado un editor de texto:**

`apt-get install nano` o `apt-get install vim`
