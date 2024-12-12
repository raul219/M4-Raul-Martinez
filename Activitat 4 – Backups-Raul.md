NOTA: X representa el teu cognom
Crea una pàgina web on resolguis les següents activitats. Afegeix captures de
pantalla i explicacions de cada pas que donis.
**Activitat 1:** Crea i explica les comandes per fer còpia de seguretat i restaurar el
directori /var/www amb la comanda tar.
• sudo tar -czvf /home/xavi/mohaguapo.tar /var/www
![image](https://github.com/user-attachments/assets/0b39a1a9-0de0-4de0-9b82-6f5374932c3b)
**EXPLICACIO**
-c crea un nou arxiu tar.
-z comprimeix l'arxiu amb gzip.
-v mostra el progrés de la creació de l'arxiu.
-f especifica el nom de l'arxiu.
/home/xavi/mohaguapo.tar és el nom de l'arxiu que es crearà.
/var/www és el directori que es vol fer còpia de seguretat.

• sudo tar -xzvf /home/xavi/mohaguapo.tar -C /
![image](https://github.com/user-attachments/assets/2f81dfdb-1f32-46bb-a2f3-56c7e6a9780f)

**EXPLICACIO**
sudo tar -xzvf /home/xavi/mohaguapo.tar -C /:
-x extrau l'arxiu tar.
-z descomprimeix l'arxiu amb gzip.
-v mostra el progrés de l'extracció de l'arxiu.
-f especifica el nom de l'arxiu.
/home/xavi/mohaguapo.tar és el nom de l'arxiu que es vol extraure.
-C / especifica el directori on es vol extraure l'arxiu.

**Activitat 2:** Crea i explica les comandes per fer còpies de seguretat i restaurar el
directori /var/www amb la comanda rsync.
![image](https://github.com/user-attachments/assets/ed1c7914-ee0f-4730-84c9-f82646d46eae)

**EXPLICACIO**
sudo rsync -avz /var/www /home/xavi/mohaguapo:
-a preserva els permisos i els propietaris dels fitxers.
-v mostra el progrés de la creació de la còpia de seguretat.
-z comprimeix la transferència de dades.
/var/www és el directori que es vol fer còpia de seguretat.
/home/xavi/mohaguapo és el directori on es vol crear la còpia de seguretat.
sudo rsync -avz /home/xavi/mohaguapo /var/www:
-a preserva els permisos i els propietaris dels fitxers.
-v mostra el progrés de la restauració de la còpia de seguretat.
-z comprimeix la transferència de dades.
/home/xavi/mohaguapo és el directori que conté la còpia de seguretat.
/var/www és el directori on es vol restaurar la còpia de seguretat.

**Activitat 3:** Utilitzant els comandaments de Dump i restore:
• Crea una carpeta al teu home anomenada /Xbackup.
• Dins la carpeta guarda dues imatges.
• Fes un backup amb dump al fitxer /tmp/Xbackup de la carpeta.
• Esborra les imatges.
• Recupera amb restore les imatges a la carpeta que ara està buida.

**EXPLICACIO**
**Activitat 4:** repeteix l’activitat anterior amb tar.
**Activitat 5:** Repeteix l’activitat anterior amb rsync.
**Activitat 6:** Utilitza deja-dup per fer una còpia de seguretat del teu directori
/home/usuari
**Activitat 7:** Busca un altre programa de backups en entorn gràfic i fes una copia de
seguretat de /home/usuari. Documenta el procés.
