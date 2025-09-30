
<center>

# Git y control de versiones


</center>

***Nombre:*** Antonio Navarro Hernández(user1), Jose Manuel Peña Rodríguez(user2).
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

En esta tarea se nos propone trabajar con git y control de versiones. Para ello relizamos tanto trabajo por terminal como la utilización de la interfáz gráfica de github.

#### ***Objetivos***. <a name="id2"></a>

El objetivo es crear issues en un archivo que trabajamos en conjunto crear colisiones e issues en un archivo css para resolverlas con el fin de completar el trabajo.

#### ***Material empleado***. <a name="id3"></a>

Respecto al Hardware usamos nuestros PCs, los asignados en clase pero también usamos los que tenemos en casa. En la parte de software usamos Github para el control de versiones, distintos tipos de terminales (CMD, bash) y el IDE visual Studio Code.  

#### ***Desarrollo***. <a name="id4"></a>

*user1* crea un repositorio público llamado git-work en su cuenta de GitHub, añadiendo un README.md y una licencia MIT.

<img src="capturas_img/1.png" alt="captura1" width="400"/>


*user1* clonará el repo y añadirá los ficheros: index.html, bootstrap.min.css y cover.css. Luego subirá los cambios al upstream.


<img src="capturas_img/2_git_clone.png" alt="captura2" width="400"/>

<img src="capturas_img/3_explorador.png" alt="captura2" width="400"/>

<img src="capturas_img/3_terminal.png" alt="captura2" width="400"/>


*user2* crea un fork de git-work desde su cuenta de GitHub.


<img src="capturas_img/4_fork.png" alt="captura3" width="400"/>


*user2* clonará su fork del repo.


<img src="capturas_img/5_clonarfork.png" alt="captura4" width="400"/>


*user1* creará una issue con el título "Add custom text for startup contents".


<img src="capturas_img/paso6.png" alt="captura5" width="400"/>


*user2* creará una nueva rama custom-text y modificará el fichero index.html personalizándolo para una supuesta startup.


<img src="capturas_img/7.1_CrearRama.png" alt="captura6" width="400"/>

<img src="capturas_img/7.2_IniciarStartup.png" alt="captura6" width="400"/>


*user2* enviará un PR (Pull Request) a user1.


<img src="capturas_img/7.2_IniciarStartup.png" alt="captura7" width="400"/>


*user1* probará el PR de user2 en su máquina (copia local) creando previamente un remoto denominado upstream, y realizará ciertos cambios en su copia local que luego deberá subir al propio PR.


<img src="capturas_img/paso9.png" alt="captura8" width="400"/>


*user1* y *user2* tendrán una pequeña conversación en la página del PR, donde cada usuario incluirá, al menos, un cambio más.


<img src="capturas_img/10_ConversacionYCierreDePullRequest.png" alt="captura9" width="400"/>


*user1* finalmente aprobará el PR, cerrará la issue creada (usando una referencia a la misma) y actualizará la rama principal en su copia local.


<img src="capturas_img/paso11.png" alt="captura10" width="400"/>


*user2* deberá incorporar los cambios de la rama principal de upstream en su propia rama principal.


<img src="capturas_img/12_UpstreamARamaJose.png" alt="captura11" width="400"/>


*user1* creará una issue con el título "Improve UX with cool colors".


<img src="capturas_img/13_issue.png" alt="captura12" width="400"/>


*user1* cambiará la línea 10 de cover.css a: color: purple;


<img src="capturas_img/14_purple.png" alt="captura13" width="400"/>


*user1* hará simplemente un commit local en main → NO HACER git push.


<img src="capturas_img/15_sinPUSH.png" alt="captura14" width="400"/>


*user2* creará una nueva rama cool-colors y cambiará la línea 10 de cover.css a: color: darkgreen;


<img src="capturas_img/16.1_CrearRamaCoolColors.png" alt="captura15" width="400"/>

<img src="capturas_img/16.2_CambiarColorADarkGreen.png" alt="captura15" width="400"/>


*user2* enviará un PR a *user1*


<img src="capturas_img/17conflicto.png" alt="captura16" width="400"/>


*user1* probará el PR de *user2* (en su copia local). A continuación tratará de mergear el contenido de la rama cool-colors en su rama principal y tendrá que gestionar el conflicto: Dejar el contenido que viene de user2.


<img src="capturas_img/18conflicto_resuelto.png" alt="captura17" width="400"/>


Después del commit para arreglar el conflicto, *user1* modificará la línea 11 de cover.css a: text-shadow: 2px 2px 8px lightgreen;


<img src="capturas_img/19.png" alt="captura18" width="400"/>


*user1* hará un commit especificando en el mensaje de commit el cambio hecho (sombra) y que se cierra la issue creada (usar referencia a la issue). A continuación subirá los cambios a origin/main.


<img src="capturas_img/20.png" alt="captura19" width="400"/>


*user1* etiquetará esta versión (en su copia local) como 0.1.0 y después de subir los cambios creará una "release" en GitHub apuntando a esta etiqueta.


<img src="capturas_img/21_1.png" alt="captura21" width="400"/>

<img src="capturas_img/21_2.png" alt="captura21" width="400"/>

<img src="capturas_img/21_3.png" alt="captura21" width="400"/>


#### ***Conclusiones***. <a name="id5"></a>

 El uso de git y github facilita muchísimo las tareas a distancia (en remoto) y es una herramienta importante en el campo de la informática a la hora de hacer código en un equipo de trabajo. 
 
 A nuestro parecer es importante aprenderlo para que, a la hora de entrar en una empresa y trabajar con mas gente, podamos manejarnos para no hacer perder tiempo al equipo.
