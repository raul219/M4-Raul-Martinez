Crea un repositori de Github on responguis les següents qüestions: 

Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.

![image](https://github.com/user-attachments/assets/0c31b226-f4c6-4c71-bfad-621eb6f608a2)

![image](https://github.com/user-attachments/assets/3f27c4c7-b20c-47fc-a4b5-65a4d127b827)

Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.

![image](https://github.com/user-attachments/assets/8d8f80b1-6f93-4013-896a-6f408117c0a3)

Reinicia el servei SAMBA.

![image](https://github.com/user-attachments/assets/0e4df1bb-cd2f-4f41-93d0-1b342c607a58)

Comprova que tens accés des de Windows.

![image](https://github.com/user-attachments/assets/c95b0444-2d81-4e2d-a887-6079d35abb36)

Crea algun fitxer a la carpeta.

![image](https://github.com/user-attachments/assets/76d3dfaa-d34e-4c25-bc7e-37db047faa3b)

Comprova que s'ha creat a Linux.

![image](https://github.com/user-attachments/assets/fc535107-8ef4-4efe-a829-effaeb39297e)

Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.

![image](https://github.com/user-attachments/assets/e1844034-5366-413f-b009-9b19cff32f6a)

Crea un usuari local anomenat user1_X (on X és el teu cognom).

![image](https://github.com/user-attachments/assets/459d398e-acee-4cad-af29-ad78aec1fc19)

Afegeux l'usuari anterior a SAMBA.

![image](https://github.com/user-attachments/assets/b0961c90-1109-43e1-b344-45cfeed1c56d)

Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.

![image](https://github.com/user-attachments/assets/a8d82345-5c84-49bf-947f-4b9b78b1b8b0)

Reinicia el servei SAMBA.

![image](https://github.com/user-attachments/assets/d642cc92-f167-4f80-a09f-20dd51e76912)

Comprova que tens accés des de Windows amb les credencials de l'usuari.

![image](https://github.com/user-attachments/assets/8df30648-7b8e-4486-84cf-9e930f258979)

Crea algun fitxer a la carpeta.

![image](https://github.com/user-attachments/assets/5a6a84a2-9987-4d08-bfb9-fc30baca7bd3)

Comprova que s'ha creat a Linux i té els permisos 755.

![image](https://github.com/user-attachments/assets/1a2d664b-cb8c-42e4-8111-80b0ad6f4357)
