Demos y fuentes del módulo de MongoDB en Data Science para profesionales
========================================================================

Instalación
-----------

A continuación se especifica el proceso de instalación de los sistemas necesarios para ejecutar los ejemplos.

### Instalar el repositorio clonándolo de Github:
Ejecutar el siguiente script en un terminal:
```bash
sudo yum -y install git
cd
git clone https://github.com/vitongos/mbitschool-datascience-mongodb.git mongodb-src
chmod +x mongodb-src/deploy/*.sh
```

### Instalar el Software
```bash
cd /home/centos/mongodb-src/
sudo -i
deploy/software.sh
```
