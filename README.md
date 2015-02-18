# docker_tomcat7_postgresql9.3
Docker build for Tomcat 7 and PostgreSQL 9.3

Based on Tomcat7; Taken from Docker's PostgreSQL service exmaple with 2 exceptions:
   - No longer use peer authentication.
   - The PostgreSQL server can now only be accessed locally.
