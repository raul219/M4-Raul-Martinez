Activitat 1: Configuració del servidor
Pas 1: Canviar el nom del servidor
Obre el Panell de Control:

Cerca "Panell de Control" al menú d'inici i obre'l.
Accedeix a "Sistema":

Fes clic a "Sistema i seguretat" i després a "Sistema".
Canvia el nom del servidor:

Fes clic a "Canvia configuració" al costat del nom del servidor.
A la pestanya "Nom del servidor", fes clic a "Canviar".
Introduïu el nou nom del servidor (per exemple, Win-X, on X és el teu cognom).
Fes clic a "D'acord" i reinicia el servidor quan se't demani.
Pas 2: Instal·lar el rol de Servei de domini d'Active Directory
Obre el Gestor del servidor:

Cerca "Gestor del servidor" al menú d'inici i obre'l.
Afegeix el rol:

Fes clic a "Afegir rols i característiques".
Segueix l'assistent i selecciona "Instal·lar rols o característiques".
Selecciona "Servidor de domini" d'Active Directory i segueix les instruccions per completar la instal·lació.
Pas 3: Promocionar el servidor a controlador de domini
Promociona el servidor:
Un cop instal·lat el rol, apareixerà una opció per promocionar el servidor a controlador de domini. Fes clic a "Promocionar aquest servidor a controlador de domini".
Selecciona "Afegir un nou domini a un nou bosquet" i introdueix el nom del domini (per exemple, X.com, on X és el teu cognom).
Completa l'assistent, configurant les opcions que necessitis (com ara la contrasenya del mode de restauració de serveis d'Active Directory).
Fes clic a "Instal·lar" i espera que el procés acabi. El servidor es reiniciarà automàticament.
Pas 4: Captura de pantalla
Un cop completat el procés, captura una imatge de la pantalla que mostri el nom del servidor i el domini creat.
Activitat 2: Creació de la màquina virtual
Pas 1: Crear una màquina virtual
Obre el teu hypervisor:

Utilitza un hypervisor com Hyper-V, VMware Workstation o VirtualBox.
Crea una nova màquina virtual:

Selecciona "Nova màquina virtual" i segueix l'assistent.
Dona-li un nom a la màquina virtual (per exemple, W10-X, on X és el teu cognom).
Selecciona el sistema operatiu com a Windows 10.
Configura la quantitat de memòria RAM i CPU que desitgis per a la màquina virtual.
Crea un disc dur virtual (VHD) amb la mida que consideris adequada (recomanat mínim 60 GB).
Instal·la Windows 10:

Adjunta la imatge ISO de Windows 10 com a mitjà d'instal·lació.
Inicia la màquina virtual i segueix les instruccions per instal·lar Windows 10.
