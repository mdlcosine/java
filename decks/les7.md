# Les 7
## Technisch ontwerp
### Start 18:00



# Agenda
* Weekend SME <!-- .element: class="fragment "  -->
* Vragen over de vorige les <!-- .element: class="fragment "  -->
* Recap Maven en JUnit <!-- .element: class="fragment "  -->
* Software Development Life Cycle <!-- .element: class="fragment "  -->
* Requirements <!-- .element: class="fragment "  -->
* Klassendiagram <!-- .element: class="fragment "  -->
* Lesopdracht <!-- .element: class="fragment "  -->
* Bespreken lesopdracht (20:35u) <!-- .element: class="fragment "  -->
* Optioneel (Mutatie testen) <!-- .element: class="fragment "  -->


# Poll en Evaluatie


# Uitslag Poll



# Wat weet je nog over Maven?
[Flinga (FG2BAjP)](https://flinga.fi/s/FG2BAJP)



# Wat weet je nog over JUnit?
[Flinga (FG2BAJP)](https://flinga.fi/s/FG2BAJP)



### Software Development Lifecycle
1. Analyse Customer Requirements <!-- .element: class="fragment "  -->
2. Design the program <!-- .element: class="fragment "  -->
3. Code the program <!-- .element: class="fragment "  -->
4. Document and test <!-- .element: class="fragment "  -->
5. Operate and maintain <!-- .element: class="fragment "  -->


### Recap
[Flinga (FG2BAJP)](https://flinga.fi/s/FG2BAJP)



> Waarom eigenlijk documentatie?
[Flinga (FG2BAJP)](https://flinga.fi/s/FG2BAJP)



# Requirements


### Business eisen
> “Welk doel dient het en welk resultaat willen we ermee behalen?”


### Stakeholder eisen
> “Welk probleem lost de software op voor de stakeholders?”


### Systeem eisen
> “Wat moet de software doen?”



### Wij richten ons op Systeem eisen
* Functionele eisen <!-- .element: class="fragment "  -->
* Niet-functionele eisen <!-- .element: class="fragment "  -->


# Functionele eisen
> Winkelmedewerkers voegen nieuwe bestellingen toe door het bestelformulier in te vullen.


# Functionele eisen
> Het systeem checkt direct of het ingevoerde adres geldig is. Zo niet, dan wordt een foutmelding getoond en kan het formulier niet worden verstuurd.


# Functionele eisen
> Aan het eind van de dag (17:00 uur) stuurt de server automatisch een rapport van openstaande bestellingen naar de manager.



# Niet-functionele eisen
1. Gebruiksvriendelijkheid <!-- .element: class="fragment "  -->
2. Betrouwbaarheid <!-- .element: class="fragment "  -->
3. Prestatie <!-- .element: class="fragment "  -->
4. Ondersteuning <!-- .element: class="fragment "  -->
5. Veiligheid <!-- .element: class="fragment "  -->


### Niet-functionele eisen
> Dankzij de layout kunnen winkelmedewerkers binnen drie klikken een nieuwe bestelling plaatsen (gebruiksvriendelijkheid)


### Niet-functionele eisen
> Er is documentatie beschikbaar die beschrijft hoe ontwikkelaars data van onze server kunnen opvragen via de API (ondersteuning)


### Niet-functionele eisen
> De ontwerpstijl voor de applicatie is flat design (gebruiksvriendelijkheid) 


### Niet-functionele eisen
> Er mag geen verlies in snelheid optreden binnen de range van 0 tot 1000 gelijktijdige gebruikers (prestatie)


### Niet-functionele eisen
> Er wordt gebruik gemaakt van JSON Web Tokens voor authenticatie. (veiligheid)



> Identificeer de eisen door bijvoorbeeld nummering toe te voegen



### Recap
[Flinga (FG2BAJP)](https://flinga.fi/s/FG2BAJP)



# Customer Stories
> Als een < actor > wil ik < actie > zodat ik < business waarde >


# Customer Stories
>  "Als zorgverlener, wil ik inzicht in de medicatiehistorie van de patiënt, zodat ik bij twijfel de nieuw voorgeschreven dosering gemakkelijk kan verifiëren."



# Klassen diagram in UML
Demo





# Les opdracht
* Clone de [De muziekvereniging](https://github.com/hogeschoolnovi/SD-BE-JP-Maven_and_Unittest-assignment)
* Maak de opdrachten en voor elke opdracht die je gemaakt hebt een commit met een nuttige beschrijving



# Bespreken les opdracht



# Huiswerk
* Maak de huiswerkopdracht [family tree](https://github.com/hogeschoolnovi/backend-java-family-tree)
* Volgende les gaan we het Spring Boot framework introduceren
* Lees hoofdstukken 1 t/m 5 van de EdHub Spring Boot
