# CS-305-Secure-Software-Development
SNHU CS 305 portfolio showcasing secure coding practices, vulnerability assessments, encryption, and software security improvements for Artemis Financial.

## CS 305 Portfolio Reflection

### 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial consulting company that develops individualized financial plans for customers, including savings, retirement, investments, and insurance. The company needed to improve the security of its software application to protect sensitive customer information. My responsibility was to identify potential security vulnerabilities and recommend ways to reduce the risks. This included reviewing the application's code, examining its dependencies, and considering how to protect information from unauthorized access.

### 2. What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

I believe I did well identifying vulnerabilities through manual code review and static testing. During my review, I identified issues such as hard-coded database credentials, missing input validation, improper error handling, and poor encapsulation. I also used OWASP Dependency-Check to identify 13 vulnerable dependencies in the application. Secure coding is important because it helps prevent unauthorized access, data breaches, and application failures. For a financial company, software security also helps protect customer trust, maintain reliable services, and reduce financial and reputational risks.

### 3. Which part of the vulnerability assessment was challenging or helpful to you?

One of the most challenging parts was understanding the results from OWASP Dependency-Check. The report identified several vulnerabilities, and I had to review the findings to understand their potential impact on the application. I also had to determine which security concerns were related to the source code and which involved outdated dependencies. Although this process was challenging, it helped me understand how security vulnerabilities are identified and why developers must regularly review their applications.

### 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I identified several ways to strengthen the application's security, including input validation, improved error handling, better encapsulation, and removing hard-coded credentials. I also recommended updating vulnerable libraries and restricting unnecessary access. These recommendations would help provide multiple layers of protection instead of relying on one security measure. In the future, I would continue using tools such as OWASP Dependency-Check, manual code reviews, and security testing to identify vulnerabilities. I would evaluate the severity of each issue and its potential impact before selecting an appropriate mitigation technique.

### 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

For Project One, I reviewed the application's source code and used OWASP Dependency-Check to identify potential security vulnerabilities. My assessment focused on identifying risks and recommending improvements rather than implementing all of the fixes. In my mitigation plan, I recommended updating vulnerable dependencies, improving input validation, and strengthening error handling. I also recommended running Dependency-Check again after changes are made and continuing manual code reviews. These steps would help verify that the application remains functional and that security improvements do not introduce additional vulnerabilities.

### 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some of the most helpful resources were OWASP Dependency-Check, Maven, Java, and secure coding guidelines. I learned how to review dependency reports, identify known vulnerabilities, and understand the importance of keeping software libraries updated. I also gained a better understanding of input validation, encapsulation, secure error handling, and protecting sensitive information. These tools and practices will be useful in future programming assignments and software development projects.

### 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show future employers my Artemis Financial Vulnerability Assessment Report because it demonstrates my ability to review software for security risks and recommend improvements. The report includes my manual code review findings, static testing results, and mitigation recommendations. It also demonstrates my understanding of secure coding practices and the importance of protecting sensitive customer information. This project helped me develop skills that I can continue improving as I work toward becoming a software developer.
