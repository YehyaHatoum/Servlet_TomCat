# Servlet Application with Apache Tomcat

## Description

This project implements a simple servlet-based web application using Apache Tomcat. The application consists of a servlet that generates a personalized greeting and an HTML page with a link to the servlet. The servlet is compiled using Java 17 and deployed on the Apache Tomcat server.

## Project Steps

1. **Download and Install Apache Tomcat:**
    - Download and install Apache Tomcat, a popular open-source servlet container, on your local machine.

2. **Implement Servlet:**
    - Developed a servlet named `HelloServlet` that generates a personalized greeting. The servlet responds to HTTP GET requests and generates HTML content with the greeting.

3. **Compile Servlet:**
    - Compiled the `HelloServlet.java` file using Java 17 to generate the corresponding `HelloServlet.class` file.

4. **Deploy Servlet to Apache Tomcat:**
    - Deployed the compiled servlet (`HelloServlet.class`) to the appropriate directory within the Apache Tomcat webapps folder. The servlet class was placed in the `WEB-INF/classes` directory of the web application.

5. **Create HTML Page with Link to Servlet:**
    - Created an HTML page named `index.html` with a link to the servlet. The HTML page is served by Apache Tomcat and contains an anchor element (`<a>`) linking to the servlet URL.

6. **Test Interaction:**
    - Tested the interaction between the HTML page and servlet by accessing the HTML page through a web browser. Clicking the link in the HTML page should invoke the servlet, displaying the personalized greeting.

#### Note: Please refer to the report submitted on Moodle for screenshots and additional details.