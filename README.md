# OPmini 
## Grabador Open Source USB para PICs  

Opmini es un grabador USB para pics basado en el proyecto open source de Alberto Maccioni Open Programmer v0.11.2 http://openprog.altervista.org/OP_eng.html#Top
El objetivo de esta version mini es la de ofrecer un grabador económico, open source y con un diseño minimalista que cumpla con las necesidades básicas de un grabador. Esto no es otro pickit clon si no un proyecto de código abierto. 
## Capacidades
- Amplia compatibilidad en pics de familias 12/16/18/24 
- Interfaz sencilla e intuitiva
- Provee una fuente de +5V a 400mA MAX con circuito de protección
- Basado en el PIC18f2550
- Velocidad de transferencia máxima de 64Kb/s
- USB HID no necesita drivers adicionales

Lista de compatibilidad provista en la página del proyecto original (pronto se agregará una lista especifica para esta versión), sin embargo se han hecho pruebas con algunos pics aun no probados por el autor, entre ellos el PIC16f18875 y funciona correctamente.

## Software PC
El software del grabador OPmini llamdado opgui-mini es compatible actualmente solo con Windows, contiene las siguientes caracterísiticas en su verison actual:
- Interfaz sencilla e intuitiva enfocada solo en funciones de grabación
- Actualiza el archivo .hex cada vez que se compila el código, eliminando la necesidad de cargar cada vez que se realize un cambio
- Permite tanto grabar como leer los binarios del micro

## Setup
Para poder usar la interfaz opgui-mini, se requiere instalar el plugin para windows GTK+ runtime Environment https://sourceforge.net/projects/gtk-win/ antes de ejecutar. Se debe seleccionar la familia del PIC obejtivo y en otra pestaña el PIC a grabar, luego se debe seleccionar el archivo .hex y finalmente cargar.  

## Por probar
- Grabar EEPROMs
- Grabar AVRs
- DsPics
- Como ICD debugger

*Para estos casos podria requerir de hardware adicional



## License
Se permite realizar cambios y redistribuir bajo los lineamientos de la GNU/GPL 
GPL V3
