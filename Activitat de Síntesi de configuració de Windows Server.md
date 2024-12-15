Activitat 1: Gestió de Disc i Còpia de Seguretat
Tasques
Crea una partició dedicada per a les còpies de seguretat amb Diskpart:

Obre l'índex de comandes com a administrador.
Executa diskpart.
Llista els discs disponibles amb list disk.
Selecciona el disc on vols crear la partició (substitueix X pel número del disc): select disk X.
Crea una nova partició (substitueix Y per la mida en MB): create partition primary size=Y.
Formata la partició: format fs=ntfs quick.
Assigna una lletra d'unitat (substitueix Z per la lletra que vulguis): assign letter=Z.
Sortir de Diskpart: exit.
Programa una tasca setmanal de còpia de seguretat:

Obre el Programador de Tasques.
Crea una nova tasca.
A la pestanya "General", dóna un nom a la tasca (per exemple, "Còpia de Seguretat Setmanal").
A la pestanya "Triggers", afegeix un nou trigger setmanal.
A la pestanya "Accions", selecciona "Iniciar un programa" i especifica el programa de còpia de seguretat (per exemple, wbadmin o un altre programari de còpia de seguretat).
Configura la ruta de destinació a la partició creada (Z:).
Configura el Visor d’Esdeveniments per enviar una alerta si la còpia de seguretat falla:

Obre el Visor d'Esdeveniments.
Navega a "Registres d'Aplicacions i Serveis" > "Microsoft" > "Windows" > "Backup" > "Operational".
Crea una nova regla d'alerta per esdeveniments d'error (ID d'esdeveniment 1, 2, etc.).
Configura l'alerta per enviar un correu electrònic o mostrar un missatge.
Executa la còpia de seguretat manualment i verifica el funcionament de l’alerta:

Executa la tasca de còpia de seguretat manualment des del Programador de Tasques.
Comprova el Visor d'Esdeveniments per assegurar-te que l'alerta s'ha activat si hi ha hagut un error.
Resultats esperats
Partició per a còpies de seguretat creada.
Tasca de còpia de seguretat programada i funcional.
Sistema de monitorització d’esdeveniments actiu amb alertes.
Activitat 2: Automatització de Manteniment i Control del Sistema
Tasques
Crea una tasca per netejar fitxers temporals i optimitzar el sistema:

Obre el Programador de Tasques.
Crea una nova tasca.
A la pestanya "Accions", selecciona "Iniciar un programa" i especifica cleanmgr.exe per netejar fitxers temporals.
Programa la tasca per executar-se setmanalment.
Programa una tasca per reiniciar el servidor setmanalment:

Crea una nova tasca al Programador de Tasques.
A la pestanya "Accions", selecciona "Iniciar un programa" i especifica shutdown.exe amb els arguments /r /t 0 per reiniciar immediatament.
Programa la tasca per executar-se setmanalment.
Configura el Monitor d’Esdeveniments per registrar l’ús de CPU, memòria i disc:

Obre el Monitor de Rendiment.
Crea un nou conjunt de dades per registrar l'ús de CPU, memòria i disc.
Configura el registre per guardar les dades en un fitxer per a la seva revisió posterior.
Assegura que serveis essencials es reinicien automàticament si s'aturen:

Obre el Gestor de Serveis.
Selecciona el servei que vols configurar.
