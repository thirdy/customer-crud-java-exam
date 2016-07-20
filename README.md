# customer-crud-java-exam
Java based Customer CRUD RESTful application

- Time Start: 10:42 AM
- Time End: 
- Duration:

### Framework choice:

Researching for choices for Java-based frameworks that support RESTful architechture came up with the following:

 1. Spring Boot + Vaadin - Spring Boot is a solid choice and Vaadin is a good choice if you want to write the UI in Java just like Apache Wicket or GWT.
 1. JHipster - A lot of stars in Github. Looks like a very stable project.
  - License: Apache 2.0
 2. lightadmin.org - Looks like a solid option if you are already familliar with the technologies it uses. However it does not that it's a PoC.
  - License: Apache 2.0
  - Last commit: 2 months ago
  - Uses Apache Tiles along with JSTL
  - Spring MVC
  - Spring Data / Hibernate
  - Gitub: https://github.com/la-team/light-admin
 1. CUBA.platform - The free license is limited; there are better options than this.

I choose option 1 as Spring is a mature framework. Vaadin is a good choice as dealing with front-end javascript frameworks can be difficult if you do not know all the do's and dont's. I've also tried out Vaadin a few years ago.

For build tool, Maven is a good choice. I heard Gradle is good as well, however, for now, Maven will do the job.


