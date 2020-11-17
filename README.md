# Pylontech
How to read data easily from console port ( RS232 ) on pylontech batteries
Conectando a 1200 Bd N8 1

sale codigo de 16 digitos :

~200146060000FDAD

CONEXION A BATERIAS PYLONTECH 

En primer lugar, la consola debe estar activada. Para ello, cambie el programa de terminal a 1200, 8,N,1.

A continuación, envíar la siguiente cadena a la batería con termite:

~20014682C0048520FCC3
 en termite escribira el valor hexadecimal :

7E 32 30 30 31 34 36 38 32 43 30 30 34 38 35 32 30 46 43 43 33 0D

Cambie ahora a 115200,8,N,1.

Datos: Enviar 0D 0A ( corresponde a intro CR + LF ).

Aparece el indicador pylon>, que permite la entrada de comandos.

Primer comando, por ejemplo.

help_n . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

muestra una ayuda

pwr'n

/*

@

Volt Volt Curr Tempr Tlow Thigh Vlow Vhigh vhigh Base.St Volt.St Curr.St Temp.St tiempo Coulomb B.V.St B.T.St B.T.St

1 49884 4310 28000 25000 26000 3322 3327
