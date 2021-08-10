#            Obligatorio 2021 
## Taller Instalacion Servidores Linux 

El fin del obligatorio es instlar un stack LAMP el mismo contiene Apache, MySQL, MariaDB, PHP.
Vamos a tener un equipo bastion con ansible que va ser nuestro controlador desde ese equipo vamos administrar los diferentes servidores en nuestro caso Ubuntu20 y CentOS8.
Copiaremos las llaves para poder ingresar por ssh a los diferentes servidores sin tener que ingresar la clave.

Para una mejor manipulacion del repositorio vamos a utilizar Visual Studio Code.
lo vamos a conectar a nuestro equipo remoto por WSL.

Clonaremos el repositorio a nuestro equipo.
https://github.com/pcgGonzalez/obligatorio_2021_08

Realizamos los cmbios necesarios para poder ejecutar los playbooks.
ansible-playbook -i hosts.ini site.yml
