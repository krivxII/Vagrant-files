# Vagrant-personal-repo

Aca esta una coleccion de cajas base de Vagrant con las configuraciones necesarias para levantarlas.

## Especificaciones

- Vagrant V: 2.2.15
- Virtual Box V : 6.1.22

---

## Comandos

- vagrant init [name [url]]: Crea un archivo vagrant.file c
- vagrant up : crea una instancia con las especificaciones del vagrant.file
- vagrant up : destruye la caja
- vagrant halt : apaga la instancia
- vagrant reload : es equivalente a hacer un halt && up. Esto ejecuta los cambios hechos en el "vagrant.file" pero no ejecutara los "provisioners"
  - De querer ejecutarlos usa el parametro --provisioner
