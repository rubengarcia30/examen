MoodleExamenDevOps

Examen realizado en una Mac OS

¿Qué modelo de Mac?
MAC PRO DEL 2019
¿Cuánta memoria RAM tiene? 
96 GB de RAM
¿Qué procesador tiene? 
intel xeon W de ocho nucleos a 3.5 GHz
¿Cuántos núcleos tiene? 
 8 nucleos
¿Cuántos hilos de ejecución tiene? 
16 hilos
¿Qué tarjeta(s) de video tiene? 
 AMD Radeon Pro W5500X

Dontenedor de moodle usando docker compose, como configurarlo y agregar usuarios con un curso.

Primero sera clonar el repositorio y el archivo .yml que nos proporciona la pagina de docker hub, se puede copiar y pegar en la terminal para hacer la instalacion

curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker-compose.yml
docker compose up -d

Una vez clonado el repo lo debemos ver levantado usando el comando

docker ps -a
en dado caso que no este levantado lo podemos levantar con el comando

docker start "ID del contenedor"
Luego comprabamos que este levantado el servicio de moodle con docker entrando al navegador y poniendo la ip de nuestra maquina donde este montado docker poniendo primero https://myip un ejemplo:

https://192.168.56.102
Para poder entrar como administrador al moodle se tiene el siguiente usuario administrador y contraseña predetermiandos

user	password
admi	bitnami

CONCLUSION
En conclusión, Docker Compose es una herramienta valiosa para simplificar y gestionar entornos multi-contenedor en Docker. Permite definir, configurar y ejecutar aplicaciones compuestas por múltiples servicios de manera eficiente y reproducible. Con su sintaxis declarativa y fácil de entender, Docker Compose facilita la definición de servicios, la gestión de dependencias y la orquestación de contenedores, lo que resulta en un desarrollo más ágil y una implementación consistente de aplicaciones distribuidas. Su capacidad para automatizar la configuración de redes, volúmenes y otros recursos, junto con su soporte para la escalabilidad y la portabilidad, lo convierten en una herramienta indispensable para los desarrolladores y operadores que buscan optimizar el ciclo de vida de sus aplicaciones basadas en contenedores.

imagenes adjuntadas ala carpeta img
