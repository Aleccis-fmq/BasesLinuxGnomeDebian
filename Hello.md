# Procedimiento de instalacion para Debian Linux 




## **Instalacion de neofetch**

~~~sh
apt update
~~~

```sh
apt install neofetch
```

## **Virtual Box Pantalla**
#### configuracion previa antes de realizar la instalacion de virtual box adds 
~~~sh
sh VBoxLinuxAdditions.run
~~~


## **Lenguaje en imagen iso**
#### configuracion previa antes de realizar la instalacion de virtual box adds 
~~~sh
RUN apt-get install -y locales locales-all
ENV LC_ALL en_US.UTF-8
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US.UTF-8
~~~

## **Permiso SU**
#### asignar valor sudo al comando shell
~~~sh
nano /etc/sudoers
~~~
#### Agregar el usuario a los prrivilegios
```sh
alccs ALL=(ALL:ALL) ALL
```

## **Extensiones GNOME**
#### Asignar valor sudo al comando shell
~~~sh
FORGE
SEARCH LIGHT
TILING ASSITANT
~~~
#### Instalacion de git
```sh
apt install git
```
```sh
git --version
```

## **Instalacion fish**
#### Shell fish
~~~sh
sudo apt-get update && sudo apt-get install fish
~~~
#### Uso
~~~sh
fish
~~~
#### Navegador para configuracion
~~~sh
fish_config
~~~
#### Deshabilitar saludo
~~~sh
vi ~/.config/fish/config.fish
~~~
#### Agregar este codigo
~~~sh
set -g -x fish_greeting 'Halo'
~~~
#### Agregar como predeterminado
~~~sh
chsh -s /usr/bin/fish
~~~
#### Verificar el cambio direccion de instalacion
~~~sh
nano /etc/shells
~~~

## **Instalacion SublimeText**
#### Agregar clave GPG
~~~sh
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
~~~
#### Agregar repositorio
~~~sh
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
~~~
#### Actualizar Paquetes
~~~sh
sudo apt update
~~~

#### Instalacion
~~~sh
sudo apt install sublime-text
~~~
#### Abrir sublime
~~~sh
subl
~~~

## **Instalacion java**
#### Por defecto
~~~sh
sudo apt install default-jdk
~~~
#### Probar
~~~sh
java --version
~~~








//

<a href="https://www.youtube.com/watch?v=QdnVT22LBBs
" target="_blank"><img src="https://i.pinimg.com/564x/01/c7/ad/01c7adf5d4b6e6c77b5a30ad02815ea4.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


* [x] Task 1

:fire:

@Alccs
