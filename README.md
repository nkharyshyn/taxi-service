![Без імені](https://user-images.githubusercontent.com/116820316/227710619-fd5bbecc-57fe-431e-8585-235f33564569.png)
# 🚕TAXI SERVICE🚕
![Без імені 232](https://user-images.githubusercontent.com/116820316/227710680-96fc0cc1-0a01-442f-9994-86e3d356295c.png)
<br></br>
# ✍️Project description
This is a simple taxi service web application that supports registration, authentication and have basic CRUD operations. <br></br>
My project was implemented according to SOLID, DRY, KISS principles 
<br></br>
# ⚙️Features
* registration as a driver;
* authentication as a driver;
* add new manufacturer/driver/car;
* display all manufacturers/drivers/cars;
* delete manufacturer/driver/car;
* add driver to a certain car;
* display all cars for authenticated driver.
<br></br>
# 🧱Structure
My project has N-tier architecture:
* presentation tier is represented by jsp pages driven by HttpServlets;
* logic tier is represented by service layer with all business logic;
* data tier is represented by dao layer with all CRUD methods to work with DB.
<br></br>
# 🖥️Technologies
* JDK 11;
* Maven 4.0.0;
* MySQL 8.0.22;
* JDBC;
* Java Servlet API 4.0.1;
* JSP;
* HTML, CSS;
* JSTL;
* Tomcat 9.0.50.
<br></br>
# ❓How to launch?
* clone project from GitHub;
* install MySQL;
* create your own schema and tables using script from file `init_db`;
* configure connection to your DB in `ConnectionUtil`<br>
  by setting your own properties for fields: `URL`, `USERNAME`, `PASSWORD`, `JDBC_DRIVER`;
* `Edit configurations...` for Tomcat;
* run the project.
<br></br>
![Без імені](https://user-images.githubusercontent.com/116820316/227710695-0537c9d5-1054-4eb2-a41b-1e8404730276.png)
