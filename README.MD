marcos@marcos-VirtualBox:~/Escritorio$ cd Escritorio

bash: cd: Escritorio: No existe el archivo o el directorio

marcos@marcos-VirtualBox:~/Escritorio$ pwd

/home/marcos/Escritorio

marcos@marcos-VirtualBox:~/Escritorio$ ls -R

.:

marcos@marcos-VirtualBox:~/Escritorio$ ll

total 8

drwxr-xr-x  2 marcos marcos 4096 nov 14 13:19 ./

drwxr-x--- 27 marcos marcos 4096 nov 23 12:03 ../

marcos@marcos-VirtualBox:~/Escritorio$ passwd -h

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

  -R, --root CHROOT_

  marcos@marcos-VirtualBox:~/Escritorio$ date

mié 23 nov 2022 12:05:40 CET

marcos@marcos-VirtualBox:~/Escritorio$ cd

marcos@marcos-VirtualBox:~$ cat > materias

ED

LM

PRO

INGLES

FOL

SI

BD

marcos@marcos-VirtualBox:~$ mkdir grado Iru

marcos@marcos-VirtualBox:~$ mv materias grado

marcos@marcos-VirtualBox:~$ cd grado

marcos@marcos-VirtualBox:~/grado$ mv materias asignaturas

marcos@marcos-VirtualBox:~/grado$ ls

asignaturas

marcos@marcos-VirtualBox:~/grado$ rm -r asignaturas

marcos@marcos-VirtualBox:~/grado$ cd

marcos@marcos-VirtualBox:~$ rm -r grado Iru

marcos@marcos-VirtualBox:~$




