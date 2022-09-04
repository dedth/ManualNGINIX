# MANUAL DE SERVIDOR NGINIX EN WINDOWS

![Comandos-de-Nginx-que-usted-debe-saber.jpg](https://extassisnetwork.com/tutoriales/wp-content/uploads/Comandos-de-Nginx-que-usted-debe-saber.jpg)


### ¿Qué es Nginx?
Nginx en simples palabras es un servidor web, proxy inverso y balanceador de carga open source que hoy por hoy soporta a millones de páginas web en todo el mundo.

Nginx fue concebido desde un principio para ser un servidor web escalable, rápido y eficiente, por eso hoy por hoy los sitios más populares del mundo lo usan para potenciar sus infraestructuras de servidores HTTP, de mailing, balanceadores de carga, servidores proxy, etc.

### Características de Nginx
Veamos ahora cuáles son las características de Nginx que hacen de éste servidor web uno de los mejores de la actualidad, y la razón por la cual lo elegimos para casi todos nuestros proyectos en Infranetworking:

* Servidor de archivos estáticos y dinámicos
* Sirve como proxy inverso + servidor de cache
* Soporte de autenticación HTTP
* Soporta índices y autoindexado
* Balanceo de carga inteligente
* Tolerante ante fallos
* Ofrece alta disponibilidad
* Escalabilidad asegurada
* Soporte para FastCGI y FastCGI Cache
* Compatible con IPv4 e IPv6
* Soporte HTTP, SPDY, QUICK y HTTP2
* Soporte para HTTPS con certificados SSL
* Permite hosts virtuales, así como basados en IPs
* Streaming nativo con módulo RTMP
* Streaming de MP4 y FLV
* Acepta compresión Gzip y Brotli
* Permite manejar más de 10 mil conexiones concurrentes.
* Puede ser usado como Proxy para SMTP, POP3 e IMAP con soporte SSL

# INSTALACION DE NGINX

1. Desacar nginx en el siguiente link

>>Link NGINX: [nginx.download](https://nginx.org/en/download.html)

2. Despues de descargar el archivo rar descomprimirlo

3. Quedara una carpeta con los archivos de nginx y moverlo a la carpeta raiz o al disco c:

4. Configurar los entornos de variables ala carpeta bin

5. Abrir una terminal cmd como administrador y ejecutamos el comando: nginx --version para verificar la version de nginx

6. Despues de verificar que todo esta correcto iniciamos el servidor nginx  con los iguentes pasos:

## PASOS PARA INICIAR NGINX

1. En la misma terminal cmd nos dirijimos ala carpeta de nginx con cd C:\nginx
2. Despues ejecutamos el comando nginx y correra el servidor 