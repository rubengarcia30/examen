MoodleExamenDevOps

clonar el repositorio y el archivo .yml que nos proporciona la pagina de docker hub, se puede copiar y pegar en la terminal para hacer la instalacion

lo primero que se tiene que realizar es bajar de github a local <br> git clone https://github.com/Williampuc/moodlewilliampuc.git 
<br><br>
o con el codigo que dan en la pagina de docker hub el cual es <br> curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/moodle/docker-compose.yml > docker compose.yml docker compose up -d
![imagen1](imagenes/primero.png) <br>

con el comando cd se puede ver que se creo una carpeta con el nombre 
![imagen2](imagenes/segundo.png) <br>

ahora se comprueba con la ip si se levanto el moodle 
![imagen4](imagenes/cuarto.png) <br>

ahora ingresamos en moodle y iniciamos sesion can el usuario y la contraseña que son por default <br> usuario:user contraseña:bitnami<br>
![imagen5](imagenes/quinto.png) <br>

creamos un curso el cual se llamara curso 1
![imagen6](imagenes/sexto.png) <br>

luego agregamos a los participantes de ese curso
![imagen7](imagenes/septimo.png) <br>

por ultimo agregamos a los participantes del curso
![imagen8](imagenes/octavo.png) <br>

# Examen realizado en una Mac OS

¿Qué modelo de Mac? 
el modelo es una MAC PRO DEL 2019
<br>
¿Cuánta memoria RAM tiene?
 cuenta con 96 GB de RAM
<br>
¿Qué procesador tiene?
es un intel xeon W de ocho nucleos a 3.5 GHz
<br>
¿Cuántos núcleos tiene? 
cuenta con 8 nucleos
<br>
¿Cuántos hilos de ejecución tiene?
16 hilos
<br>
 ¿Qué tarjeta(s) de video tiene?
 tiene un AMD Radeon Pro W5500X
 <br><br>
![imagen9](capturasdeMAC/primero.jpeg) <br>


 # Examen realizado en MAC

lo primero que se realiza es el compose
![imagen10](capturasdeMAC/segundo.jpeg) <br>

ahora se comprueba con el localhost si se levanto el moodle y se inicia sesion can el usuario y la contraseña que son por default usuario:user contraseña:bitnami
![imagen11](capturasdeMAC/tercero.jpeg) <br>

ahora creamos un curso con el nombre de curso1
![imagen12](capturasdeMAC/cuarto.jpeg) <br>
![imagen13](capturasdeMAC/quinto.jpeg) <br>

ahora agregamos a los usuarios y con el maestro raul caceres usamos como usuario: raul.ca@merida.tecnm.mx y como contraseña:E5un53cr3t0!
![imagen14](capturasdeMAC/sexto_1.jpeg) <br>
![imagen15](capturasdeMAC/sexto_2.jpeg) <br>
![imagen16](capturasdeMAC/sexto_3.jpeg) <br>
![imagen17](capturasdeMAC/sexto_4.jpeg) <br>

como se puede observar se crearon lo usuarios
![imagen18](capturasdeMAC/septimo.jpeg) <br>

por ultimo se agregan tres usuarios al curso como alumnos y uno como maestro como se puede observar
![imagen19](capturasdeMAC/octavo_1.jpeg) <br>
![imagen20](capturasdeMAC/octavo_2.jpeg) <br>
