# Practica_2
## Integrantes:  
- Francisco javier Godinez Lopez
- Pablo Axel Silva Fuentes
- Eduardo David Salas Ayala
## Introducción:  
La práctica tiene como objetivo programar una trayectoria para controlar un brazo robótico Epson utilizando el software Epson RC+. Donde se realiza la planificación de la trayectoria, que consiste en encontrar una ruta transitable entre una posición de origen y una posición objetivo. Teniendo como posición de origen o "Home" unas coordenadas previamente especificadas; la trayectoria consiste en dos posiciones objetivos, la primera donde el brazo se mueve hacia un objeto para recogerlo, y la segunda posición objetivo el brazo se mueve para dejar el objetivo y finalmente regresar a la posicón origen.
## Instrucciones:  

Primeramente, se utilizó el software Epson RC+ con la finalidad de aprender a utilizar una nueva sección de programación, la cual consistió en poder guardar coordenadas "X", "Y" y "Z" para el control del brazo robótico, y así asignar una serie de movimientos establecidos por el usuario. Para ello, primeramente, se realizaron movimientos en el simulador para observar cómo el brazo se movía virtualmente según las coordenadas preestablecidas.

El segundo paso fue profundizar más en la programación, conociendo los comandos o códigos básicos para utilizar las coordenadas guardadas en una serie de comandos que serían ejecutados físicamente en el brazo robótico. Estos comandos fueron:

*ON (Activa la válvula de la garra)
*GO (Da movimiento a la coordenada asignada)
*OFF (Apaga la válvula de la garra)


![WhatsApp Image 2024-09-05 at 7 50 27 PM](https://github.com/user-attachments/assets/119bf538-65c7-435b-9ef4-b1bfec92188c)

De tal manera que el codigo desarrollado quedo de la siguiente manera:
```
Function main
Home
ON 2
GO Arriba
GO Abajo1
OFF 2
GO Arriba
GO soltar
ON 2
Home
Fend
```

En el siguiente video se muestra el movimiento realizado utilizando el código anterior, cuyo objetivo fue tomar un fusible con la garra y trasladarlo a otro punto asignado por el profesor. Este proceso demuestra el correcto funcionamiento del sistema y cumple con los objetivos establecidos para la práctica

https://drive.google.com/drive/folders/1HjE7HlarkAU024qj9DKuwbbv-v8hnPId?usp=drive_link

## Conclusiones:  
### Francisco Javier Godinez Lopez:
Esta práctica brindó la descubrimiento de familiarizarnos con algunas de las herramientas que ofrece el programa Epson RC+, permitiendo averiguar nuevas formas de programación para la automatización del brazo robotico utilizado en el curso, de este modo aplicamos los comandos ON, GO y OFF, los cuales son necesarios para realizar movimientos y tareas en el brazo mecánico. Esto permitió comprender de manera más profunda las capacidades de control y precisión del brazo y su movimiento.


### Pablo Axel Silva Fuentes: 
 De primera instancia esta práctica se logró aprender una característica importante del software, lo que posibilitó adquirir conocimientos adicionales sobre programación, así como llevar a cabo movimientos precisos con el brazo robótico. El uso correcto de los comandos ON, GO y OFF fue necesario para completar la tarea de trasladar un objeto a una ubicación precisa, resaltando las habilidades del sistema en cuanto a exactitud y manejo.

### Eduardo David Salas Ayala: 
El desarrollo de esta practica permitio conocer una de las tantas herramientas que nos brinda del software Epson RC+, permitiendo cononocer nuevas secciones de programación y la ejecución de movimientos tanto en el simulador como en el brazo físico. El conocimiento de comandos básicos como ON, GO y OFF, junto con su correcta implementación, permitió cumplir eficazmente el objetivo de tomar un objeto y trasladarlo a otro punto, lo que ayudó a comprender mejor las capacidades de movimiento y precisión del brazo robótico.

## Referencias bibliográficas
- Localización y planificación de trayectorias - TEKNIKER. (s. f.). https://www.tekniker.es/es/localizacion-y-planificacion-de-trayectorias
