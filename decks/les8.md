# Les 8
## REST en Spring Boot
### Start 18:00



## Agenda
* Opfrissessie van morgen <!-- .element: class="fragment "  -->
* Vragen over de vorige les <!-- .element: class="fragment "  -->
* Recap Requirements <!-- .element: class="fragment "  -->
* Recap Klassendiagram <!-- .element: class="fragment "  -->
* Wat zijn Webservices <!-- .element: class="fragment "  -->
* Nieuwe tooling: Postman <!-- .element: class="fragment "  -->
* Wie wat waarom REST <!-- .element: class="fragment "  -->
* Spring Boot <!-- .element: class="fragment "  -->
* Hoe past REST in Spring Boot <!-- .element: class="fragment "  -->
* De Opdracht <!-- .element: class="fragment "  -->
* Afsluiting (+-20:50u) <!-- .element: class="fragment "  -->


# Poll en Evaluatie


# Uitslag Poll



### Wat weet je nog over de vorige les?
[Flinga (FG2BAjP)](https://flinga.fi/s/FG2BAJP)



### Wat zijn webservices?
![image](images/WebServices.png)


# Tooling
### Demo Postman
[Pokemon API](https://pokeapi.co/docs/v2)



# RESTfull


> REpresentational State Transfer



### RESTfull principes
* Stateless <!-- .element: class="fragment "  -->
* Client-Server <!-- .element: class="fragment "  -->
* Uniform Interface <!-- .element: class="fragment "  -->
* Cacheble <!-- .element: class="fragment "  -->
* Layered System <!-- .element: class="fragment "  -->
* Code on command <!-- .element: class="fragment "  -->



### HTTP
![http](images/rest.png)


### HTTP request
* Een URL adres van de server <!-- .element: class="fragment "  -->
* Een HTTP methode <!-- .element: class="fragment "  -->
* Een header <!-- .element: class="fragment "  -->
* Een body <!-- .element: class="fragment "  -->


### HTTP response
* Een HTTP status code <!-- .element: class="fragment "  -->
* Een header <!-- .element: class="fragment "  -->
* Een body <!-- .element: class="fragment "  -->


### Statuscode ranges
![statuscode](images/httpstatuscode.png)



### CRUD
![CRUD](images/crud.png)



# Spring Boot
> Convention over Configuration


### Architectuur
![spring boot architectuur](images/spring-boot-architectuur.png)



# Demo Spring Boot
note:
@RestController
@RequestMapping("/users")
public class UserController {

    @GetMapping
    public ResponseEntity<List<String>> getAllUsers() {
        return ResponseEntity.ok(List.of("Martijn", "Johan"));
    }

    @GetMapping("/{id}")
    public ResponseEntity<String> getUserById(@PathVariable String id) {
        if (id.equals("1")) {
            return ResponseEntity.ok("Johan");
        } else if (id.equals("2")) {
            return ResponseEntity.ok("Martijn");
        } else {
            return ResponseEntity.notFound().build();
        }

    }
}



# De Opdracht
* Clone de [Tech It Easy](https://github.com/hogeschoolnovi/backend-spring-boot-tech-it-easy-controller)
* Maak de opdrachten en voor elke opdracht die je gemaakt hebt een commit met een nuttige beschrijving
* Maak voor alles wat je maakt ook een Unit Test



# Afronding
* Maak [Tech It Easy](https://github.com/hogeschoolnovi/backend-spring-boot-tech-it-easy-controller)
* Volgende les gaan we het hebben over Domain Models, Repository + Databases
* Lees hoofdstukken 7 en 9 van de EdHub Spring Boot
* Lees de hele cursus Database Development (2020) 
