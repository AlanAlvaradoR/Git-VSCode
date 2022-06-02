# Git-VSCode
Comandos básicos para usar Git desde VSCode y actualizar, modificar o crear archivos en Github por medio de la terminal.

![Logo de Git y VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git0.jpg)

## Requisitos

- Cuenta de [Github](https://github.com/). Si no se tiene, es necesario seguir las instrucciones en el sitio para crear una nueva cuenta con su e-mail
- Computadora con Windows, Linux o MacOs
- [VSCode](https://code.visualstudio.com/) instalado
- [GIT](https://git-scm.com/downloads) instalado

---------------------------------------------------------

## Pasos

## Si se desea crear un nuevo repositorio en Github

1. Se inicia sesión en [Github](https://github.com/). Si no se tiene cuenta, es necesario seguir los pasos para crear una cuenta.

![Inicio Github](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git1.PNG)


2. En la parte superior izquierda en la sección de repositorios, se presiona el botón de "nuevo".

![Nuevo Git Repo](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git2.PNG)

Otra alternativa si no aparece la opción es ir a: Tu imagen de perfil (parte superior derecha) -> Tus repositorios -> Nuevo

3. Aparecerá otra ventan donde debemos poner el nombre del repositorio, y la descripción. Desmarcamos la opción de "agregar archivo README" y, en la parte inferior presionamos el botón "crear repositorio".

![Nuevo Repo Conf](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git3.PNG)

4. Aparecerá la siguiente venatan indicando que se ha creado el repositorio con éxito

![Nuevo Repo](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git4.PNG)

5. Abrimos Visual Studio Code

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git5.PNG)

6. Presionamos el botón de agregar archivo (marcado en la siguiente imagen) y escribimos "README.md" y le damos enter

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git6.PNG)

7. Debemos tener una vista como la siguiente, donde en el lado derecho se puede editar el código del archivo que acabamos de crear

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git7.PNG)

8. Escribimos el siguiente código de prueba

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git8.PNG)

9. Si se desea agregar imagenes, siga los pasos del 10 al 14, en caso contrario pasa al paso 15

10. Para un mejor orden en los archivos, se crea una nueva carpeta al presionar el botón de "nueva carpeta"(marcado en la imagen)

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git9.PNG)

11. Igual que al momento de crear el archivo, aparecerá un recuadro donde debemos escribir el nombre de la carpeta, en este caso la llamaré "imagenes" y se presiona "enter"

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git10.PNG)

12. Se debe ver de esta forma

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git11.PNG)

13. Ahora vamos a la carpeta e nuestra computadora donde se encuantran las imagenes que vamos a usar. En este gif se muestra como se arrastra una sola imagen hasta la carpeta que creamos en el VSCode, aunque se puede hacer con varias imagenes a la vez también al seleccionarlas todas y arrastrarlas.

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git1.gif)

14. Ahora para agregar la imagen que recién pusimos al "README.md" hacemos lo siguiente

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git2.gif)

15. Volvemos anuestro repositorio de Github, buscamos el siguiente link (único y diferente para cad persona) y lo copiamos: 

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/gitA.PNG)

16. Ahora presionamos ctrl+alt+ñ en el teclado mientras estamos en el VSCode para abrir una nueva terminal en la parte inferior

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git13.PNG)

17. Ahora en la terminal que abrimos escribiremos lo siquiente y presionamos enter después de cada línea de código

- git init

- git add README.md                                 
*NOTA: si agregamos imagenes, debemos escribir en cambio esto otro: git add .

- git commit -m "first commit"

- git branch -M main

- git remote add origin https://github.com/AlanAlvaradoR/repo-para.git         
*NOTA:(el link debe ser reemplazado por el que copiamos de Github anteriormente)

- git push -u origin main

18. Si solo subimos el archivo README.md sin imagenes, deberiamos ver algo como esto:

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git20.PNG)

19. Si también subimos imagenes, deberiamos ver algo así:

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git21.PNG)

20. Para que se muestren las imagenes, debemos regresar al inicio del repositorio y entrar a la carpeta de imagenes y la imagen que nos interese y copiar su url:

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git23.PNG)

21. En el archivo README.md debemos cambiar el link de cada una de las imagenes por el nuevo que nos da github y, volver a actualizar el repositorio desde la terminal con:

- git add .
- git commit "numero del commit"
- git push origin main 

22. Ahora debreriamos ver algo como esto

![VSCode](https://github.com/AlanAlvaradoR/Git-VSCode/blob/main/imagenes/git22.PNG)


