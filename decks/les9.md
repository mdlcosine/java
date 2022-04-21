# Les 9
## Repositories en Databases
### Start 18:00



## Agenda
* Vragen over de vorige les <!-- .element: class="fragment "  -->
* Recap Services <!-- .element: class="fragment "  -->
* Nieuwe tooling: PGAdmin <!-- .element: class="fragment "  -->
* Demo Repository in Spring Boot <!-- .element: class="fragment "  -->
* De Opdracht <!-- .element: class="fragment "  -->
* Afsluiting (+-20:50u) <!-- .element: class="fragment "  -->


# Poll en Evaluatie


# Uitslag Poll



### Wat weet je nog over de vorige les?
[Flinga (FC7JTZE)](https://flinga.fi/s/FC7JTZE)



# Tooling
### Demo PGAdmin



# Demo Databases in Spring Boot
note:
<dependency>
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
<dependency>
<groupId>org.postgresql</groupId>
<artifactId>postgresql</artifactId>
<scope>runtime</scope>
</dependency>
spring.datasource.url=jdbc:postgresql://localhost:5432/demo
spring.datasource.username=springboot
spring.datasource.password=springboot
spring.datasource.driver-class-name=org.postgresql.Driver
spring.jpa.hibernate.ddl-auto=create-drop
spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect




# De Opdracht
* Clone de [Tech It Easy](hhttps://github.com/hogeschoolnovi/backend-database-tech-it-easy)
* Maak de opdrachten en voor elke opdracht die je gemaakt hebt een commit met een nuttige beschrijving
* Maak voor alles wat je maakt ook een Unit Test



# Afronding
* Maak [Tech It Easy](hhttps://github.com/hogeschoolnovi/backend-database-tech-it-easy)
* Volgende les gaan we het hebben over Service, DTO’s en SOLID, Clean code
* Lees hoofdstukken 6 + 8
* Lees hoofdstuk 5 van de cursus Clean Code
