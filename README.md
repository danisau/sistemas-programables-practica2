## Alarma con RedSwitch y sensor de movimiento PIR

***objetivo***

Implementar una alarma unsado un Zumbador. La alamrma se activara mendiante la instalación de un interruptor magnetico (Red Switch) que al pasar un iman cerca de el, activara la alarma y al mismo tiempo se encedera un led. La alarma tambien cuenta con un sensor de movimiento PIR, que al acercarse un objeto cerca de el, envia una señal al ardino para encender la larma. 

***Interruptor Magnetico (Red Switch)***
--------------------------------------------
Una magnetic reed es un dispositivo electromecánico que se comporta como un interruptor que se activa ante la presencia de un imán.
Los sensores magnetic reed son ampliamente utilizados. Por ejemplo, muchas alarmas de puertas y ventanas funcionan ubicando un imán en el elemento, y detectando la apertura con un magnetic reed. También podemos ubicar el imán en una puerta, o vitrina, para encender una luz, etc.
Como un magnetic reed no deja de ser un interruptor, podemos emplear este dispositivo para encender o apagar un dispositivo directamente. Por supuesto, también podemos emplear las entradas digitales de Arduino para leer el estado del magnetic reed, de forma similar a como vimos en la entrada leer un pulsador con Arduino.

***Materiales***
----------------
-Arduino Uno
-Red Switch
-2 LED´s
-Sensor de movimiento PIR
-Iman 
-Cable de cobre

