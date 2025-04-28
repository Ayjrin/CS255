## Project Reflection - CS 255 System Analysis and Design

### 1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
DriverPass is a driving instruction company that needed an integrated, webbased platform for both online practice exams and in person lesson scheduling. DriverPass wanted a cloud system to handle user registrations, appointment booking, exam administration, progress tracking, and reporting—all with role based access control.

### 2. What did you do particularly well?
- **Requirements gathering:** I distilled the interview transcript into clear functional and nonfunctional requirements, ensuring nothing super critical was missed.
- **UML accuracy:** My usecase, activity, sequence, and class diagrams show system behaviors and data relationships.
- **Clarity and organization:** By using templates and bulleted lists, I kept the documents easy to review and iterate on.

### 3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would refine the technical requirements section in the system design document. Specifically, I’d add more detail around scalability (e.g., autoscaling rules, loadtesting metrics) and disaster recovery procedures, so future maintainers know  how to keep the system responsive and resilient as user volume grows.

### 4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
I mapped each stakeholder request like flexible package management or secure password resets—to concrete system features and corresponding UML flows. Prioritizing user needs ensures the final product solves real problems, delights end users, and avoids wasted effort building unused functionality.

### 5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
My usual process is:
1. **Stakeholder interviews & documentation** – capture goals, pain points, and constraints
2. **Requirement classification** – split into functional, nonfunctional, and technical requirements
3. **Give it a go** – develop a proof of concept that demonstrates either the correct or incorrect path, recieve feedback, clarify the technical sides of the problem on my own and increase understanding of the domain
4. **Modeling with UML** – visualize use cases, workflows, object interactions, and data structures
5. **Iterative feedback loops** – present diagrams to stakeholders for validation
6. **Scalability & security review** – ensure architecture can grow and protect sensitive data


