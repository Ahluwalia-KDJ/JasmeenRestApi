# JasmeenRestApi
REST API using springboot framework
Softwares used:
1. Eclipse IDE for Enterprise Java Developers. (Version: 2019-06 (4.12.0))
2. Spring Boot v2.1.8.RELEASE
3. tomcat-jsp-9.0.24 (Included in dependencies)
4. In-memory database H2

How to run Project:
1. Download entire project and unzip jasmeenAPI.zip
2. Import project into an IDE (preferably Eclipse)
3. Click on imported project and choose run as Java Application.
4. Choose 'JasmeenApiApplication - com.jasmeen.jasmeenAPI' from the list populated by run as wizard.
5. Port 8080 must be vacant.
6. In web browser enter the URL http://localhost:8080/ to start using the REST API. (Homepage)
7. Since all dependencies are included the project can simply be run after pulling from GitHub.

Resources are located at following URLs:
1. Products catalog at http://localhost:8080/products
2. Cart at http://localhost:8080/cart
3. All product details http://localhost:8080/products/details
4. Individual product details http://localhost:8080/products/details/{prodid}
   (where {prodid} is the particular product ID)

Note: The API can also be accessed via Clients like Postman etc. to check REST API functionalities

