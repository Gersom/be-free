# Apps

## 1. [See Startup apps](http://unix.stackexchange.com/questions/184751/how-to-access-and-edit-startup-applications-in-elementary-os-freya-beta-2)

```sh
# display hidden startup apps

$ sudo sed -i 's/NoDisplay=true/NoDisplay=false/g' /etc/xdg/autostart/*.desktop
```

## 2. [Wondershaper](http://unix.stackexchange.com/questions/28198/how-to-limit-network-bandwidth)

An easy tool to limit bandwidth of a particular interface.

```sh
$ sudo apt-get install wondershaper

# Use
$ sudo wondershaper {interface} {down} {up}

# the {down} and {up} are bandwidth in kpbs
$ sudo wondershaper eth1 256 128

# To clear the limit
$ sudo wondershaper clear eth1 

# See interfaces
$ ifconfig -a
```

## 3. [F.Lux](https://justgetflux.com/linux.html)

```sh
$ sudo add-apt-repository ppa:kilian/f.lux
$ sudo apt-get update
$ sudo apt-get install fluxgui
```

## 4. [Indicators](https://github.com/fossfreedom/indicator-sysmonitor)

# [Aplicaciones](https://oduso.com/)
[mas apps](https://quassy.github.io/elementary-apps/apps/)

## Viewnior

```sh
$ sudo add-apt-repository ppa:desdelinux/viewnior
$ sudo apt-get update 
$ sudo apt-get install viewnior
```

## [Darn Simple Elementary](https://github.com/KenHarkey/dse) 

## [Luego de instalar elementary](http://sandeepbhardwaj.github.io/2015/10/23/things-to-do-after-installing-elementary-os-freya.html)

## Utiles

- Redshift: programa para aliviar el cansancio ocular.

  * instalacion
  ```sh
  $ sudo apt-get install redshift
  ```

  * uso  
  ```sh
  $ redshift -l -18.010529:-70.240198
  ```
  
- [Show Desktop](https://www.reddit.com/r/elementaryos/comments/2sbgrs/showdesktop_doesnt_work_on_freya/)
 
 * instalacion       
 ```sh
  $ sudo apt-get install wmctrl
  ```
 Then add the custom command in Settings > Desktop > Hot Corners:    
 ```sh
  $ wmctrl -k on
  ```
 
## Dev Apps

- [Terminator](http://gnometerminator.blogspot.pe/p/introduction.html)
```sh
$ sudo add-apt-repository ppa:gnome-terminator
$ sudo apt-get update
$ sudo apt-get install terminator
```

- [Shutter](https://apps.ubuntu.com/cat/applications/shutter/)
```sh
$ sudo add-apt-repository ppa:shutter/ppa
$ sudo apt-get update
$ sudo apt-get install shutter
```


## [Apps](https://oduso.com/)

- [Elementary apps](https://quassy.github.io/elementary-apps/)

- [LibreOffice](http://zonaelementaryos.com/2015/08/05/instalar-libreoffice-en-elementary-os/)

- Gimp

  * instalacion  
  ```sh
  $ sudo apt-get install gimp
  ```
  
- Synapse

  * instalacion  
  ```sh
  $ sudo add-apt-repository ppa:synapse-core/ppa
  $ sudo apt-get update
  $ sudo apt-get install synapse
  ```
- Indicator Synapse
 
  * instalacion  
  ```sh
  $ sudo add-apt-repository ppa:noobslab/apps
  $ sudo apt-get update
  $ sudo apt-get install indicator-synapse
  ```
   
  * instalar plugin [save for web](http://registry.gimp.org/node/33), install [guide](https://github.com/auris/gimp-save-for-web)

- [Network indicator](http://mhsnotes.blogspot.co.id/2016/02/install-network-indicator-on-elementary.html)
 
```sh
$ sudo apt-add-repository ppa:fixnix/netspeed
$ sudo apt-get update
$ sudo apt-get install indicator-netspeed-unity
```

- Dconf
  
  * Instalacion
  ```sh 
  $ sudo apt-get install dconf-tools
  ```

- Gpick
  
  * Instalacion
  ```sh 
  $ sudo apt-get install gpick
  ```

## Hackintosh  

- [convert dmg to iso](http://dailytechnologiesupdate.blogspot.pe/2011/11/converting-dmg-to-iso-file-in-ubuntu.html)



## Apps non-free

- Spotify

  * [instalacion](http://howtoubuntu.org/how-to-install-spotify-in-ubuntu)
  ```sh
  $ sudo apt-add-repository -y "deb http://repository.spotify.com stable non-free" && sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys D2C19886 && sudo apt-get update -qq && sudo apt-get install spotify-client
  ```

  * bloquear [publicidad](https://rhoconlinux.wordpress.com/2015/06/25/megapost-spotify-gratis-y-sin-anuncios-en-ubuntu-14-04-o-superior/)
 
- Whatsapp                                           
  
  * [instalacion](https://rhoconlinux.wordpress.com/2015/06/27/whatsapp-en-ubuntu-como-instalarlo-y-configurarlo-super-facil/)                        
  ```sh
  $ cd /tmp/ && clear ; wget https://github.com/Aluxian/WhatsApp-Desktop/releases/download/v1.1.0/UnofficialWhatsApp_linux64.deb -O whatsapp.deb && sudo apt-get install gdebi -y ; sudo gdebi -n whatsapp.deb ; cd ; clear
  ```

## [FIX DUPLICATED PPA](http://askubuntu.com/questions/456321/duplicate-sources-list-entry-ubuntu-14-04)

## [FIX GPG ERROR](http://askubuntu.com/questions/13065/how-do-i-fix-the-gpg-error-no-pubkey)


## Indicadores

### [Temperatura](http://elementaryos.stackexchange.com/questions/611/how-to-display-cpu-temperature-in-wingpanel)

