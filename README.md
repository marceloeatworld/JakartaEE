# Example Project Jakarta EE 10 with IntelliJ Community and Tomcat 10.1.10

This example project shows you how to set up a Jakarta EE project in IntelliJ Community and how to import the Jakarta servlet library into a Java class. It also guides you on setting up Tomcat 10.1.10 in IntelliJ Community.

## Steps

1. Create a new project in IntelliJ Community.
   
   ![Création du projet dans IntelliJ Community](1.png)

2. Import the Jakarta servlet library.
     ` import jakarta.servlet.*;
       import jakarta.servlet.http.*;
       import jakarta.servlet.annotation.*;  ` 
   
   ![Importation de Servlet Jakarta dans une classe Java](2.png)
   
 4. Import the TSTL library.
    
   ` import jakarta.faces.*;`
   
 5. Importez la bibliothèque TSTL.
    
  - pom.xml:
    
     `   <dependency>
            <groupId>org.glassfish.web</groupId>
            <artifactId>jakarta.servlet.jsp.jstl</artifactId>
            <version>3.0.1</version>
        </dependency>`
    
   - and in the jsp view:
     
   `  <%@ taglib prefix="c" uri="jakarta.tags.core" %>`
  

4. Set up Tomcat in IntelliJ Community.
   
   ![Configuration de Tomcat dans IntelliJ Community](tomcat.png)

## Download

You can download the complete example project in ZIP format by clicking on the following link: 
[JakartaEE_Exemple.zip](JakartaEE_Exemple.zip)

## Note

This example project is provided for illustration and demonstration purposes only. It is designed to help you understand the basics of setting up Jakarta EE with IntelliJ Community and Tomcat.

Feel free to explore the source code and use it as a starting point for your own Jakarta EE projects!

