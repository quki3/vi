# neovim
## editar el archivo con vin
```bash
h //? nos movemos a la isquierda
b //? nos lleva por palabras a la isquierda
l //? nos movemos a la derecha 
w //? nos lleva por palabras a la derecha
e //? nos lleva por palabras a la derecha ubicandonos en la ultima palabra
j //? nos lleva para abajo 
k //? nos lleva para arriba

i //? inserta texto a la isquierda
I //? inserta texto a la isquierda al inicio de la linea
a //? inserta texto a la derecha
A //? insertar texto a la derecha de la linea

d //? borra la letra seleccionada recive segundoos parametros
d w //? borra toda la palabra las los espacios
d e //? borra toda la palabra sin los espacio
D  //? borra desde donde estamos hasta el final de la linea
x //? borra la letra seleccionada 
X //? borra la letra a la isquierda

uv //? modo visual podemos selecionar las palabras

s //? borra un caracter y nos pone en modo insertar
S //? borra toda la linae y nos pone en modo insertar
c //? borra la/s letra seleccionada y te pone en modo insertar
C //? borra desde donde estamos hasta el final de la linea

u //? deshase los cambios
Ctrl r //? rehase los cambios

 
```
## la consola de vim
```bash
:w newnamearchivo //? guarda y crea el archivo 
:pwd //?muestra la ruta
:e nombredelarchivoalquequeremosir  //? abre el archivo que pusimos si no existe lo crea
```
