# CS_305_Artifact

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was the client, a consulting company that provides individualized financial plans for its customers, including savings, retirement, investments, and insurance. The company wanted to modernize its operations and address security concerns by identifying and mitigating vulnerabilities in its RESTful web-based application to protect sensitive financial data from external threats.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I successfully assessed the software’s security vulnerabilities and provided solutions to mitigate them. I also documented ways to avoid similar vulnerabilities in the future so the company could take preventative action. Secure coding is important because security failures can lead to major financial loss, privacy breaches, and exposure of sensitive data. Strong software security improves a company’s overall well-being by preventing attacks such as SQL injection, protecting customer information, and maintaining trust.

# Which part of the vulnerability assessment was challenging or helpful to you?

One challenging part of the vulnerability assessment was reviewing vulnerabilities that contained more than 30 CVEs. The technical language initially felt overwhelming, but breaking the vulnerabilities down into simpler terms made them easier to understand and assess. The vulnerability assessment diagram was especially helpful because it provided structure and guidance throughout the assessment process.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by updating libraries to their latest stable versions, applying secure coding best practices, and addressing identified security issues in the code. I also ensured the application was protected against SQL injection attacks. In the future, I would use dependency-check reports, vulnerability scanning tools, and mitigation frameworks to assess risks and determine appropriate security solutions.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I ensured the code and software application remained functional and secure by following established secure coding best practices during development and refactoring. This included making careful code changes, avoiding insecure patterns, validating inputs, and ensuring dependencies were properly managed. I verified that the application continued to run as expected after each change. After refactoring the code, I ran Maven dependency-check reports to confirm that no new vulnerabilities were introduced and that existing security issues were resolved.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Useful tools and practices included Maven, dependency-check reports, secure coding standards, and manual code reviews. These tools helped me systematically identify and assess security vulnerabilities, ensuring the application was reliable. One valuable skill I learned was how to find vulnerabilities manually by reviewing code, which improved my ability to recognize potential risks that automated tools might miss. I also learned that automated tools can produce false positives, so I can watch out for those. This skill and awareness will be a valuable asset in future assignments and real-world projects, helping me write more secure and dependable software.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I can show future employers that I am able to inspect software for security vulnerabilities and suggest appropriate mitigation and prevention techniques. This work demonstrates my understanding of how important software security is and why code must be written securely. It shows that I consider risks such as SQL injection and other attacks during development and understand that coding errors and a lack of security practices can lead to serious security issues and losses.
