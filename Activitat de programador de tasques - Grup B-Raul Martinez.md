Activitat 1: Recordatori per comprar el pa
Obre el Programador de Tasques:

Cerca "Programador de Tasques" al menú d'inici i obre'l.
Crea una nova tasca:

Fes clic a "Crear tasca" al panell dret.
A la pestanya "General", dona un nom a la tasca (per exemple, "Recordatori de compra de pa").
A la pestanya "Triggers", fes clic a "Nou" i selecciona "A una hora programada". Escull un moment durant la classe (per exemple, 10:30 AM).
A la pestanya "Accions", fes clic a "Nou" i selecciona "Mostrar un missatge" (si la teva versió de Windows ho permet) o "Iniciar un programa" i escriu powershell.exe amb l'argument -Command "Add-Type -AssemblyName System.Windows.Forms; [System.Windows.Forms.MessageBox]::Show('X Y has de comprar el pa')" (substitueix X Y pel teu nom i cognom).
A la pestanya "Condicions", assegura't que "Iniciar la tasca només si l'ordinador està alimentat" no estigui seleccionat.
Fes clic a "D'acord" per guardar la tasca.
Verifica que funciona:

Espera fins a l'hora programada i comprova si apareix el missatge.
Activitat 2: Programa el reinici de l'ordinador
Crea una nova tasca:

Obre el Programador de Tasques.
Fes clic a "Crear tasca".
A la pestanya "General", dona un nom a la tasca (per exemple, "Reinici de l'ordinador").
A la pestanya "Triggers", fes clic a "Nou" i selecciona "A una hora programada". Escull un moment durant la classe (per exemple, 10:35 AM).
A la pestanya "Accions", selecciona "Iniciar un programa" i escriu shutdown.exe amb els arguments /r /t 0.
Fes clic a "D'acord" per guardar la tasca.
Verifica que funciona:

Espera fins a l'hora programada i comprova si l'ordinador es reinicia.
Activitat 3: Obre el navegador amb la web de l'institut
Crea una nova tasca:

Obre el Programador de Tasques.
Fes clic a "Crear tasca".
A la pestanya "General", dona un nom a la tasca (per exemple, "Obrir navegador amb web de l'institut").
A la pestanya "Triggers", fes clic a "Nou" i selecciona "Al iniciar sessió".
A la pestanya "Accions", selecciona "Iniciar un programa" i escriu la ruta del navegador (per exemple, C:\Program Files\Google\Chrome\Application\chrome.exe) i com a paràmetre, escriu la URL de la web de l'institut (per exemple, http://www.institut.edu).
Fes clic a "D'acord" per guardar la tasca.
Verifica que funciona:

Tanca la sessió i torna a iniciar sessió per veure si s'obre el navegador amb la web de l'institut.
Activitat 4: Executa una aplicació a una hora determinada
Crea una nova tasca:

Obre el Programador de Tasques.
Fes clic a "Crear tasca".
A la pestanya "General", dona un nom a la tasca (per exemple, "Executar aplicació").
A la pestanya "Triggers", fes clic a "Nou" i selecciona "A una hora programada". Escull un moment durant la classe (per exemple, 10:40 AM).
A la pestanya "Accions", selecciona "Iniciar un programa" i escriu la ruta de l'aplicació que vols executar (per exemple, C:\Program Files\Aplicacio\aplicacio.exe).
Fes clic a "D'acord" per guardar la tasca.
Verifica que funciona
