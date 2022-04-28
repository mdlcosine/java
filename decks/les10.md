# Les 10
## Services, DTO en Intro Clean Code
### Start 18:00



## Agenda
* Vragen over de vorige les <!-- .element: class="fragment "  -->
* Recap Repositories en Databases <!-- .element: class="fragment "  -->
* Introductie Clean Code <!-- .element: class="fragment "  -->
* De Service laag <!-- .element: class="fragment "  -->
* DTO's - Wie Wat Hoe Waarom <!-- .element: class="fragment "  -->
* De Opdracht <!-- .element: class="fragment "  -->
* Afsluiting (+-20:50u) <!-- .element: class="fragment "  -->



# Poll en Evaluatie


# Uitslag Poll



### Wat weet je nog over de vorige les?
[Flinga (F2RKHN6)](https://flinga.fi/s/F2RKHN6)



### Intro Clean Code?
> Waarom Clean Code?

[Flinga (F2RKHN6)](https://flinga.fi/s/F2RKHN6)



# Service laag


## 3e en laatste laag binnen onze applicatie
1) Controller (Presentatie laag) <!-- .element: class="fragment "  -->
2) Service (Domein / Business laag) <!-- .element: class="fragment "  -->
3) Repository (Data laag) <!-- .element: class="fragment "  -->


## Hoe weet Spring er vanaf?
```java[1-4|1]
@Service
public class CustomerService {
    
}
```



# DTO - Data Transfer Object
>  Scheiding van de interne en externe applicatie structuur


```java
class User {
	long id;
	String userName;
	String firstName;
	String lastName;
	String email;
	String password;
	String socialSecurityNumber;
	List<Authority> authorities;
}
```
```java
class UserDto {
	public String username;
    public String password;
    public String email;
    public List<String> authorities;
}
```


## Validatie
```xml
<dependency>
    <groupId>org.hibernate.validator</groupId>
    <artifactId>hibernate-validator</artifactId>
</dependency>
```
```java[1-9|5]
@RestController("users")
public class UserController {
    @PostMapping
    public ResponseEntity<User> createUser(
        @Valid
        @RequestBody UserDTO userDTO){
        //....
    }
}
```
<!-- .element: class="fragment "  -->


# Demo - From The Start
1) Spring boot REST application
2) Hello World Get endpoint
3) Adding Hibernate (Object Relational Mapping)
4) User Entiteit
5) User Repository
6) Create User Endpoint (UserDTO en Validatie)
7) User Service
8) Exception Handling



# De Opdracht
* Clone de [Tech It Easy](https://github.com/hogeschoolnovi/backend-spring-boot-tech-it-easy-service-dto)
* Maak de opdrachten en voor elke opdracht die je gemaakt hebt een commit met een nuttige beschrijving
* Maak voor alles wat je maakt ook een Unit Test



# Afronding
* Maak [Tech It Easy](https://github.com/hogeschoolnovi/backend-spring-boot-tech-it-easy-service-dto)
* Volgende les gaan we het hebben over Relaties tussen Domain Models
* Lees hoofdstukken 7.6
