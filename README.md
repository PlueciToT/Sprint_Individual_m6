# Sprint_Individual_m6
## Yo quiero otro mundo APP - Nicolas Calderón
![Banner](https://i.imgur.com/lYPuTHd.png) <br>
<p align=justify>
Acontinuacion te dare a conocer el proyecto estudiantil aplicado por Awakelab "Yo quiero otro mundo" un proyecto el cual esta basado en la pasion y en que es lo que queremos para este planeta, como lo imaginamos y que podemos hacer por el y contribuir por un mejor futuro, ademas te dejare credenciales para que puedas ver el funcionamiento base ver las restricciones creadas en el proyecto.
</p>
<p align=justify>
Este proyecto si bien es basico y simple aun asi esta realizado con amor y pasion, y expuesto para todo aquel que pueda necesitar una guia o idea basica.
</p>
---
<p align=justify>
/// CREDENCIALES ///<br>
🌱 Usuario regular <br>
Username: Astra <br>
Pass:     Gata1234 <br>
(puede ver todo excepto users) <br><br>
🌳 Usuario Admin <br>
Username: ClaudioDel <br>
Pass:	  AwakeLab123 <br>
(puede ver toda la pagina)
</p>
---

### Registrate <br>
<p align=justify>

![registro](https://i.imgur.com/RHEjzUl.png)

La interfaz es dinamica pero sencilla, ya que se ha pensado para ser un portal de noticias o articulos con tematica medioambiental. Al momento de ir a registrarte puedes escojer si quieres aportar escribiendo notas (siendo Blogger) o siendo siendo lector y compartiendo el contenido con otras personas, entre todos creamos comunidad, cabe destacar que podrias dar tu opinion en cada publicacion ¡todos queremos escucharte! 😀
</p>

![registro2](https://i.imgur.com/BASdHZp.gif)

### Inicia y cierra tu sesión cuando quieras <br>
<p align=justify>
  
![inicia](https://i.imgur.com/zvQbKl7.png)

Inicia sesion, te damos la bienvenida, disfruta, crea comunidad y cuando ya te quieras salir cierra tu sesion cuando quieras.

![Wellcome](https://i.imgur.com/oqlxlQa.gif)
</p>

### Grupos <br>
  <p align=justify>
    
- Se añaden dos grupos, Blogger y Lector, los cuales tienen distintos permisos.
    
- Blogger pueder Ver: permisos, grupos, Usuarios (app y proyecto), contenido y sesion - Editar: Su usuario, contenido - Eliminar: Su user, su contenido, y cerrar sesion - Agregar: Contenido al blog e iniciar sesion.
  
- Lector puede Ver: su sesion, su usuario, permisos y contenidos - Editar su user - Iniciar y cerrar su sesion.
  
Los permisos son equilibrados para que el blogger pueda tener los mismos permisos que el usuario regular, pero ademas puede agregar contenido, editarlo o eliminarlo. Cabe destacar que el Blogger es parte del
Staff por lo que tiene algunos accesos mas, mientras que el RegularUser es un usuario de estado "activo"
</p>


## Descripción
<p align=justify>
Esta aplicación "quiero_otro_mundo" es una aplicación web desarrollada en Django que permite a los usuarios registrarse, realizar login/logout y permite a los administradores ver quines forman parte
de la lista de usuarios registrados. Toda la información es guardada en una base de datos de sqlite3 y administrada por el panel de control de Django.
</p>

## Funcionalidades

![userlist](https://i.imgur.com/M3j23BW.png)
<p align=justify>
  En caso de ser super admin eres el unico que puede ver los usuarios registrados, los cuales apareceran enlistados en una pagina restringida, el link hacia esta sale en el menu de navegacion pero solo sera visible para los superadmin 🤫.
  
- Registro de usuarios: Registro simple, mediante nombre de usuario, contraseña y correo electronico. Validación en nombre de usuario (150 caracteres como máximo. Únicamente usar letras, dígitos y @/./+/-/_ )
y contraseña (valida que la contraseña no posea atributos similares a información provista por el usuario, establece un largo mínimo de 8 caracteres, no puede ser una contraseña común, ejemplo 1234, e impide contraseñas completamente numéricas).

- Inicio de sesión de usuarios: Si el registro es exitoso, el usuario puede acceder a una página exclusiva (de otro modo inaccesible) con un saludo personalizado con su nombre de usuario. Si se 
  intenta entrar a esta página sin iniciar sesión, ocurre una redirección automática que redirige al usuario a la página de login.
  
- Cierre de sesión de usuarios: Cierre de sesión una vez iniciada. El botón para realizar esta acción se encuentra en la pagina de saludo personalizado post-login.
  
- Vista de los últimos usuarios registrados: Visualización de usuarios registrados sin necesidad de utilizar el panel de control provisto por Django solo visible para administradores dado que contiene informacion de los usuarios, como username, email y nombres.
  
- Interfaz intuitiva y fácil de usar: Interfaz sencilla, minimalista y con el contenido justo para no sobresaturar ni entorpecer el uso de la aplicación.
</p>

## Requisitos del sistema

  -Python 3.11.3
  
  -Django 4.2.1
  
  - DBeaver (o cualquier otro cliente de base de datos que maneje sqlite)
    
  - Navegador web de su preferencia.
    
  - Conexión estable de internet
    
  - dependencias necesarias para la aplicación se encuentran en archivo requirements.txt


## Instrucciones de instalación

1. Clona el repositorio de la aplicación desde GitHub:

2. Accede al directorio del proyecto:

3. Crea un entorno virtual e instala las dependencias desde requeriments.txt :
     - python -m venv (nombre de tu entorno virtual)
     - (nombre de tu entorno virtual)\scripts\activate.bat   <-- Ejecutar dentro del directorio del proyecto
     - pip install -r requirements.txt

5. Configura la base de datos:
   - Crea una base de datos en PostgreSQL y actualiza la configuración en el archivo `settings.py`.
   - Si deseas puedes utilzar la base datos por defecto (sqlite3) que trae la aplicación.

7. Aplica las migraciones:
   - python manage.py makemigrations
   - python manage.py migrate

9. Inicia el servidor local:
    - python manage.py runserver

11. Abre tu navegador web y visita `http://localhost:8000` para acceder a la aplicación.

### Contribuciones

¡Se agradecen las contribuciones a "quero_otro_mundo"! Si deseas colaborar, sigue estos pasos:

1. Crea un fork del repositorio
2. Crea una rama para tu nueva función o corrección de error: `git checkout -b nombre-rama`
3. Realiza tus modificaciones y asegúrate de escribir pruebas adecuadas.
4. Realiza un commit de tus cambios: `git commit -m "Descripción de los cambios"`
5. Envía tus cambios al repositorio remoto: `git push origin nombre-rama`
6. Abre una solicitud de extracción en GitHub para que revisemos tus cambios.

### Soporte

Si tienes alguna pregunta, problema o sugerencia, no dudes en contactarnos a través de la sección de "Issues" en GitHub.

¡Gracias por utilizar "quiero_otro_mundo"!
