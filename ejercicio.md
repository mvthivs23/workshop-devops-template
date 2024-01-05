
# Pasos del taller


Cree un nuevo repositorio utilizando la plantilla de repositorio del taller: https://github.com/mvthivs23/workshop-devops-template

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/a8289d88-bc67-4079-ae04-50960dd94174)


<br>
<br>




Luego completas los campos que se te indica: (Ignora Azure Pipelines ya que viene por defecto)

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/b1f80d26-fec0-4d82-b5c6-604376a81002)

<br>
<br>


Esta plantilla contiene:

I. Código de muestra de una app simple en HTML.

II. Ejercicios de creación de ramas, pull request y revertir cambios.
<br>
<br>
<br>
 


3. Clone el repositorio en su máquina y ábralo en su editor preferido o edítelo directamente en el navegador presionando la .tecla (punto) en su teclado.
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/0c13a14d-4ff0-4ff6-8418-87ccc9426524)

<br>
<br>

Creamos una carpeta de trabajo y abrimos una consola "Git Bash" o si tienes Visual Studio Code lo puedes realizar de igual manera en la terminal.
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/9a7dec17-8b1e-4741-97cb-dda429922e69)

<br>
<br>

Ingresamos el siguiente comando para abrir nuestro editor de texto VS Code:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/64722f82-015c-4eaf-adb6-41433f9df968)

<br>
<br>

Ya podremos editar el codigo de nuestra App:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/12f70871-e19b-49e3-ac2c-ebabb7e7cb1d)


<br>
<br>

Abrimos una Terminal, puedes seleccionar en la parte superior izquierda o tambien presionando las teclas CTRL+MAYUS+Ñ
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/5da301bb-6d9c-46f5-b0dc-b1c5717082cb)


<br>
<br>

Si ejecutamos el comando "git branch" nos mostrará las ramas actuales del repositorio
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/a65da126-2359-4cc5-9970-f0616f634a63)

<br>
<br>

Por lo que crearemos una rama para realizar nuestros cambios:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/c108b9ea-7b2d-41fd-b835-ad5f75196fcf)

<br>

Ahora tenemos tanto nuestra rama "main" y nuestra rama "feature-OC2024-NuevaFuncionalidadIndex"
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/7c0ef2de-2bb0-4011-9d91-748e03875cc2)

<br>
<br>

Nos cambiamos a nuestra rama feature y asi empezar a relizar cambios en nuestro codigo:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/1404d985-3efe-4bd8-9b21-8986e94dc718)


<br>
<br>

Luego agregamos los cambios y los subimos a nuestra rama feature:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/6e13090a-ec1b-4ee9-9f9b-d96d2f73405a)


<br>
<br>
<br>
<br>

Ya creamos una rama mediante la consola git, ahora crearemos dos ramas a través de la consola de GitHub:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/0d4a3b8e-e9c1-406e-b89b-59da6d7a7f09)

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/fcb28778-c2c7-491e-aa71-8ccd31e96cc0)

<br>

Una vez pusheamos nuestros cambios a nuestra rama feature, creamos un Pull Request:
![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/d8e6763e-8d9d-4153-b4f7-34ea66f57deb)

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/c133a278-f471-497d-bbea-b205e824c42e)

<br>

Una vez creado podemos podemos añadir revisores para nuestros cambios:

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/6cb4dcfe-c7f9-43b4-a39c-bf6563851284)

<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/e4cc568a-0ab7-4295-bfa4-e0d74bb7a41c)


<br>

![image](https://github.com/mvthivs23/workshop-devops-template/assets/114781399/38fc4ed3-850a-4239-8b31-1c43c8d6f957)


<br>
<br>
<br>

Despues que creamos nuestra rama en GitHub, en nuestro local ingresamos el comando git fetch --prune, luego git branch --all y luego un git checkout a nuestra rama.

<br>

> git fetch --prune
<br>
From https://github.com/mvthivs23/Mask-app
 * [new branch]      Test       -> origin/Test*

 <br>

 git checkout <rama-nueva>


 











