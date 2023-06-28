# Codebuch Projekt Mafia Cosa Nostra

Wie sind die Mitglieder der Cosa Nostra, die in den Maxi-Prozessen 1986/87 verurteilt wurden, miteinander vernetzt?

**Node-Attribute**

-   id: Kürzel der Knoten
-   name: Namen der Mafia-Mitglieder/Clans
-   nameshort: id (Kürzel)
-   nickname: Spitzname des Mitglieds
-   age: Alter nach Geburtsjahr
-   city: Geburtsort
-   familyclan: Zugehörigkeit zu Familie
-   position: z.B. Boss
-   crime: Verbrechensart
          - Drogenhandel
          - Mord
-   sentence: Haftstrafe in Jahren (numerisch)

**Edge-Attribute**

-   relation: Art der Beziehung: 
                - family: Familienzugehörigkeit
                - ally: Verbündete
                - conflict

-   weight: Intensität der Beziehung
                - family: 1= 2. Grades, 2= 1. Grades
                -  ally: 1 = Bekannte, 2 = Freunde

-   type: Zugehörigkeit zu Familienclan
-   range: Jahr der Beziehung
               
