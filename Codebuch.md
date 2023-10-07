# Codebuch Projekt Mafia Cosa Nostra

Wie sind die Mitglieder der Cosa Nostra, die in den Maxi-Prozessen 1986/87 verurteilt wurden, miteinander vernetzt?


**Node-Attribute**

-   id: Kürzel der Knoten
-   name: Namen der Mafia-Mitglieder bzw. Clans
-   nameshort: id (Kürzel)
-   nickname: Spitzname des Mitglieds
-   age: Alter nach Geburtsjahr
-   city: Geburtsort
-   familyclan: Zugehörigkeit zu Familienclan
-   type: member oder clan
-   position: z.B. Boss oder Mitglied, besondere Ämter
-   crime: Verbrechensart
          - Drogenhandel
          - Schmuggel
          - Mord(e)
-   sentence: Haft-/Geldstrafe 1. und 2. Grades in Jahren (numerisch)

**Edge-Attribute**
-   from, to
-   relation: Art der Beziehung:
                - family: Familienclan-Zugehörigkeit
                - ally: Verbündete
                - conflict

-   weight: Intensität der Beziehung
                - family: 1 = gleicher Familienclan 2= gleicher Familienclan + blutsverwandt
                - ally: 1 = Bekannte, 2 = Freunde, 3 = blutsverwandt (aber nicht gleicher Clan)
                - conflict: 1 = Konflikt
    
-   type: Zugehörigkeit zu Familienclan oder Beziehung zwischen Verurteilten
          - clan
          - member

               
