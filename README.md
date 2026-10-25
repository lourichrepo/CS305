# CS 305 – Software Security

## Artemis Financial: Practices for Secure Software 

For this project, I worked with Artemis Financial, a financial consulting company that wanted to improve the security of its software application. The company needed to protect sensitive financial information and reduce security risks. My job was to identify vulnerabilities and make improvements to the application. 

### 1. Identifying Security Vulnerabilities 

I think I did well identifying potential security problems and learning how to use tools like OWASP Dependency-Check. Secure coding is important because even the smallest vulnerabilities can put sensitive information at risk. For a financial company, strong security can help prevent financial losses and protect customer trust. 

### 2. Challenges and Helpful Experiences 

One of the more challenging parts was working with Dependency-Check and understanding the vulnerabilities it found. Some results were false positives, while others were legitimate issues that still needed attention. Learning how to review these findings instead of assuming every warning was accurate was helpful. 

### 3. Adding Layers of Security 

I added SHA-256 hashing to generate a checksum, created a self-signed certificate using Java Keytool, and configured the application to use HTTPS. These changes provided additional security measures for the application. In the future, I would use tools like OWASP Dependency-Check, along with code reviews and testing, to identify vulnerabilities and determine which security improvements are needed. 

### 4. Testing the Application 

After making changes to the code, I ran the application to make sure it still worked correctly. I tested the checksum and used Dependency-Check to scan for known vulnerabilities. The application was functional, although some vulnerabilities in its older dependencies still needed to be addressed. 

### 5. Useful Tools and Resources 

Some of the tools I found useful were Java Keytool, Maven, and OWASP Dependency-Check. I also learned more about encryption, hashing, and HTTPS. These tools and concepts will be helpful in future projects where software security is a focus. 

### 6. What I Can Show Future Employers 

This project demonstrates my ability to review an application for security vulnerabilities, make improvements to its code, and test the results. It also shows that I can document my work and identify security problems that still need attention. These are skills I can continue building as I work toward becoming a software developer. 


[View My Completed Security Report](CS_305_7-1_Project_2_Artemis_Report.pdf)
