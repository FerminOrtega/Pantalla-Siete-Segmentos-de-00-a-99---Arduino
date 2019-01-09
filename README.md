# Pantalla de Siete Segmentos de 00 a 99 - Arduino
En este proyecto vamos a ver el uso de las pantallas de siete segmentos, como conectarlas para formar los dígitos que deseeamos y conbinarlas con otras pantallas para hacer todos los números que queramos. 

![alt text](https://www.technologicalarts.ca/shop/components/com_virtuemart/shop_image/product/7_segment_LED_Di_4b0af019b3ac6.jpg)

## Componentes y materiales
1. Placa de Arduino (se usará para el ejemplo la placa Arduino UNO)

![alt text](https://cdn.antratek.nl/media/product/b81/arduino-uno-rev3-a000066-aaf.jpg)

2. Dos Pantallas de Siete Segmentos (de tipo ánodo común)

![alt text](https://handsontec.com/wp-content/uploads/2016/05/7-seg-1Dig-1-300-100x100.jpg)

3. Protoboard

![alt text](https://www.elegoo.com/wp-content/uploads/2017/01/3-22-100x100.jpg)

4. Cables de puente

![alt text](http://www.electronicspro.com.pk/wp-content/uploads/2017/11/40P-Male-to-male-Jumper-Wires-for-Arduino-100x100.jpg)

## Como funcionan estas pantallas??
Estas pantallas tienen un pin por cada uno de los segmentos que se pueden iluminar y el de potencia, la potencia que suelen usar estas pantallas es de 3.3v y no 5v como la mayoria de los componentes. 
Para el proyecto vamos a usar todos los pines digitales de los que disponemos por lo que conectaremos todos los segmentos de nuestras pantallas menos el del punto ya que no lo necesitaremos.
El esquema de los pines de las pantallas de siete segmentos se ven así:

![alt text](https://www.moodle.gym-wst.de/pluginfile.php/1205/mod_label/intro/sieben_seg_pinbelegung.png)

## Cómo conectamos las Pantallas a la placa
