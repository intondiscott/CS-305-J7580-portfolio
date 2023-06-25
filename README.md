<div><h1 align="center">📚 CS-305-J7580-portfolio 📚</h1>
<img src="https://learn.snhu.edu/content/enforced/1311887-CS-305-J7580-OL-TRAD-UG.23EW5/course_documents/Module%20Eight%20Journal%20Image.jpg?_&d2lSessionVal=jMkir4dPI7k37EvvXSD8n8HWR&ou=1311887" /> </div>

<!-- Answering all the questions about my project-->
<div>
  <h2>Q: Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</h2>
  <p>A: 🐾 The client was looking to incorporate a more secure system on their existing platform</p>
  <h2>Q: What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?</h2>
  <p>A: 🥷 I spotted false positives in some dependencies where the server was giving warnings about dependencies that are for a different version. I suppressed them in the Pom file. In the current implementation of Artemis Financial, there were security issues that attackers would be able to inject SQL into the database, and I was able to spot that and took appropriate action to mitigate an attack.</p>
  <h2>Q: What about the process of working through the vulnerability assessment did you find challenging or helpful?</h2>
  <p>A: ♟️ The dependency checker helped so much in spotting issues and what is needed to fix them. The other way would be looking online for what is written about each dependency and issue which can take forever at scale.</p>
  <h2>Q: How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?</h2>
  <p>A: 🐛 I would definitely use a dependency checker as it gives useful information that is gathered from accredited companies. This gives me insight as to if my code is secure and free of bugs.</p>
  <h2>Q: How did you ensure the code and software application was functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</h2>
  <p>A: 🩹 I would keep an old copy of the dependency checker and compare it with an updated check after refactorization.</p>
  <h2>Q: What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?</h2>
  <p>A: 👨‍💻 I unlocked my inner google-Fu, looked at the stacked overflow, and redit to see if others had the same issues e.g., why my server wouldn't spin up, and found that I needed to update my properties file.</p>
  <h2>Q: Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this assignment might you want to showcase to a future employer?</h2>
  <p>A: ⚙️ I would like to showcase my ability onto working with secure sockets.</p>
</div>
