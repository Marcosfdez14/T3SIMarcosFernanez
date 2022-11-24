#Ejercicio 1. Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:

---

> Hare que mi directorio actual (Escritorio) sea el padre de mi directorio de inicio

 ~~~
cd /home
 ~~~


> Visualizo la ruta de acceso a mi directorio actual

 ~~~
 pwd
 ~~~
 > Salida del comando:
~~~
/home
~~~
___

> Para obtener un listado de ficheros/directorios que cuelgan de mi directorio de trabajo actual
 ~~~
 ls
 ~~~

> Salida del comando:
~~~
marcos
~~~
___

> Realizo un listado recursivo de mi directorio de inicio
 ~~~
 ls -R
  ~~~

> Salida del comando:
~~~

.:
marcos

./marcos:
Descargas  directories  Documentos  dos  ejercicios  Ejercicos  Escritorio  help  Imágenes  make  marcos  Marcos  marcos1  Música  Plantillas  Público  snap  tres  uno  Vídeos

./marcos/Descargas:

./marcos/directories:

./marcos/Documentos:

./marcos/dos:

./marcos/ejercicios:

./marcos/Ejercicos:

./marcos/Escritorio:

./marcos/help:

./marcos/Imágenes:

./marcos/make:

./marcos/marcos:
directorio  ejercicio3  home  jercicio3  marcos

./marcos/marcos/directorio:

./marcos/marcos/home:

./marcos/marcos/jercicio3:

./marcos/Marcos:
'[fichero]'   nombres

./marcos/Marcos/nombres:

./marcos/marcos1:

./marcos/Música:

./marcos/Plantillas:

./marcos/Público:

./marcos/snap:
snapd-desktop-integration  snap-store

./marcos/snap/snapd-desktop-integration:
14  common  current

./marcos/snap/snapd-desktop-integration/14:
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos

./marcos/snap/snapd-desktop-integration/14/Desktop:

./marcos/snap/snapd-desktop-integration/14/Documents:

./marcos/snap/snapd-desktop-integration/14/Downloads:

./marcos/snap/snapd-desktop-integration/14/Music:

./marcos/snap/snapd-desktop-integration/14/Pictures:

./marcos/snap/snapd-desktop-integration/14/Public:

./marcos/snap/snapd-desktop-integration/14/Templates:

./marcos/snap/snapd-desktop-integration/14/Videos:

./marcos/snap/snapd-desktop-integration/common:

./marcos/snap/snap-store:
582  599  common  current

./marcos/snap/snap-store/582:

./marcos/snap/snap-store/599:

./marcos/snap/snap-store/common:

./marcos/tres:

compa  companeros  nombres

./marcos/uno:
compa  companeros  grupo  nombres
~~~
___
> Para pedir ayuda al comando passwd

 ~~~
 passwd -h
 ~~~
 
 > Salida del comando:
~~~
Modo de uso: passwd [opciones] [USUARIO]

Opciones:

  -a, --all                     informa del estado de las contraseñas de

                                todas las cuentas

  -d, --delete                  borra la contraseña para la cuenta indicada

  -e, --expire                  fuerza a que la contraseña de la cuenta

                                caduque

  -h, --help                    muestra este mensaje de ayuda y termina

  -k, --keep-tokens             cambia la contraseña sólo si ha caducado

  -i, --inactive INACTIVO       establece la contraseña inactiva después de

                                caducar a INACTIVO

  -l, --lock                    bloquea la contraseña de la cuenta indicada

  -n, --mindays DÍAS_MIN        establece el número mínimo de días antes

                                de que se cambie la contraseña a DÍAS_MIN

  -q, --quiet                   modo silencioso

  -r, --repository REP          cambia la contraseña en el repositorio REP

  -R, --root CHROOT_DIR         directorio en el que hacer chroot

  -S, --status                  informa del estado de la contraseña la cuenta

                                indicada

  -u, --unlock                  desbloquea la contraseña de la cuenta indicada

  -w, --warndays DÍAS_AVISO     establece el aviso de caducidad a DÍAS_AVISO

  -x, --maxdays DÍAS_MAX        establece el número máximo de días antes de

                                cambiar la contraseña a DÍAS_MAX

~~~
___
> Para obtener la fecha y hora del sistema 

 ~~~
 date
 ~~~

> Salida del comando:
~~~
jue 24 nov 2022 11:18:12 CET
~~~
___
> Para ir al directorio de inicio

 ~~~
 cd
 ~~~

> Para crear un fichero llamado "materias"

 ~~~
 cat > materias
 ~~~

> Salida del comando:
~~~
ED

LM

PRO

SI

BD

INGLES

FOL
~~~
___
Escribimos el contenido deseado y para terminar la operacion presionamos ctrl + d

> Con un solo comando crearemos los directorios grado y Iru

 ~~~
 mkdir grado Iru
 ~~~

> Para mover un fichero ("materias") para que cuelgue de un directorio ("grado") con el nombre de asignaturas

 ~~~
 mv materias grado
 cd grado
 mv materias asignaturas
 ~~~

> Para visualizar los ficheros/directorios de mi directorio de trabajo actual , asi sabremos donde esta mi fichero asignaturas

 ~~~
 ls
 ~~~

> Salida del comando:
~~~
asignaturas
~~~
___
> Para eliminar el fichero asignaturas

 ~~~
 rm -r asignaturas
 ~~~

> Para subir a mi directorio de inicio

 ~~~
 cd
 ~~~

> Para eliminar con un solo comando dos directorios ("grado , Iru")

 ~~~
 rm -r grado Iru
 ~~~

