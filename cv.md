# KARMYZOV SERGEY
## Junior Frontend Developer
### Contact information:
* phone :   +375296543271
* Email:     skarmyzov@gmail.com
* Skype:    snkarmyzov
* Linkedin: http://surl.li/ccmqy
### Education
10/2021-04/2022 -- IT-Academy (Educational Center of HTP)
Course: Technologies for developing enterprise-solutions in Java
Description: Hibernate, Spring, Maven, Tomcat, GitHub

### Skills and Proficiency:
* Web technologies: HTML, CSS
J2EE Technologies: Servlets, JSP, JDBC, JMS
* Java Frameworks: Hibernate, Spring (Core, MVC, Security, Data, Boot)
* AWS: Amazon Web Services
* Application Servers: Tomcat
* Database Servers: MySQL, PostgreSQL, PGAdmin
* Software project management tool:Maven
* Operating Systems: Windows
* CVS: Git
* Development IDEs and editor code: IntellijIDEA 
Docker, Amazon WebService

### Code example: 
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.
``` function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
### Languages:
* English - Intermediate/Upper-intermediate
* Belarussian - native
* Russian - native
