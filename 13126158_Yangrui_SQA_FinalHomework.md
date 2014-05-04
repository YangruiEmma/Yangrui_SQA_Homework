# How to ensure the quality of a software system ---China Unicom Electronic Sale System#
**YangRui  13126158**

I did Java development for China Unicom Electronic Sale System (ESS) as intern for 10 months. The Electronic Sale System is to process business for users of China Unicom. As developers, we almost get new business requirements every week. I didn’t participate in the project at beginning, but I will combine with what we have learned to analyze how to ensure the quality of the system. 

Software quality involves developers, customers, project managers, and other aspects. The focus of different people is various. For customers, the quality is in line with their requirements; for developers, the quality is in accordance with predetermined functions, procedures or completion development according to the specification; for the project managers, quality is to accomplish on the project schedule and at cost, and software must meet the user’s demand. In order to ensure software quality better, from my point of view, the following are important in Electronic Sale System.

**Make project plan and risk assessment**

Our customer is China Unicom, every process must be detailed and let customers know. For ensuring the quality of project we have to design the project plan firstly when we start the project. 

The project plan is to document planning assumptions and decisions facilitate communication among stakeholders, and document approved scope, cost, and schedule baselines. I think it will lead the project process.  SQA is not only to ensure the high quality of system. What is most important is to produce high quality products quickly and at the lowest possible cost. 

Except the project plan, we also need to do the risk assessment. Any risk maybe encounter during the project, so we have to identify the possibility of risks and think about the plan to avoid or solve these risks.

**Detailed and Correct Software Requirement**

As a software engineer, we know that how important a right requirement is. For ESS project, we publish version every two weeks, if we don’t analyze requirements correctly and the requirement is very important, it will be horrible and maybe the customer will be crazy.

**Effective Project Management and Suitable Development Process**

For the software industry, software product development process determines the ultimate quality of software products. In common sense, a mature software development process can ensure the excellence quality, correctly function, assessable cost and schedule, less defects. So, it needs control the software development activities effectively.

In the ESS project, the business requirements of customer almost added or changed every week, we have to accept new requirement and publish new version at least every two weeks. We know one principle of agile development is embracing change and it just accords with ESS project. Scrum is suitable for our project situation basically. When new requirements are coming, a new iteration starts and all group members will participate in requirement discussing. Then group break requirements (user story) into smaller tasks, estimate the hours that tasks are finished and give priorities for tasks. The members choose task themselves and report their performance of tasks every morning. The group has to do the code walkthrough and discuss the problems meet during the development at least one time a week. If one task cannot be finished on time, scrum master has to think a solution to solve the problem, for example let more people to do the task. The ultimate purpose is to ensure the version published on time.

**Testing (Coverage is important)**

I have mentioned that development model of ESS is scrum, the cycle is short. Testing is usually done at same time with development. Every kind of testing has to be done effectively. The system is used for China Unicom, if the business logic is right is very important, so we have to design more and more test cases to verify the business. Once we met a big error, because the tester missed a test case then one serious logic error is not found. However, the version was released next day, so the error is found on line. This mistake leaded all businesses cannot submit order. It really let customer crazy. So the test cases must be enough.

**Defect Classification and Analysis**

Although we have met errors, we should try to let it not happen again. Analyses of discovered defects and related information from quality assurance (QA) activities can help both developers and testers to detect and remove potential defects, and help other project personnel to improve the development process, to prevent injection of similar defects and to manage risk better by planning early for product support and services.


The above is my idea. The scope of SQA is wide. I just mentioned some important parts to ensure quality of China Unicom Electronic Sale System.  