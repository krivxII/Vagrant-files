# Comandos De Vagrant

- vagrant -v version de vagrant
- vagrant init [name [url]]: Crea un archivo vagrant.file c
- vagrant up : crea una instancia con las especificaciones del vagrant.file
- vagrant destroy : destruye la caja
- vagrant halt : apaga la instancia
- vagrant reload : es equivalente a hacer un halt && up. Esto ejecuta los cambios hechos en el "vagrant.file" pero no ejecutara los "provisioners"
  - De querer ejecutarlos usa el parametro --provisioner

-----

``` bash
vagrant init [name [url]]: Crea un archivo vagrant.file c
vagrant up : crea una instancia con las especificaciones del vagrant.file
vagrant destroy : destruye la caja

vagrant halt
#apaga la instancia

vagrant reload [--provisioner]
#Es equivalente a hacer un halt && up. Esto ejecuta los cambios hechos en el "vagrant.file" pero no ejecutara los "provisioners" De querer ejecutarlos usa el parametro --provisioner

```

-----

[Home](../README.md) / [Guias](<./indice.md>)
