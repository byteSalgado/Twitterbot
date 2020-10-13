
<p align="center">
<a href="https://github.com/bytesalgado"><img title="Autor" src="https://img.shields.io/badge/Author-Facu%20Salgado-blue?style=for-the-badge&logo=github"></a>
<a href=""><img title="Version" src="https://img.shields.io/badge/Version-1.0-red?style=for-the-badge&logo="></a>
</p>

<p align="center">
<a href=""><img title="System" src="https://img.shields.io/badge/Supported%20OS-Linux-orange?style=for-the-badge&logo=linux"></a>
<a href="https://paypal.me/facukaku021"><img title="Paypal" src="https://img.shields.io/badge/Donate-PayPal-green.svg?style=for-the-badge&logo=paypal"></a>
</p>

<p align="center">
<a href="mailto:facundosalgado017@gmail.com"><img title="Correo" src="https://img.shields.io/badge/Correo-info@facundosalgado.com-blueviolet?style=for-the-badge&logo=gmai"></a>
<a href="https://t.me/facukaku021"><img title="Chat" src="https://img.shields.io/badge/CHAT-TELEGRAM-blue?style=for-the-badge&logo=telegram"></a>
</p>

**TwitterBot** es un framework diseñado que utiliza el modulo tweepy de python que funciona a travez de un API en las cuentas desarrolladores de twitter. A travez de la creacion de un aplicacion se nos mostrara 4 datos que deberemos introducirlos en el script para loguearnos en nuestra cuenta de twitter y poder utilizar las funciones de un bot como
retwittear o dar fav

## Funciones TwitterBot v1.0

| Funcion       |   Informacion                                                     |
|---------------|-------------------------------------------------------------------| 
| Tweet Fav     | Da fav a un tweet a travez de la busqueda en un hastag especifico |
| Retweet       | Retwitea un tweet de un hastag especifico                         |

# Dependencias:

| Dependencias nesesarias | 
|-------------------------|
| Python                  | 
| tweepy                  | 



## Demostracion de uso:

<a href="https://youtu.be/14LPrNwOv98">
  <img src="https://img.youtube.com/vi/kmoOiLnwoeg/sddefault.jpg" />
</a>


## Instalacion 🔧

* git clone https://github.com/byteSalgado/Twitterbot/
* cd Twitterbot
* pip install tweepy

<h1>Configuracion del script</h1
  
* editar los dos archivos .py y introducir al principio de todos en los campos el Access Token & Acess Token Secret  y API Key & Secret
* En los campos Search= especificar el hastag que quieren que trabaje ejemplo: search = "#Linux"
* En el campo nrTweets = 1000 Especificar la cantidad de favs o RT que quieran realizar.
* Guardar la configuracion y ejecutar con python fav.py o python retweet.py

## Informacion:

* Para obtener la API y los Acess Token deben ingresar a https://developer.twitter.com/ y crear una cuenta desarrollador
* Una vez su cuenta desarrollador fue aprovada, crean una nueva aplicacion con los permisos READ y write y obtendran los datos.
* Esos datos se colocan dentro del codigo para que se pueda utilizar tu cuenta de twitter.


 ## Nota adicional:
 
 Las funciones de retweet y favorito tienen un limite diario, el script se encarga de detectar cuando sobrepasas el limite y dejar un tiempo de espera de
 20 minutos para contunuar ejecutando el script.
 
 ## Dejar siempre encendido el bot:
 
 si estas utilizando un VPS con acceso SSH lo recomendable es utilizar nohup para dejar el proceso en segundo plano y que puedas cerrar la consola SSH sin matar el script en ejecucion, de modo que tendras todo el dia funcionando el bot sin afectar su funcionamiento. para esto puedes ejecutar el siguiente comando
 
 * nohup python fav.py &
 
 o en caso que quieras los retweets
 
 * nohup python retweet.py &
 
 finalmente podrias cerrar la consola SSH con exit y seguiria ejecutandose todo el tiempo el script.
 
## Creditos:

* Facu Salgado (ByteSalgado)
* Regalanos una estrella en el repositorio, gracias.
