
# Pasos del taller
<br>

Antes de comenzar te sugiero instalar el editor de texto Visual Studio Code: [AQUI](https://code.visualstudio.com/download)
<br>
<br>
También tener instalado Git en tu ordenador, puedes seguir los pasos: [AQUI](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git)
<br>
<br>
Si ya los tienes instalado puedes continuar sin problemas!!

<br>
<br>
<br>

En esta plantilla te pongo a disposición una Aplicación Web Bancaria (Simple) llamada "TransferMoney" en la cual podrás realizar los ejercicios propuestos.

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/f21ea671-618c-4e45-9868-71ef9ac74d57)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# Trabajando con Git y GitHub

<br>
<br>
<br>




Cree un nuevo repositorio utilizando la plantilla de repositorio del taller: https://github.com/mvthivs23/workshop-devops-template

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/a8289d88-bc67-4079-ae04-50960dd94174)


<br>
<br>
<br>
<br>
<br>
<br>


Luego completas los campos que se te indica: (Ignora Azure Pipelines ya que viene por defecto)

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/b1f80d26-fec0-4d82-b5c6-604376a81002)

<br>
<br>
<br>
<br>
<br>
<br>

Esta plantilla contiene:

I. Código de muestra de una app simple en HTML.

II. Ejercicios de creación de ramas, pull request y revertir cambios.

<br>
<br>
<br>
<br>
<br>
<br>


3. Clone el repositorio en su máquina y ábralo en su editor preferido o edítelo directamente en el navegador presionando la .tecla (punto) en su teclado.
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/0c13a14d-4ff0-4ff6-8418-87ccc9426524)

<br>
<br>
<br>
<br>
<br>
<br>

Creamos una carpeta de trabajo y abrimos una consola "Git Bash" o si tienes Visual Studio Code lo puedes realizar de igual manera en la terminal.

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/9a7dec17-8b1e-4741-97cb-dda429922e69)

<br>
<br>
<br>
<br>
<br>
<br>

Ingresamos el siguiente comando para abrir nuestro editor de texto VS Code:

<br>
<pre>
<code>
code .
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/64722f82-015c-4eaf-adb6-41433f9df968)


<br>
<br>
<br>
<br>
<br>
<br>

Ya podremos editar el codigo de nuestra App:
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/12f70871-e19b-49e3-ac2c-ebabb7e7cb1d)


<br>
<br>
<br>
<br>
<br>
<br>

Abrimos una Terminal, puedes seleccionar en la parte superior izquierda o tambien presionando las teclas CTRL+MAYUS+Ñ
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/5da301bb-6d9c-46f5-b0dc-b1c5717082cb)


<br>
<br>
<br>
<br>
<br>
<br>

Si ejecutamos el comando "git branch" nos mostrará las ramas actuales del repositorio


<br>
<pre>
<code>
git branch
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/a65da126-2359-4cc5-9970-f0616f634a63)

<br>
<br>
<br>

Por lo que crearemos una rama para realizar nuestros cambios:

<br>
<pre>
<code>
git branch -b Nombre-rama-feature
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/c108b9ea-7b2d-41fd-b835-ad5f75196fcf)

<br>
<br>
<br>

Ahora tenemos tanto nuestra rama "main" y nuestra rama "feature-OC2024-NuevaFuncionalidadIndex". Esto lo verificamos con el siguiente comando:

<br>
<pre>
<code>
git branch
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/7c0ef2de-2bb0-4011-9d91-748e03875cc2)

<br>
<br>
<br>
<br>
<br>
<br>

Ya creamos una rama mediante la consola git, ahora crearemos una rama a través de la plataforma de GitHub (ES SOLAMENTE ELECCIÓN, PUEDES TRABAJAR SOLO CON TU RAMA FEATURE Y MAIN SI TU LO DESEAS).

<br>

Debes presionar la zona marcada en rojo "Branches" 

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/964477f6-8259-40cc-ae4f-7e44b6f61996)

<br>


<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/da8d5d7b-d214-4f4f-9cdc-f1bd0828a1ee)

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/889b35eb-b888-4dba-b12d-df87a485ded6)

<br>
<br>

Despues que creamos nuestra rama en GitHub, en nuestro local ingresamos el comando git fetch --prune y nos traerá la creación de nuestra rama.

<br>
<pre>
<code>
git fetch --prune
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>


<br>
<pre>
<code>

*ESTO NOS IMPRIMIRÁ POR CONSOLA*
 
From https://github.com/usuario/Mask-app
 * [new branch]      Nueva-rama-creada    -> origin/Nueva-rama-creada
</code>
</pre>

<br>


<br>
<br>
<br>
<br>
<br>
<br>
<br>

# Realizar cambios en el proyecto

<br>

Para realizar cambios en nuestro proyecto, nos cambiamos a nuestra rama feature y asi empezar a realizar cambios en nuestro codigo:

<br>
<pre>
<code>
git checkout Nombre-rama-feature
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/1404d985-3efe-4bd8-9b21-8986e94dc718)


<br>
<br>
<br>

Puedes realizar algún cambio en el codigo ya sea agregando alguna funcionalidad, añadiendo algun estilo o simplemente eliminando una linea.

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/30bd3be7-3f7c-49b7-a23b-cfb98cc7ec3c)

<br>

¡¡RECUERDA GUARDAR TUS CAMBIOS!!

<br>
<br>
<br>
<br>

Después de realizar modificaciones en los archivos de nuestro proyecto, el estado de esos archivos se encuentra en el directorio de trabajo. 

<br>

Lo cual debemos agregarlos al area de Staging


<br>
<pre>
<code>
git add .
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

o tambien puedes agregarlos por archivo (puede ser uno o varios) con el siguiente comando

<br>
<pre>
<code>
git add nombre-archivo1 nombre-archivo2
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

Luego utilizamos el comando "git commit" para confirmar los cambios en el área de staging y crear una nueva instantánea (commit) en la historia del proyecto.

<br>
<pre>
<code>
git commit -m "Descripcion acerca del cambio"
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>

La opción -m permite incluir un mensaje de confirmación en línea.

<br>


<br>


Una vez que hemos confirmado nuestros cambios localmente, podemos enviar esos cambios al repositorio remoto (En este caso GitHub). Utilizamos el comando git push para enviar los cambios al servidor remoto.

<br>
<pre>
<code>
git push origin nombre-de-la-rama
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>


<br>
<br>
<br>
<br>
<br>

# Creación Pull Request

Después de crear una nueva rama (feature, por ejemplo) y realizar cambios en esa rama localmente, cuando haces un git push para enviar esos cambios al repositorio remoto, GitHub detecta la nueva rama y te ofrece la opción de "compare and pull request". Esto es común cuando estás trabajando en una nueva funcionalidad o corrección de errores.

<br>

Una vez pusheamos nuestros cambios a nuestra rama feature, creamos un Pull Request:
<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/d8e6763e-8d9d-4153-b4f7-34ea66f57deb)

<br>

Podemos añadir revisores a nuestros cambios en la sección de la derecha y luego podemos crear el Pull Request:

<br>


![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/c133a278-f471-497d-bbea-b205e824c42e)

<br>

<br>

Luego seleccionamos la opción de mezcla que tu eligas, en este caso se mezclará con "Squash". todos los commits de la rama feature se combinan en un solo commit en la rama main.

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/6cb4dcfe-c7f9-43b4-a39c-bf6563851284)

<br>

<br>

Seleccionamos "Squash and Merge"
<br>


![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/e4cc568a-0ab7-4295-bfa4-e0d74bb7a41c)


<br>

Luego seleccionamos "confirm Squash and Merge"

<br>


![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/38fc4ed3-850a-4239-8b31-1c43c8d6f957)


<br>
<br>
<br>
<br>
<br>
<br>

# Reto

<br>

Te propongo el reto de agregar otro cambio al proyecto en tu rama feature y luego crear un Pull Request desde la rama feature hacia main y luego mezclas.

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/a6da5780-09ce-476d-8507-3a7afccea32c)

<br>

Además, puedes intentar realizar algún revert de un commit que hayas realizado, te dejo algunos tip para realizarlo.

<br>
Ingresa el comando "git log", este comando nos sirve para mostrar el historial de confirmaciones (commits) en una rama.

<br>
<pre>
<code>
git log
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>


Utiliza el comando git revert con el hash del commit que deseas revertir.

<br>
<pre>
<code>
git revert <hash-del-commit-a-revertir>
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>


Después de ejecutar este comando, se abrirá un editor para que ingreses un mensaje de confirmación. Guarda y cierra el editor para completar el proceso.

<br>

Después de revertir el commit, ahora tienes un nuevo commit que deshace los cambios del commit original. Puedes seguir con el proceso de empujar los cambios al repositorio remoto si es necesario.

<br>

<br>
<pre>
<code>
git push origin nombre-de-tu-rama
</code>
</pre>
<button class="copy-btn" data-clipboard-target="#tuCodigo"></button>
<br>







# Un Craaaaaaaaa!!
 











