# cs-305
Projects completed during course work for CS 305 Software Security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
In this assignment, I was tasked with assessing the vulnerabilities in code provided by Artemis Financial. The client uses a cloud or server-based data processing program. The client wanted me to assess vulnerabilities to identify how the program may be attacked. They also wanted me to develop a plan for mitigating the vulnerabilities. In this assignment, I looked at the code for any obvious issues such as not utilizing input validation. I then ran a maven-based extension that would assess the specific dependencies of the program and inform me of any known vulnerabilities and what has been done to mitigate the vulnerabilities. In the assessment, I found that many of the vulnerabilities were patched out by the developers who recommended updating the dependency to the latest version. I also found a few cases where specific dependencies created a vulnerability when used together. I found that these vulnerabilities were mostly patched out as well. In the cases that were not patched out I recommended that one dependency was chosen to be removed if at all possible. 

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I assessed all possible solutions and provided backup solutions if the client chose not to adhere to my initial solutions. Software security is essential because it protects the end user from malicious attacks that could be as harmless as lost time, as detrimental as leaked personal leading to identity theft, and anywhere in between. Having a reputation of being secure will make perspective clients more likely to choose your services over the competitors. 

Which part of the vulnerability assessment was challenging or helpful to you?
All of the sifting through of the known vulnerabilities. Most dependencies had multiple vulnerabilities. Most of the vulnerabilities were patched out and it was difficult keeping track of all of it. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I implemented a clean-up of code and reduced redundant lines. I also ensured that the code was as solid as possible before even looking at the dependencies. In the future, I would do things the same, but I would use the "false positive" filtering that I learned in Project 2 to make the process easier and less time-consuming. 


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I ran the code after refactoring it. This made me find errors in the code that I was tweaking and I was able to tweak and run the code until everything operated as smoothly as I needed it to. Along every step of the way I continued to use the maven dependency checker to see if anything had changed. Since I implemented no additional libraries no dependencies changed, but at least I continued to check to ensure that it stayed that way. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show future employers the code that I specifically wrote to implement input validation. I would also show screenshots of the before and after of the dependency checker. I would also attach the write-up that I did where I assessed each and every known vulnerability. The write-up is written in the same manner that I approach my work so it would give them an insight to how I would approach every task.
