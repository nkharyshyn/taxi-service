![taxi1](https://github.com/nkharyshyn/images/blob/main/%D0%91%D0%B5%D0%B7%20%D1%96%D0%BC%D0%B5%D0%BD%D1%96.png)
# _🚕TAXI SERVICE🚕_
![taxi2](https://github.com/nkharyshyn/images/blob/main/%D0%91%D0%B5%D0%B7%20%D1%96%D0%BC%D0%B5%D0%BD%D1%96%20232.png)
<br></br>
# _✍️Project description_
This is a simple taxi service web application that supports registration, authentication and have basic CRUD operations. <br></br>
My project was implemented according to SOLID, DRY, KISS principles 
<br></br>
# _⚙️Features_
* registration as a driver;
* authentication as a driver;
* add new manufacturer/driver/car;
* display all manufacturers/drivers/cars;
* delete manufacturer/driver/car;
* add driver to a certain car;
* display all cars for authenticated driver.
<br></br>
# _🧱Structure_
My project has N-tier architecture:
* presentation tier is represented by jsp pages driven by HttpServlets;
* logic tier is represented by service layer with all business logic;
* data tier is represented by dao layer with all CRUD methods to work with DB.
<br></br>
# _🖥️Technologies_
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
# _❓How to launch?_
* clone project from GitHub;
* install MySQL;
* create your own schema and tables using script from file `init_db`;
* configure connection to your DB in `ConnectionUtil`<br>
  by setting your own properties for fields: `URL`, `USERNAME`, `PASSWORD`, `JDBC_DRIVER`;
* `Edit configurations...` for Tomcat;
* run the project.
<br></br>
![taxi3](https://github.com/nkharyshyn/images/blob/main/%D0%91%D0%B5%D0%B7%20%D1%96%D0%BC%D0%B5%D0%BD%D1%96.png)
