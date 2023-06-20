# SoftwareSecurity

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

  Artemis Financial is a consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance. They wanted to add a file verification step to their web application to ensure secure communications. When the web application is used to transfer data, they will need a data verification step in the form of a checksum.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

  I provided the code that met their needs in a very direct and orderly fashion. In unnecessaryly complicated code comes vulnerabilities, it is better to keep things simple. Secure coding practices provide numerous benefits, including enhanced security, regulatory compliance, customer trust, cost savings, and protection against reputational and financial damage.

What part of the vulnerability assessment was challenging or helpful to you?

  The most challenging part of the project for me was in figuring out how to run a server application in Eclipse, because I had never done it before and the resources provided did not mention anything about how to accomplish that. It was an incredibly insightful problem to work through. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  We added a hash function to verify transferred data. Specifically, I added the SHA-256 hash function. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  We relied on the Maven dependency check. We ran one before refactoring the code to document what the application was vulnerable to before we touched it. Then after we refactored the code and got it running seccessfully, we ran the check again to make sure we didn't introduce any new vulnerabilities.
