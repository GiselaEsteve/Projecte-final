# Projecte-final
Detector de Phishing en Correus Electrònics

1. **Descripció**

Aquest projecte consisteix en una aplicació creada en Python que permet detectar correus electrònics sospitosos de phishing. Utilitzant la biblioteca tkinter per a la creació d'una interfície gràfica, l'usuari pot introduir informació  sobre un correu electrònic (remitent, assumpte, cos del correu i arxius adjunts) i l'aplicació realitza un anàlisi per determinar si el correu pot ser legítim o sospitós de phishing.

El sistema realitza diverses comprovacions, incloent:

- Validació del domini del remitent.
- Anàlisi de paraules clau en l'assumpte del correu.
- Verificació d'enllaços sospitosos dins del cos del correu.
- Comprovació d'extensions perilloses en els arxius adjunts.

Els resultats es mostren en la interfície gràfica i es poden desar en un fitxer de text per a futures revisions.

2. **Requeriments**

Per poder executar aquest codi, necessitaràs els següents requisits:

- Python 3.x
- Biblioteca tkinter (generalment preinstal·lada amb Python)
- Biblioteca re per a l'ús de expressions regulars (també preinstal·lada amb Python)

3. **Com utilitzar l'aplicació**

- *Executar el codi*
- *Interfície gràfica:*

Un cop executada l'aplicació, es mostrarà una finestra amb diversos camps per introduir la informació del correu electrònic.

Completa els camps de remitent, assumpte, cos del correu i arxius adjunts.

Fes clic al botó "Analitzar Correu" per iniciar l'anàlisi.

Els resultats de l'anàlisi apareixeran a la part inferior de la finestra. També es guardarà un fitxer resultats_analisis.txt amb els resultats obtinguts.

- *Netejar els camps:*

Si vols analitzar un altre correu electrònic, pots fer clic al botó "Limpiar" per restablir tots els camps a les condicions inicials.
