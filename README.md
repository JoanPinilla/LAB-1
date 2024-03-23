# LAB-1
PRIMER LABORATORIO DE ROBÓTICA
# 1. DESCRIPCIÓN DE LA SOLUCIÓN:
   Según los requerimentos de la guía de laboratorio, se diseñó un logo en un área de 28.5 cm x 26 cm que contiene los siguientes elemetos:
   * Logo de una compañía, en este caso BMW.
   * El nombre de la compañía
   * Las iniciales de los integrantes del equipo, en este caso únicamente JMPL.
   Estos elementos se pueden ver modelados en la figura 1.
## Figura 1
![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/8823854d-e20a-447e-a79d-babde7d27e99)

Para lograr marcar el papel con el logo y las iniciales, primero se crearon targets al que van por todo el borde de las letras, para luego crear un path por cada letra e introducirlos en orden al procedimiento del robot. Los targets se deben orientar de tal forma que su eje z sea perpendicular a la superficie donde se van a hacer los trazos.

Luego de completar los paths y la rutina, se modificó el código para añadir las entradas y las salidas digitales. Una de estas entradas requiere que el robot empiece el procedimiento y otra requiere que este se ponga en una posición de mantenimiento. Esta pose de mantenimiento se muestra en la figura 2.

## Figura 2
![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/bc30f816-2a28-4e2d-8c08-243df6b43556)

Las entradas digitales corresponden a pulsadores en el laboratorio, y las salidas digitales corresponden a LEDs indicadores que se encienden cuando la pose de mantenimiento o la rutina del logo se están ejecutando.

# 2. Diagrama de flujo

## Figura 3
![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/8e4612dc-adde-4dd8-bf47-50e68326eaa7)

# 3. Plano de planta de cada elemento
Se muestra el plano de planta en la figura 4.

## Figura 4
   ![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/e69e7240-6496-49a1-95ed-a6e8bbbc4d38)

Donde:
* a: 5 cm
* b: 50 cm
* c: 26 cm
* d: 28.5 cm

# 4. Descripción funciones utilizadas

Las principales funciones utilizadas fueron:
* MoveL: Para mover linealmente el TCP. Sirve para hacer líneas rectas.
* MoveJ: Mueve las articulaciones del robot.
* MoveC: Mueve el TCP en una trayectoria circular.

# 5. Diseño de la herramienta
El modelo de la herramienta se puede ver en la figura 5. La brida de la base va de acuerdo al plano de la brida proporcionado en el manual del robot. Sostiene el marcador a 30° para que sea más sencillo escribir y tiene un patrón de reducción de peso en forma de espiral. También cuenta con un espacio en la base del marcador para el resorte y dar flexibilidad a la herramienta.

## Figura 5
![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/071a0ee7-5c49-4e15-b638-fa6628feaddd)

La herramienta con el modelo del marcador (en gris) se puede ver en la figura 6.

## Figura 6
![image](https://github.com/JoanPinilla/LAB-1/assets/118155154/47ab8295-86bb-44c8-bbce-6a5dca881c8a)


# 6. Código de RAPID

Disponible en el repositorio

# 7. Video

Video de la simulación disponible en: [YouTube](https://youtu.be/CfWUV-n_29U)

Video de la demostración en laboratorio disponible en: [YouTube](https://youtu.be/uWWaZR0-C00)
