## Inleiding
In de les hebben we het gehad over Maven en unitTesten. 

Iedere applicatie die we maken, willen we opleveren inclusief testen. Dit is belangrijk, omdat dit een groot aantal bugs uit de applicatie kan halen, voordat de applicatie in productie gaat.


## Opdrachtbeschrijving
We gaan een applicatie maken om een familie stamboom te maken. Iedereen heeft familieleden: van sommige houden we heel veel en van sommige misschien wat minder. Maar hoe dan ook hebben we allemaal familie.
Voor deze applicatie hoeven we niet allerlei moeilijke opties toe te voegen.
In de applicatie die we gaan maken, is het mogelijk om nieuwe personen en huisdieren toe te voegen aan de familie stamboom. Wanneer we bijvoorbeeld kinderen toevoegen aan een persoon in de stamboom, is het natuurlijk wel zo netjes om deze persoon gelijk neer te zetten als vader of moeder. Naast deze methode gebruiken we nog meer familie gerelateerde methodes binnen deze applicatie. 

![Family!](./assets/Family.JPG)


## Randvoorwaarden
De opdracht moet voldoen aan de volgende voorwaarden:

- minimaal 1 `Person`
- minimaal 1 `Pet`
- alle methodes (behalve de getters en setters) worden getest door een unittest

De `Person` heeft volgende attributen:

- name
- middleName
- lastName
- sex
- age
- mother
- father
- siblings
- children
- pets

De `Pet` heeft minimaal de volgende attributen:

- name
- age
- species
- owner

De `Person` bevat naast de attributen het volgende:

- constructor met name, lastname, age en sex
- constructor met name, middleName, lastname, age en sex
- getters & setters
- addParents methode
- addChild methode
- addPet methode
- addSibling methode
- getGrandChildren methode

De `Pet` bevat naast de attributen minimaal:

- een constructor met alle attributen op 'owner' na
- getters & setters


## Stappenplan
Let op: het is uitdagender om jouw eigen stappenplan te maken. Als je niet zo goed weet waar je moet beginnen, kun je onderstaand stappenplan gebruiken.

1. Maak de benodigde klassen aan.

2. Geef de klassen de juiste attributen.

3. Maak de constructors aan binnen de klassen.

4. Maak alle getters & setters.

5. Schrijf de benodigde methodes in de juiste klassen.

6. Voeg Maven toe aan het project.

6. Schrijf voor alle methodes unittesten op de juiste locatie in de project structuur.


## Bonusopdrachten
Als je de bonusopdrachten maakt, zorg dan dat deze ook getest worden!

1. Schrijf een methode om alle dieren van de kleinkinderen terug te geven van een persoon. 
2. Schrijf een methode om alle nichtjes terug te geven van een persoon.
3. Voeg een partner toe aan de `Person` en implementeer deze partner door de gehele applicatie inclusief getter & setter en benodigde methodes.
