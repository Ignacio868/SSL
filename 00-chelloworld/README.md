Consigna:
Instalar un compilador del lenguaje c, para posteriormente ejecutar un comando "Hola Mundo", el cual tiene que direccionar a 
un mensaje por pantalla y crear una txt. Para finalizar hay que escribir la version del lenguaje C y el compilador
que fueron instaladas en el dispositivo, al igual que la manera utiliza para saber la vesion.

Resolucion:
El compilador de lenguaje C que instale fue MinGW o gcc, en el entorno al editor de codigo Visual Studio Code.

Version gcc: 6.3.0
Para saber la version que instale use el comando "gcc -v" en el cmd o en "git bash"/"cmd".

Version C:C11
Para saber la version de C que instale en mi computadora use el comando escrito al final. El cual me indico que mi estandar 
de C era 201112, el cual es equivalente a C11.

#include<stdio.h>
int main(){
    printf("Version del estanadar de c: %ld\n", __STDC_VERSION__);
    return 0;
}
