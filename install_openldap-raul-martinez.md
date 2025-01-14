Passos
1.- Nom del servidor
Primer canviem el nom de la màquina:

sudo hostnamectl set-hostname ldapserver.dungeonofbits.com
Després afegim a /etc/hosts les modificacions necessàries:
sudo nano /etc/hosts

![image](https://github.com/user-attachments/assets/f3cc5330-db36-47e8-a66f-31474a042496)

2.- Actualitzem software
Actualitzarem els repositoris de software de l'equip amb la comanda següent:

sudo apt update
3.- Instal·la slapd i ldap-utils
Instal·lem el software necessari amb la comanda:

sudo apt install slapd ldap-utils
Ens demanarà la contrasenya d'administrador:
