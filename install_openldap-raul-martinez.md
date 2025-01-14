Passos
**1.- Nom del servidor
**
Primer canviem el nom de la màquina:

sudo hostnamectl set-hostname ldapserver.dungeonofbits.com
Després afegim a /etc/hosts les modificacions necessàries:

sudo nano /etc/hosts

![image](https://github.com/user-attachments/assets/f3cc5330-db36-47e8-a66f-31474a042496)

**2.- Actualitzem software
**
Actualitzarem els repositoris de software de l'equip amb la comanda següent:

sudo apt update

![image](https://github.com/user-attachments/assets/ab9d9931-2af4-4f77-ae14-dd81095b9bfd)


**3.- Instal·la slapd i ldap-utils
**
Instal·lem el software necessari amb la comanda:

sudo apt install slapd ldap-utils

![image](https://github.com/user-attachments/assets/074c1bd5-bc1f-47be-8b52-7bde7d985fca)

Ens demanarà la contrasenya d'administrador:

![image](https://github.com/user-attachments/assets/adf836f5-8f85-4427-8f26-f4fad70a8cd1)

![image](https://github.com/user-attachments/assets/fd6bba98-6a5d-4b39-a446-d5d0c209528d)

**4.- Configuració:**

Introduïm la comanda:

sudo dpkg-reconfigure slapd

Ens preguntarà si volem ometre la configuració del servidor LDAP, diem que NO.

![image](https://github.com/user-attachments/assets/ac029196-ed7a-49d0-b4f0-208ac410200b)

Escollim el nom del domini:

![image](https://github.com/user-attachments/assets/9b76a9bb-4324-46d5-8209-0582ab530be1)

I el nom de l'empresa que fa la instal·lació:

![image](https://github.com/user-attachments/assets/a278fc4b-27bf-4aef-9d7e-29edd2705bdf)

Introduim i confirmem una contrasenya:

![image](https://github.com/user-attachments/assets/998e8866-753e-441c-94fb-bc1c5f6e8b28)

Confirmem que volem que s'esborri la BBDD quan eliminem LDAP:

![image](https://github.com/user-attachments/assets/6688adc8-124d-4ade-ab7e-a66a7e04202f)

Després ens avisa que queden fitxers antics de la BBDD i que si els volem moure, diem que sí:

![image](https://github.com/user-attachments/assets/09d76d4e-a0de-4071-ba4b-e6e05f15e432)

Ja estaria:

![image](https://github.com/user-attachments/assets/d005645a-1eff-4359-a357-30002e82968f)

**5.- Comprovem la instal·lació:
**
Comprovem que s'ha instal·lat bé amb la comanda:

sudo slapcat

![image](https://github.com/user-attachments/assets/8405d12c-7767-4736-a84e-1c7cab2ac0b9)


