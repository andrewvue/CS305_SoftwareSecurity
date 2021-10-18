# CS305_SoftwareSecurity
Software Security course SNHU CS305 21EW21

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The Client Artemis Financial is a financial institution that is inquiring about the latest software security practices and required their communication lines to be secured. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe I did well to find their security vulnerabilities in their communication not being secured through encryption, they had old and outdated dependencies that required updates. They I addressed these issues by making the necessary changes and recommendations for the client, but at the end of the day the client will have to make the decision to make such changes and suggestions.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

What I found challenging when working thorugh the vulnerability assessment was predicting the use cases and scope of the client's project. This client is not currently engaging in international transactions, but it is important to address the potential for their business changes in the future. To address this further research would be needed to address other international security practices, regulations and standards.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The first step was to run dependency checks and then I addressed any other high level security risks such as non secured sites like HTTP. The next step was to incorporate encryption for secure communication.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After ensuring that my code was error free I ran the project in a local environment to make sure my output was what I intended. The next step was to create self signed certificates to ensure that the site will be reached via https (secure). The next step is to check the depenencies again to ensure that I addressed all of the previous issues present before the refactor.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Creating SSL certificates was something that I found very useful in testing my code in a local environment. I will be using this method moving forward.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would share my final project in this course because it is a culmination of all that I learned from this course. It shows my understanding of current (at the time of the assignment) best security practices and using said best practices to complete my project.
