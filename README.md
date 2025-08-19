# CS-305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that needed its software assessed for vulnerabilities. The client wanted to make sure that sensitive customer data was protected, that communication between clients and servers was secure, and that the application complied with industry standards for software security. The main issue they asked me to address was identifying security weaknesses in their code and recommending ways to mitigate them.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I did well at identifying weak spots in communication and data handling. I was able to strengthen the application with AES encryption, SHA-256 hashing, and secure HTTPS connections. Secure coding is important because it prevents unauthorized access, protects customer information, and ensures that the application can be trusted. Strong software security also builds customer confidence, helps the company meet regulatory requirements, and reduces the financial and reputational risks of a breach.

Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was generating and configuring certificates since that required careful attention to detail. The most helpful part was secondary testing because it confirmed that my changes did not break functionality and that the security improvements worked as intended.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by applying AES-256 encryption, adding SHA-256 hashing for data integrity, enabling HTTPS, and generating SSL certificates for secure communication. I also used dependency-check tools to confirm there were no hidden issues in the code. In the future, I would use both static and dynamic analysis tools along with manual code reviews to identify vulnerabilities and choose the best mitigation techniques.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I tested the application by running the refactored code to make sure it executed without errors and functioned as expected. I also validated that secure communication was established in the browser and verified checksums with SHA-256. Finally, I ran the dependency-check report again to confirm that no new vulnerabilities were introduced after refactoring.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used AES-256, SHA-256, SSL certificate generation, keytool for managing certificates, and OWASP dependency-check for testing. I also practiced secure coding techniques like input validation and avoiding hardcoded credentials. These tools and practices are valuable for any future projects that involve sensitive data or secure communication.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I could show the refactored code, the secure communications setup, and the dependency-check results. Together these demonstrate my ability to implement encryption, configure certificates, and follow industry-standard best practices while still keeping the application functional and reliable.
