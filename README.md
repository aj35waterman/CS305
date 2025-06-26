# CS305
Artemis Financial needed help securing their RESTful application. They wanted to make sure the sensitive data being shared between client and server was 
protected and not vulnerable to attacks. I focused on improving the security by adding a SHA-256 hash function, setting up HTTPS with a self-signed certificate, 
and making sure the application used updated, secure versions of Spring Boot and Tomcat. I followed industry standards to reduce the risk of threats and made sure 
data wasn’t exposed in plain text. I think I did well identifying vulnerabilities and fixing them with proper tools and methods. One of the more helpful parts was 
running OWASP Dependency-Check, which scanned my code for any known issues in the libraries I used. I also wrapped risky code in try-catch blocks and tested the app 
to make sure it still worked after refactoring. If I do this again, I’d add even more logging and automate the testing steps. I’ll definitely keep using built-in security 
tools, hashing techniques, and static testing in future projects. This assignment is something I’d be proud to show employers as proof of my ability to write secure and 
functional code.
