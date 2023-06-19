# Codebuch Projekt Mafia

Wie sind die Mitglieder der Cosa Nostra, die in den Maxi-Prozessen 1986/87 verurteilt wurden, miteinander vernetzt?

**Node-Attribute**

-   id: Kürzel der Knoten
-   name: Namen der Mafia-Mitglieder
-   nickname: Spitzname des Mitglieds
-   age: Alter
-   city: Geburtsort
-   familyclan: Zugehörigkeit zu Familie
-   crime: Verbrechensart
-   sentence: Strafe

**Edge-Attribute**

-   relation: Art der Beziehung: 
                - family: Familienzugehörigkeit
                - ally: Verbündete
                - conflict

-   weight: Intensität der Beziehung
                - family: 1= 1. Grades, 2= 2. Grades
                -  ally: 1 = Bekannte, 2 = Freunde 3 = Unterworfen
               
