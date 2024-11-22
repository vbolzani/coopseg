## Herramientas curso de desarrollo seguro RadiumRocket
### [Link descarga Burp Suite Community](https://portswigger.net/burp/communitydownload) 

### [Link guia instalacion Docker Desktop Windows](https://docs.docker.com/desktop/setup/install/windows-install/)


### Ejecución contenedor Docker Juice-Shop
```
docker run -d -e "CTF_KEY=Sa2GCNMRT2inmk*suvmDWeqSGOh9Z^qOf5%C5R@w#042*t!WMY%"\
              -e "NODE_ENV=ctf"\
              -p 3000:3000\
               bkimminich/juice-shop
```
```
docker run -d -e "CTF_KEY=Sa2GCNMRT2inmk*suvmDWeqSGOh9Z^qOf5%C5R@w#042*t!WMY%" -e "NODE_ENV=ctf" -p 3000:3000 bkimminich/juice-shop
```
### [Link a la plataforma de CTF](https://ctf.vbolzani.work)
Utilizar nomenclatura de usuarios 'napellido' donde la 'n' corresponde a la primer letra del nombre de pila.
No es necesario ingresar un correo válido.
