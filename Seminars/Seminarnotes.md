Running log from the seminars. For each seminar:

• Write down the questions posed by the teacher
• Write down your log of searching for answers to the questions
• Full references of articles you read
– Brief summary from each article
• your synthesis!
• your answers to the questions.
• Summary of the discussion around the question.


————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————


Seminar One:


Q1: What is large scale requirements engineering?


Q2: What are the challenges in large scale requirements engineering?


Q3: What is the order of magnitude of the number of requirements we are
discussing?


Q4: Read up on and summarise [Strategic] Release Planning



Search Log
keyword: 1. large scale requirements engineering
         2. requirements engineering
         3. requirements engineering magnitude
         4. Release planning
database: BTH library



AR1: Ruhe, Gunther, and Moshood Omolade Saliu. "The art and science of software release planning." IEEE Software 22.6 (2005): 47-53.

SUM1: Release planning is used to select and assign the feature in product releases, which need to satisfy the factor of technique, resource, budget, risk and so on, a good release planning need to provide the best business value of development, satisfy the most important stakeholders and should be feasible in recent resource and should show the dependency of different features. So it's very difficult to make a release plan. There are two way to make the release plan, art way or science way.
Art way means, that the release plan is based on human ability and experience, in Agile, RP pay attention to the next duration, but with the increase of stakeholders and constraints, it will become unsuitable.
Science way means, using modeling to solve the problem, we need consider about feature, dependencies between features, resource constraints, the importance of stakeholders, the prioritization of features and also the objective function when we are modeling.
Author come out with a new way that using science way to create several solution and let the human judge which solution is best by experience. There will be three steps of this solution: modeling, exploration and consolidation.
1. Modeling: Plan the objectives and constraints of the problem, offer the stakeholder to voting it, and finally estimate the current resources.
2. Exploration: Author developed specialized integer programming algorithms find solution.
3. Consolidation: The manager decide the solution based on his experience and context of the problem, also the manager can simulate some problem in the real development to think about the solution.
But the practical effect of this approach still need some experiment to prove.


AR2: Svensson, Richard Berntsson, and Bjorn Regnell. "A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements." Requirements Engineering: Foundation for Software Quality (2015).

SUM2: In MDSD, almost all the method and approach used to make RP didn't consider about the Quality Requirements. But QUPER model consider about how to deal with the Quality Requirement. QUPER model is used to face the challenge about the fast software development technology, and also increase the importance of QR in the company in order to help company get more market competitiveness.
There are two main factor that promote the development of QUPER model. First is the direct need identified in industry. Second is that there are no suitable model found in the literature. And also when the company deal with the QR and the RP of QR, they cannot find a suitbale model to judge it. So there is a great need to promote the development of QUPER.
There are several steps of QUPER model.
step1. Identify the QR(consider about the features, market, hardware or competitor)
step2. Define a scale and unit for QR(used to judge the quality of QR)
step3. Identify  reference levels.(Point  estimates including a single ﬁgure, Interval  estimates including a [min,  max] interval,  Triangle  distribution  estimates including a three-tuple of [low bund, most probable,high bound])
step4. Elicit quality breakpoints(the lowest acceptable value on the market)
step5. Estimate cost barriers(to estimate the budget for each QR, author think two CB are better, one for software change, anthor for the new hardware or something influence the whole software architecture)
step6. Set candidate requirements
step7. Identify cost dependencies
And throught a case study of large company operating in a market-driven RE context using a product line approach.
And the conclution from the case study is that QUPER model is feasible and scalability in the company to improve the measurement of QR and also improve the company's market competitiveness.



AR3:Richard Berntsson Svensson, Thomas Olsson, Bjorn Regnell. "Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model.", 2008

SUM3: market-driven product development and release planning is becoming more important and common in recenct software company. But the project management is more difficult since the complex of software project. And a good release plan can directly influence the success of product. And to earn more in market and also to improve the company's competitiveness, the company should pay attention to the Quality requirement of the product. That's the reason that QUPER model is needed.
There are three steps of QUPER model of the two case of company:
Step 1: Problem definition. Focus on the different requirement of two case company to identify the cost-benefit model of quality requiremnt
Step 2: Model definition. Including three views: a benefit view, a cost view and a roadmap view.
        Benefit view: Used to indicate principal changes in the benefit level with respect to user experience and market value
        Cost view: Used to show ther cost barriers of non-linear relationship between cost and quality
        Roadmap view: Combine the benefit view and cost view to show the 
Step 3: Model validation. An evaluation of the model.
These steps are the generic, but for different case, there should be some change. For example, for the Sony Ericsson case. It can be change to following steps:
step 1: Define quality
step 2: Estimate current quality also the competing one
step 3: Estimate the breakpoint
step 4: Discuss the actual targets
And follow these steps and after the research on the Sony Ericsson case. Authors come out with a solution that:
1. The QUPER model is easy to use and learn, not very complex, and good for discussing between team members.
2. The QUPER model is useful and related when the company make high level decision of quality requirements in the release planning.
3. The main challenge of the QUPER model is that it's difficult to identify and specify the values for the differentiation and saturation breakpoints.



AR4:Regnell, Bjorn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: Results from an industrial process improvement programme." Requirements Engineering 3.2 (1998): 121-129.

SUM4: This article mainly describe a specific industrial RE process for packaged software, called REPEAT (Requirements Engineering ProcEss At Telelogic. REPEAT is a requirements enginnering process which can be used to manage the requirement in the release cycle.And REPEAT is focus on how to select the requirement and also the release planning. There are several actors in the REPEAT:
1. Requirement management group: Manage the requirement and make a decision on which requirement should be developed.
2. Issuer: A stakeholder which can submit a requirement to the Requirement management group.
3. Requirements team: The team which is response for analysing and specifying the requirements.
4. Construction team: The team which is response for designing and implementing the requirements.
5. Test team: The team which is response for verifying the requirement.
6. Expert: The person who evaluate the requirement in depth.
And there are five different phases of the REPEAT process:
1. Elicitation Phase: there will be two main things in this phase, collectiong and classification, collect the requirement make by an issuer and also submit it for storage in Requirement Database
2. Selection Phase: there will be two main things in this phase, first is to select the requirement which will be implemented in the current release, and second is to specify the selected requirements, and also validate the RQ document.
3. Change Management in parallel with Construction & Verification: the requirement management group should make a decision on changing the RD which is caused by some new requirement or high-priority requirment which may influence some development process such as construction and verification.
4. Conclution: make the conclution about requirement management in the current phase.
The conclution of this article is that REPEAT is a good way to manage the requirement, the REPEAT will inprovement the quality of product, the release precision, the effort estimation and specification of requirments. 

Q1: What is large scale requirements engineering?
A1: Large scale requirement engineering means using proven techniques to perform the analysis of large number of requirements and identify customers needs, help the analysts understand the problems, define all the external features of the target large and complex system. LSRE describes the system to be developed and its behavior characterisitics and related constraints through appropriate tools and notation. LSRE will froms the requirement document, and supports the evolving needs of the users. LSRE is an iterative process of defining requirements, documenting records, evolving requirements and finally decide the requirements on the basis of validation.

Q2: What are the challenges in large scale requirements engineering?
A2: 1. The complex system bring large number of requirements to deal with. 
    2. Lack of domain knowledge and the problems of the area always be inaccurate.
    3. Conflicts between multiple knowledge sources.
    4. The customers can't provide the things you want to know.
    5. New releases through the projects will come out with lots of problem.
    6. Too much requiremetns stored in the requiremens database.
    7. Distributed development will lead to lots of problem.
    8. Uncertainty and frequently change.
    9. Time pressure.
    10. Multiple levels of abstraction.

Q3: What is the order of magnitude of the number of requirements we are
discussing?
A3：Thousands or more, the system will be developed should be large and complex.

Q4: Read up on and summarise [Strategic] Release Planning
A4: Release planning is to make a plan for delivering the different requirement of the whole system which will be developed. All the stakeholders need to participated in the release planning to ensure the quality of plan in different aspect. And then the release planning will be used to make iteration plan for each individual iteration. There are several main target of release planning:
   1. Make the target of this release.
   2. Define the business background and competitive environment.
   3. Define the current status of product.
   4. Sort out the backlog of the product
   5. Locate and discuss issues.
And the output is the release plan, new items which should be put into release backlog, and advice to improve future plan.




• At Least, read and summarise:
– Ruhe “The art and science of release planning”, plus some more recent
works on the EVOLVE methods.
– R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation
of the guideline-supported QUPER model for elicitation of quality
requirements”, 21st International Working Conference on Requirements
Engineering: Foundation for Software Quality (REFSQ’15),
Essen, Germany, pp. 230-246, 2015.
– Berntsson Svensson & Olsson “Introducing support for release planning
of quality requirements –an industrial evaluation of the QUPER
model”
– Regnell et al. “A market-driven requirements engineering process:
results from an industrial process improvement programme”
