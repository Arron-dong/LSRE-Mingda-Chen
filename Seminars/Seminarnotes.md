Seminars One
———————————————————————————————————————————————————————

Q1: What is large scale requirements engineering?

A1: Large scale requirement engineering means using proven techniques to perform the analysis of large number of requirements and identify customers needs, help the analysts understand the problems, define all the external features of the target which is the large and complex system. LSRE describes the system to be developed and its behavior characterisitics and related constraints through appropriate tools and notation. LSRE will forms the requirement document, and supports the evolving needs of the users. LSRE is an iterative process of defining requirements, documenting records, evolving requirements and finally decide the requirements on the basis of validation.

———————————————————————————————————————————————————————

Q2: What are the challenges in large scale requirements engineering?

A2: 
    
    1. The complex system bring large number of requirements to deal with. 
    2. Lack of domain knowledge and the problems of the area always be inaccurate.
    3. The pressure of time.
    4. The customers can't provide the things you want to know.
    5. New releases through the projects will come out with lots of problem.
    6. Too much requirements stored in the requiremens database.
    7. Distributed development will lead to lots of problem.
    8. Uncertainty and frequently change.
    9. Conflicts between multiple knowledge sources
    10. Multiple stakeholders to consider about

———————————————————————————————————————————————————————

Q3: What is the order of magnitude of the number of requirements we are
discussing?

A3：Thousands or more, the system will be developed should be large and complex.

———————————————————————————————————————————————————————

Q4: Read up on and summarise [Strategic] Release Planning

A4: Release planning is to make a plan for delivering the different requirement of the whole system which will be developed. All the stakeholders need to participated in the release planning to ensure the quality of plan in different aspect. And then the release planning will be used to make iteration plan for each individual iteration. There are several main target of release planning:
   
      1. Make the target of this release.
      2. Define the business background and competitive environment.
      3. Define the current status of product.
      4. Sort out the backlog of the product
      5. Locate and discuss issues.
And the output is the release plan, new items which should be put into release backlog, and advice to improve future plan.

———————————————————————————————————————————————————————

Reference：

      1.Ruhe, Gunther, and Moshood Omolade Saliu. "The art and science of software release planning." IEEE Software 22.6 (2005): 47-53.
      2.Svensson, Richard Berntsson, and Bjorn Regnell. "A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements." Requirements Engineering: Foundation for Software Quality (2015).
      3.Richard Berntsson Svensson, Thomas Olsson, Bjorn Regnell. "Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model.", 2008
      4.Regnell, Bjorn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: Results from an industrial process improvement programme." Requirements Engineering 3.2 (1998): 121-129.
      5.Luiz Marcio Cysneiros, Eric Yu, " Requirement engineering for large-scale multi-agent systems", April 2003.
      6.An Ngo-The, Günther Ruhe, " Optimized Resource Allocation for Software Release Planning", IEEE Transactions on Software Engineering 2009 vol.35: 109-123.

———————————————————————————————————————————————————————

Search Log

keyword: 

      1. large scale requirements engineering
      2. requirements engineering
      3. requirements engineering magnitude       
      4. Release planning

database: BTH library

———————————————————————————————————————————————————————

AR1: Ruhe, Gunther, and Moshood Omolade Saliu. "The art and science of software release planning." IEEE Software 22.6 (2005): 47-53.

SUM1: Release planning is used to select and assign the feature in product releases, which need to satisfy the factor of technique, resource, budget, risk and so on, a good release planning need to provide the best business value of development, satisfy the most important stakeholders and should be feasible in recent resource and should show the dependency of different features. So it's very difficult to make a release plan. There are two way to make the release plan, art way or science way.
Art way means, that the release plan is based on human ability and experience, in Agile, RP pay attention to the next duration, but with the increase of stakeholders and constraints, it will become unsuitable.
Science way means, using modeling to solve the problem, we need consider about feature, dependencies between features, resource constraints, the importance of stakeholders, the prioritization of features and also the objective function when we are modeling.
Author come out with a new way that combine two ways, using science way to create several solution and let the human judge which solution is best by experience. There will be three steps of this solution: modeling, exploration and consolidation.
       
      1. Modeling: Plan the objectives and constraints of the problem, offer the stakeholder to voting it, and finally estimate the current resources.
      2. Exploration: Author developed specialized integer programming algorithms find solution.
      3. Consolidation: The manager decide the solution based on his experience and context of the problem, also the manager can simulate some problem in the real development to think about the solution.
And the science way is a tool to create solution, but the final decision will be made by the project manager.
But the practical effect of this approach still need some experiment to prove.

Good: This article first of all describe the current status of software development, and describe the importance of release planning, to come out with the new approach, the author describe the pros and cons of both Art way and Science way. And also author give a very detail description of his new approach.

Bad: I think the only bad for this article is the limitation of the new approach is missed, the author didn't discuss the limitaion of this new approach and also he ignore the influence of the number of release.

———————————————————————————————————————————————————————

AR2: Svensson, Richard Berntsson, and Bjorn Regnell. "A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements." Requirements Engineering: Foundation for Software Quality (2015).

SUM2: In MDSD, almost all the method and approach used to make RP didn't consider about the Quality Requirements. But QUPER model consider about how to deal with the Quality Requirement. QUPER model is used to face the challenge about the fast software development technology, and also increase the importance of QR in the company in order to help company get more market competitiveness.
There are two main factor that promote the development of QUPER model. First is the direct need identified in industry. Second is that there are no suitable model found in the literature. And also when the company deal with the QR and the RP of QR, they cannot find a suitbale model to judge it. So there is a great need to promote the development of QUPER.
There are several steps of QUPER model.
       
      Step1. Identify the QR(consider about the features, market, hardware or competitor)
      Step2. Define a scale and unit for QR(used to judge the quality of QR)
      Step3. Identify  reference levels.(Point  estimates including a single ﬁgure, Interval  estimates including a [min,  max] interval,  Triangle  distribution  estimates including a three-tuple of [low bund, most probable,high bound])
      Step4. Elicit quality breakpoints(the lowest acceptable value on the market)
      Step5. Estimate cost barriers(to estimate the budget for each QR, author think two CB are better, one for software change, anthor for the new hardware or something influence the whole software architecture)
      Step6. Set candidate requirements
      Step7. Identify cost dependencies
And throught a case study of large company operating in a market-driven RE context using a product line approach.
And the conclution from the case study is that QUPER model is feasible and scalability in the company to improve the measurement of QR and also improve the company's market competitiveness.

Good: This article fully describe the reason why we need some new model to let the reader notice the importance of QUPER model, and detail describe the steps and principles of QUPER model, also the case study show the effect of QUPER model.

Bad: This article just describe the common steps of QUPER model, but as we know, common steps may be not suitable for every situation. So in the case study, I think the author should discuss the change of QUPER model when we are facing real situation.

———————————————————————————————————————————————————————
  
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
      
      Step 1: Define quality
      Step 2: Estimate current quality also the competing one
      Step 3: Estimate the breakpoint
      Step 4: Discuss the actual targets
And follow these steps and after the research on the Sony Ericsson case. Authors come out with a solution that:
      
      1. The QUPER model is easy to use and learn, not very complex, and good for discussing between team members.
      2. The QUPER model is useful and related when the company make high level decision of quality requirements in the release planning.
      3. The main challenge of the QUPER model is that it's difficult to identify and specify the values for the differentiation and saturation breakpoints.

Good: Same as the last article, this article discuss the reason of why we need QUPER model at first, and this article is mainly focus on the real case, we can see the author make some change to let QUPER model can be very suitable for different situation. That is what I think best.

Bad: Too less description of QUPER model itself. So I suggest to read this article and the last article together to make full understanding of QUPER model.

———————————————————————————————————————————————————————

AR4:Regnell, Bjorn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: Results from an industrial process improvement programme." Requirements Engineering 3.2 (1998): 121-129.

SUM4: This article mainly describe a specific industrial RE process for packaged software, called REPEAT (Requirements Engineering Process at Telelogic. REPEAT is a requirements enginnering process which can be used to manage the requirement in the release cycle.And REPEAT is focus on how to select the requirement and also the release planning. There are several actors in the REPEAT:
      
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

Good: This article detail describe the REPEAT process, from the actors to the phases and also use some process enactment scenarios to show how to deal with the problem in real project. And the conclution of this article is based on both theoretical knowledge and practical results.

Bad: Only one thing bad I think, this article did not decribe the current status at first, in other words, the reason why REPEAT is important is not adequate.

———————————————————————————————————————————————————————



Seminars Two
———————————————————————————————————————————————————————

Q1: Read up on GAP/CVA/IVA Analysis.

A1:

      GAP Analysis: Every development process will have the target or desired performance, but in fact, the actual performance cometimes are not same with the desired one, there should be some gap between them, GAP Analysis means the analysis to find out these gap, to find out how and where can we improve the process. 
      CVA Analysis:
      IVA Analysis:

———————————————————————————————————————————————————————

Q2: What tools are available for Continuous Integration?

A2: There are lots of tools are available for Continuous Integration, for example, CruiseControl, LuntBuild, TeamCity, Bamboo, QuickBuild, Hudson and so on. And from the selection of several free tools, I download the QuickBuild for trying. After I trying it, I find out that QuickBuild is little bit different from other tools, first of all, QuickBuild doesn't have the concept of project, QuickBuild use configuration instead, but to be honest, I didn't understand very well about the configuration, but I think it's similar with the root node of tree. The three main processes in the QuickBuild are CheckOut, Build, Publish Artifacts. And since the QuickBuild is based on configuration, so I can set child node to make the tree structure of project. Because I just download the free version of QuickBuild, so I just can set max 16 configuration. And also QuickBuild can simply copy the configuration, it's very convenient to use.

———————————————————————————————————————————————————————

Q3: What is technical product management?

A3: Technical product management is a kind of product management way that requires the managers have technical background. Regular product manager can be familar with the management of project and also have some experience, but without the technical background. There will be some problems when working together with the developer. And the technical product manager do not need to design or develop the software since they are actually the product management role working together with the software development team. Technical product management is an approach that let the product manager have more knowledge about the real development work. So the manager can manage the process more reasonable and efficient, and improve the plan with his knowledge, technical skills and experience. And Technical product management should focus on the business side of role. As we said before, techincal product manager have technical skills, so the communication between manager roles and development rolos will be easier.
    
———————————————————————————————————————————————————————

Q4: What is roadmapping? How can you do it large scale?

A4: Therefore, it is possible to carry out predictive derivation by "roadmap", and by continual construction and revision, the organization of the enterprise can be operated and the countermeasure can be proactively responded to the predicted trend. The "path map" can effectively deal with the problem of time-varying targets (moving targets), is the biggest difference with the general strategic planning tools. In the initial stage of the project execution process, the roadmap is used to locate the project attributes and input resources. This is achieved by observing the market dynamics, forecasting the technology and generation deductions, and advancing the "roadmap" And the implementation of the project implementation and communication platform for the coordination of resources and scheduling with the basis.

———————————————————————————————————————————————————————

AR1: Tony Gorschek, Claes Wohlin，"Requirements Abstraction Model", Requirements Engineering, 2006, Volume 11, Number 1, Page 79

SUM1: In recently development, market-driven incremental product development and release is becoming very common in software industry. Incremental product development means choosing an optimal subset of requirements in a certain release including what is the requirement, when should the requirements released, and how much resource we need for these requirements, how the customer involving into the development to improve the quality. And as the sources of requirements are very different and also requirements sometimes are indirect in the process. It's hard to get the requirement since they have different forms and shapes at what we called different levels of abstraction. So in the market-driven incremental product development, the product manager should be able to solve the problem that how to make the continuous incoming stream requirement ranging from abstract form to the detailed form. To solve the problem, author think RAM is the best solution. 
RAM is model to provide product manager the requirment engineering model to help their work. RAM can support the situation which will deal with lots of continuous incoming stream requirement. Using different types for inputing requirements and divide these abstract requirements into some detail and readable requirements. There are four main advantages of RAM:
      
      1. In RAM, every requirements will be compare with the company or project strategy. So every product will not influence the total management target.
      2. Every requirement will divede into several abstraction level so it is good and easy enough to develop.
      3. Using RAM, it's easy to compare different requirements. It's important when we face the problem of prioritization of requirements.
      4. RAM can help every staffs involving the project to understand more about the requirements.
And when we come to the real situation, we can divide the  process into following action steps:
      
      1. Specify: Description the requirements, the reason and benefit of the requirements, risks of the requirments and the title of requirements.
      2. Place: Since there will be lots of different abstraction level, so we need to consider about how to place the requirements in to different abstraction level.
      3. Abstraction(work-up): Subsequent the requirements into different abstraction level and also breakdown the requirement.
And also the discuss how to do the validation work in RAM, basiclly divide into static validation and dynamic validation:

      1. Static Validation: Consists of Review and walkthroughs way to validate the product
      2. Dynamic Validation: Consists of a live industry requirements engineering effort.
And the conclusion of this article is that RAM is a good approach to help product manager to handle and deal with the requirements on multiple levels of abstraction in a continuous requirements engineering easier, also reduce the risk in requirement engineering, finally improve the quality of products and development and process.

Good: This article first of all describe the reason why we need RAM, then describe what is the RAM, and then show us how to do the RAM step by step. Using the case to detail show every steps in the real situation. And author consider about all most all the phase we may faced in the development work, and the conclusion is based on the knowledge and practice experience.

Bad: I don't think anything bad in this article, the only thing I think can be improved is the maybe author can pay attention to the practice experience, and put less space on theoretical knowledge, since requirement engineering is an practice problem.

———————————————————————————————————————————————————————

AR2: Khurum, Mahvish, Khurum Aslam, and Tony Gorschek. "A Method for Early Requirements Triage and Selection Utilizing Product Strategies." Asia-Pacific Software Engineering Conference (2007).

SUM2: With the development of software development, the market-driven development is gaining more attention recently. And the change will directly influence the traditional requirement engineering. Market-driven development requirement engineering is more related to internal sources including developers, marketing groups and so on. We need to pay more attention to the market information and competitor information, and since MDRE is a continuous acticity, will influence the project during all the release. And MDRE need to continuously deal with lots of requirements. We need to discard some unimportant requirement as early as possible, then we can pay more attention to important requirements. So we present a method for Early Requirements Triage and Selection(MERTS), there are two main goals of this MERTS:
    
      1. MERTS put both strategic and technical views into consideration, to ensure the decision areas is abstract and also weigh their relative importance.
      2. MERTS can be used to help manager to triage the requirements and select the right requirements for realization.
The prerequisite of MERTS is that the requirements which we need to deal with should have similar abstraction level with our product strategy. And there are three part of MERTS:

      1. Early Requirements Triage: First of all, we need specify the requirement especially state the goals we need to meet, the way we meet the goal and the thing we need to do. Then we need to assign weights for different requirements. Finally compare the requirements with weights we assigned.
      2. Requirements Selection for Release: After we selected a set of requirement, we need to do following things. First, specify the product technology roadmap. This roadmap will show when we need to do what thing with what resource. Second, we need to estimate the resource to ensure the feasibility of requirements.
      3. Strategy Rationale: Document the reason for each strategy for future plan.
To explore the effect of MERTS, author use two case study to research on it. And the conclusion of this article is MERTS is good to help product manager to build strategy but there are still some limitation for the MERTS.

Good: Detail, clear, describe the reason of why we come out with MERTS, and also step by step show us how to use the MERTS.

Bad: MERTS have lots of limitation in my opinion, for example, MERTS will do better if we have lots of initial investment and cannot work well if there is lots of continuously resource. And also I think MERTS has been limited in scope like author said, author need to do more research and make some change to improve MERTS.

———————————————————————————————————————————————————————

AR3:Tony Gorschek, Alan M.Davis. "Requirements engineering: In search of the dependent variables", Information and Software Technology, Volume 50, Issues 1-2, January 2008, Pages 67-75.

SUM3: Since when software team modify the requirements engineering process, they will always based on the product quality, but it's not enough and also flawed to just consider about the product quality. So the author present a new framework. These framework will pay attention to something more important than SRS, and will make positive or negative influence to the success of product even company. In most company, they will only consider about the process of requirements engineering and the main output of requirements engineering.
There are five levels of the new framework, we will starting at center and working out.

      1. Requirements phase: Requirements phase is also the most usual part in recent company to be considered about. In this new framework, we need to pay more attention to the requirement cost and time also the quality of requirement.
      2. Project: Project related to lots of factor, whether the project is success, whether the project finished on time, whether the project finished under the limitation of budget and so on. So we need to consider about the project budget and time and the project estimates. One more thing is to pay attention the change of requirement degree.
      3. Product: Product level means to analyze whether the product is success, here the success means meet the customers' requirement. We need to focus on the selection of requirements, since a good selection will reduce the risk and improve the effciency. And the degree of impart for different factor in the product.
      4. Company: In company level, we need focus on the influence of product to the company. Success of product doesn't means the success of company. We need to consider about the portfolio management, how to align strategic and also the degree of impact.
      5. Society: Every company activities need to consider about the influence of society, both positive and negative.
And the conclusion of this article is that in high level , we need to consider more aspect. Requirements engineering is a complex work and the product manager is the connection between management and development. Every one involving in the project need to know any change to the process will influence lots of quality level, so we can use these five levels to consider about the problem.

Good: Author come out with some new idea which is really good I think, for example, the last two level, company level and society level. Anything happened in the project process may influence the company's plan and also the society image of company.

Bad: Author want to two things in this articel, first is to present the five levels consideration model and second is to show that product manager need to consider any change in process with different aspect. But I think author should focus on one thing, in my opinion. Second thing could be the reason of the five levels model, and focus on the description of the five levels and how to consider these levels in some practice cases.

———————————————————————————————————————————————————————

AR4:R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935

SUM4: Since the increases of different software and also the increases of complex of software, requirements engineering process become more and more important, and the product is based on its functional requirements and quality requirements. A success product means good function with good quality. We cannot just ignore the quality. Quality will also influence the market competitive strength. So the quality of product is very important but in fact, lots of company didn't consider about it. And this article will research on the 22 staffs from 11 different company in Sweden to know how these company deal with the quality. There are two kinds of company, first kind is to develop and sell software to other company. Another kind of company is to develop product for market.
Then the author describe his research methodology and validty ways, and following are the conclusion:

      1. For B2C, usability is the most important and for B2B, safety is the most important. So the most important quality requirements should be consider about based on company itself.
      2. There is a close realationship between requirements and cvalue.
      3. For the cost estimation of QR, the result of research show that there is no direct difference between FR and QR. And the expert opinion is still the main method.
      4. There are almost 20% QR are dismissed in some phase during the whole project.
More attention to QR will directly increase the market competitive strength of product. So the author think the company should focus on it.

Good: Simple reaserch, but lead to a very serious result, from the result of research we can see that recently company begin to pay more attention to the QR, but beginning is not enough, and also company didn't go very deep or quality requirement engineering. 

Bad: Research target is little bit small, so the scope is little bit small, so the result of this research will be limited in different situation.

———————————————————————————————————————————————————————

AR5: J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997.

SUM5: The final target of developing a software systems is to meet the stakeholder's needs and requirements to see the a competitive edge. But for each software, there will be lots of requirment both functional, nonfunctional from different stakeholder. Theoretically we need to satisfy all the requirement to develop a best software, but in fact, with the limitation of technology, time and resource, we cannot meet every requirement. So the product manager need to choose a subset of customer's requirements, but it's a hard job. So the author present a cost-value approach for prioritizing requirements and applied it to two commercial projects.
Author think a process for prioritizing requirements must be simple and fast and also accurate and reliable, and there be several steps of author's new approach:

      1. Requirements engineers need to review the completeness of all the requirement to ensure they are described well and readable.
      2. Users and Customer assess the value of requirements by applying AHP's pairwise comparison method.
      3. Let the experienced requirements engineers to esimate the cost of each requirements.
      4. Calculate the relative value and implementation cost, put them into a cost-value diagram.
      5. Stakeholder use this diagram to analyze the every requirements and decided the prioritization of the requirement, also can build the release plannig based on these diagrams.
Author also use two case to show the effect of this new approach, one case is about the RAN project, another is about the PMR project. and the conclusion of this article is:

      1. This new approach can fill the need of the trade-off analysis.
      2. This new approach can provide the mathematical basis for the software requirment engineering.
      3. This new approach can put less attention to the dependency of requirement to reduce the cost.
      4. This new approach can reduce the difficult of communication between customers, users and project managers.
      5. This new approach is efficiency to determined the requirements priorities.
      
Good: Prioritization work is very difficult since the manager need to consider lots of things for example the importance of different customer, the cost, the time and so on. But this approach combine the relative value and implementation cost to provide a important information for the requirements prioritization work, I think it's very useful. And the two case also prove this opinion. 

Bad: This new approach didn't consider about the dependency of requirement. The dependency between requirement is also a very important factor in prioritization work. So I think authoer may need to change something in this new approach to consider about this factor. In my opinion, if we put dependency into consideration when we are doing requirement engineering, there is no doubt we can make a better release plan and reduce cost and time in real developemnt of software.
      
