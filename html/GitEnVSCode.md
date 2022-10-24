# Git en Visual Studio Code

## 0. Antes de empezar.
Para empezar, tenemos que tener instalados VS Code y Git, y contar con un repositorio local en nuestra máquina.<br>
![Imagen](../img/gitEnVsCode/1.png)<br>
Si lo tenempos, en VS Code abrimos el directorio en el que tenemos el repositorio local y ha debido detectar que ese directorio es un repositorio local y muestra cuando un archivo es modificado o no estaba previamente.<br>
![Imagen](../img/gitEnVsCode/3.png)<br>
La pestaña de control de código fuente también nos indica el nº de cambios que se han realizado en total. Pero aún no sabe dónde está el repositorio online, así que hay que iniciar sesión en github e indicar en git usuario y email.<br>
Cuentas -> Activar sincronización de configuración.<br>
![Imagen](../img/gitEnVsCode/4.png)<br>
Iniciar sesión y activar -> Iniciar sesión con github.<br>
![Imagen](../img/gitEnVsCode/5.png)<br>
Por último, introducimos los credenciales de GitHub y ya podemos empezar.
## 1. Sincornizar el repositorio remoto con el local (push).
Ahora podemos confirmar los cambios y sincronizarlos con el repositorio online. Vamos a Control de código fuente -> Opciones -> Commit -> Confirmar todo.<br>
![Imagen](../img/gitEnVsCode/8.png)<br>
Nos abrirá un archivo donde es necesario escribir un comentario que acompañe a nuestro commit. Una vez escrito, a la derecha de la pantalla le damos a confirmar.<br>
![Imagen](../img/gitEnVsCode/9.png)<br>
También se puede escribir escribir el comentario en el cuadro de texto que aparece justo encima de del botón de confirmación y luego darle a dicho botón, más rapido y sencillo.<br>
Y por último, a la izquierda nos saldrá el botón para sincronizar los cambios con github.<br>
![Imagen](../img/gitEnVsCode/10.png)<br>
Con esto, hemos hecho push del repositorio local al remoto.
