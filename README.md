# client-spring-angular
Project "Client" in Spring Boot, Angular, MySQL


This project is a compilation of several technologies to create a full-stack project using Spring Boot, Angular and MySQL.


Angular Basic Components
- NavBar. https://getbootstrap.com/docs/4.3/components/navbar/
- Body
- Footer


Boostrap order
- Website: https://getbootstrap.com/docs/4.3/getting-started/download/
- bootstrap.min.css (head)
- jquery.* (body)
- popper.min.js (body)
- bootstrap.min.js (body)

### Step 1. Create 'header' component
- Generate the component using: `ng g c header`
- Include the NavBar from Bootstrap.

### Step 2. Create 'footer' component
- Generate the component using: `ng generate component footer`

footer.component.css
``` css
.footer {
  position: absolute;
  bottom: 0px;
  height: 60px;
  width: 100%;
}
```

### Step 3. Create 'listOfItems' component
Example of the use of the Structural directive `*ngFor`.
- Generate the component using: `ng g c listOfItems`
- `listOfCourses: string[] = ['Typescript', 'Java', 'JS', 'HTML'];`
``` html
<ul class="list-group">
  <li class="list-group-item" ngFor="let course of listOfCourses"> {{course}} </li>
<ul>  
```




