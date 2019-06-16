# client-spring-angular
Project "Client" in Spring Boot, Angular, MySQL


This project is a compilation of several technologies to create a full-stack project using Spring Boot, Angular and MySQL.


Angular Basic Components
- NavBar. https://getbootstrap.com/docs/4.3/components/navbar/
- Body
- Footer


Boostrap order
- bootstrap.min.css (head)
- jquery.* (body)
- popper.min.js (body)
- bootstrap.min.js (body)

Step 1. Creating the header component
- ng g c header
- Include the NavBar from Bootstrap.

Step 2. Creating the footer component
- ng generate class footer

css:

.footer {
  position: absolute;
  bottom: 0px;
  height: 60px;
  width: 100%;
}




