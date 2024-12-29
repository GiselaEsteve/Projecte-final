# Projecte-final
Detector de Phishing en Correus Electrònics

1. Descripció
  Aquest projecte consisteix en una aplicació creada en Python que permet detectar correus electrònics sospitosos de         
  phishing. Utilitzant la biblioteca tkinter per a la creació d'una interfície gràfica, l'usuari pot introduir informació 
  sobre un correu electrònic (remitent, assumpte, cos del correu i arxius adjunts) i l'aplicació realitza un anàlisi per 
  determinar si el correu pot ser legítim o sospitós de phishing.

El sistema realitza diverses comprovacions, incloent:

Validació del domini del remitent.
Anàlisi de paraules clau en l'assumpte del correu.
Verificació d'enllaços sospitosos dins del cos del correu.
Comprovació d'extensions perilloses en els arxius adjunts.
Els resultats es mostren en la interfície gràfica i es poden desar en un fitxer de text per a futures revisions.

Requeriments
Per poder executar aquest codi, necessitaràs els següents requisits:

Python 3.x
Biblioteca tkinter (generalment preinstal·lada amb Python)
Biblioteca re per a l'ús de expressions regulars (també preinstal·lada amb Python)
Com instal·lar Python i les biblioteques
Instal·lar Python: Si encara no tens Python, pots descarregar-lo des de python.org.

Verificar la instal·lació de tkinter: En la majoria de casos, tkinter ja està inclòs en la instal·lació de Python. Si no és així, pots instal·lar-lo amb:

bash
Copiar código
pip install tk
Verificar la instal·lació de re: La biblioteca re forma part de la biblioteca estàndard de Python, així que no cal instal·lar-la per separat.

Com utilitzar l'aplicació
Executar el codi:

Descarrega el fitxer .py del projecte.
Obre una terminal o línia de comandes.
Navega fins al directori on tens el fitxer i executa la següent ordre:
bash
Copiar código
python detector_phishing.py
Interfície gràfica:

Un cop executada l'aplicació, es mostrarà una finestra amb diversos camps per introduir la informació del correu electrònic.
Completa els camps de remitent, assumpte, cos del correu i arxius adjunts.
Fes clic al botó "Analitzar Correu" per iniciar l'anàlisi.
Els resultats de l'anàlisi apareixeran a la part inferior de la finestra. També es guardarà un fitxer resultats_analisis.txt amb els resultats obtinguts.
Netejar els camps:

Si vols analitzar un altre correu electrònic, pots fer clic al botó "Limpiar" per restablir tots els camps a les condicions inicials.
Limitacions
Precisió: Tot i que l'aplicació utilitza llistes de dominis sospitosos i paraules clau conegudes, la detecció de phishing no és 100% precisa. Alguns correus legítims poden ser marcats com a sospitosos i alguns intents de phishing poden passar desapercebuts.
Dependència de llistes predefinides: L'aplicació depèn de llistes de dominis i enllaços sospitosos que poden no estar actualitzades en tot moment. És important mantenir aquestes llistes actualitzades per millorar la seguretat.
Archivos adjunts: Si els arxius adjunts no són proporcionats en el format correcte (separats per comes), l'aplicació pot no detectar-los correctament.
