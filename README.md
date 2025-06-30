# CS305
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

    Artemis Financial is a consulting firm that provides customized financial planning services, including savings, retirement, investment, and insurance solutions. The company is aiming to modernize its operations by enhancing the security of its public web application. To achieve this, they’ve requested the implementation of a file verification process using checksums to ensure data integrity during transfers. This added layer of security is intended to protect sensitive client information and support Artemis Financial’s commitment to using up-to-date, effective software security measures.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

    When I discovered security weaknesses in the client’s software, I addressed them by implementing secure coding practices such as input validation, robust encryption methods, and adding a checksum-based file verification system. These measures helped eliminate vulnerabilities while preserving the system’s integrity and performance. Writing secure code is critical because it helps prevent attacks, safeguards sensitive information, and lowers the chances of data breaches that could negatively impact both users and the organization. Secure coding builds a strong foundation of trust with clients and ensures compliance with relevant industry standards and regulations.

Which part of the vulnerability assessment was challenging or helpful to you?

    The most difficult aspect of the vulnerability assessment was uncovering hidden security issues that weren’t immediately apparent (resolving 1 CVE can sometimes introduce another flaw - it's important to research all CVE's applicably). On the other hand, as I'm also a bit newer to Eclipse and Maven projects I found the assessment helpful because it provided a clear roadmap for improving the application’s security posture. It highlighted exactly where to focus efforts — like implementing strong cryptographic checksums and enforcing secure transport — which made it easier to prioritize tasks. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

    I increased layers of security by implementing multiple complementary measures: adding a checksum-based file verification to ensure data integrity, enforcing secure communication through TLS encryption, validating checkSum results and incorporating multiple acceptable security algorithms. This defensive approach helps protect the system at various points, reducing the risk that a single vulnerability could be exploited.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

    To make sure the code and software were both functional and secure, I used static analysis tools to detect common security flaws, such as injection risks or improper data handling. After refactoring, I ensured no new vulnerabilities were introduced by running security-focused tests (vulnerability reports). I also checked the versions of third-party dependencies that were flagged originally to avoid known vulnerabilities and confirmed that the code adhered to secure coding standards like those from OWASP.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

    Through the development of this project, I really didn't use any specific tools other than self-researching through errors or exceptions I encountered. I would say that by having a security - forward mindset in programming that alone helped me tackle some of the roadblocks that I ran into. One takeaway I can say is that defensive programming will always a key feather in any developer's hat. It's important to perform those validations before executing dependent blocks of code. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

    I would just show the final project as it showcased a lot of different security levels to programming, and it also showed a good comprehension of dealing with vulnerabilities in a code base!