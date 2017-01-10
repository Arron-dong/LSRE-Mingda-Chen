Change history in this commitment:

Nov 20, 2016：It's my first time to use Github, so I just find out how to show the feedback from you, and this commitment is the improvement based on all the past feedback. And I am sorry I use the commit button as "save" button before, so everytime I come out with something or find something useful, I will write here or copy here as recording. But from now, I will update change history in this commitment here to show anything I done in this commitment and write the seminarnotes in local text and upload them when I finished it. I am sorry for disturbing you before. 

Nov 22, 2016: Updated the result of homework of Seminars three.

Dec 3, 2016：Updated the result of homework of Seminars four, I thought I already updated it early...

Jan 10，2017：Read more and think more, make some change based on the feedback.

Seminars One
———————————————————————————————————————————————————————

Q1: What is large scale requirements engineering?

A1: With the growth of complexity and size of software intense systems, the sets of requirements increasingly become large and complex. The increased role of software come with the increased number of requirements. Lots of new idea will come out in MDRE based on the change of situation, the flow of new requirements will directly bring more requirements from different perspective of customers than the project team can deal with during each project cycle. So the size of requirements databases may exceed 10 thounsands of requirements. And this situation is called large scale requirements engineering. The process of LSRE is similar with RE, which is to elicit, specify, prioritize and manage the requirements. Final goal of LSRE is to deal with the requirements and produce better product.

 
 
Reference:
      
      1. Luiz Marcio Cysneiros, Eric Yu, " Requirement engineering for large-scale multi-agent systems", April 2003.
      2. Wnuk, Krzysztof,"Exploring factors affecting decision outcome and lead time in large-scale requirements engineering", Journal of software: evolution and process, volume 27, Issue 9, page:647-673
      3. Wnuk, Krzysztof,"Understanding and Supporting Large-Scale requirements management",2010.
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
  
Reference:

      1. Wnuk, Krzysztof,"Exploring factors affecting decision outcome and lead time in large-scale requirements engineering", Journal of software: evolution and process, volume 27, Issue 9, page:647-673
      2. Wnuk, Krzysztof,"Understanding and Supporting Large-Scale requirements management",2010.
———————————————————————————————————————————————————————

Q3: What is the order of magnitude of the number of requirements we are
discussing?

A3：Thousands or more.

Reference:

      1. Wnuk, Krzysztof,"Exploring factors affecting decision outcome and lead time in large-scale requirements engineering", Journal of software: evolution and process, volume 27, Issue 9, page:647-673
      2. Wnuk, Krzysztof,"Understanding and Supporting Large-Scale requirements management",2010.
———————————————————————————————————————————————————————

Q4: Read up on and summarise [Strategic] Release Planning

A4: Release planning is a planning process that during the agile software project, which is a high level decision making process to make a release plan, release plan is an evolving log that describes which function or feature will be delivered in next release or future release. Also release planning will plan and estimate the resource delivered for each feature.
There are several main advantages of release planning:
   
      1. Gives the project team a common understanding about the feature they need to develop.
      2. Gives the project team a common understanding about the resource they can use.
      3. Prioritize the feature.
      4. Reduce the conflicts and lead the team to a common target.
      5. Locate and discuss problem they meeted.

Reference:
      
      1.Ruhe, Gunther, and Moshood Omolade Saliu. "The art and science of software release planning." IEEE Software 22.6 (2005): 47-53.
      2.An Ngo-The, Günther Ruhe, " Optimized Resource Allocation for Software Release Planning", IEEE Transactions on Software Engineering 2009 vol.35: 109-123.
      3.Svahnberg, Mikael, et al. "A systematic review on strategic release planning models." Information & Software Technology 52.3 (2010): 237-248.
      
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

Good: This new approach combine the science way and art way, it can be used to make the release planning comprehensively. Science way can make a set of solution, and art way can used to pick the final solution based on human experience.

Bad: I think the only bad for this article is the limitation of the new approach is missed, the author didn't discuss the limitaion of this new approach so that I think the bad of this new approach is its limitation. And also he ignore the influence of the number of release. In opinion, the number of release will influence this approach a lot, large number of release cost lots of time, then there will be lots of uncertain factor, so the science way will be less available.

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

Good: QUPER model fill the gaps in the quality requirements management approach. QUPER can systemly analyze the QR and also consider about the market level factor, which is very good to improve the quality of product and competitive strength of company. And in some steps, its similar with the functional requirment management, so it can be easy to learn.

Bad: This article just describe the common steps of QUPER model, but as we know, common steps may be not suitable for every situation. So in the case study, I think the author should discuss the change of QUPER model when we are facing real situation. And for me I think the QUPER model in this article cost too much time to analyze the QR if its in the real case, and the time factor will influence the situation of market. So I think QUPER model is little bit complex, for example, in my opinion step3, step4, step5 can be done together as a cost-value analysis.

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

Good: Same as the last article, but this article show us the real case of QUPER model, we can see the author make some change to let QUPER model can be very suitable for different situation just like what I expected in last article. That is what I think best. This article is better than the last article since this article show us the practice effiency of QUPER. And the good for the real case QUPER model is similar with the solution, easy to use and learn, not complex, useful and so on.

Bad: No bad thing for the QUPER model in the Sony Ericsson case, it's effictive and not complex.

———————————————————————————————————————————————————————

AR4:Regnell, Bjorn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: Results from an industrial process improvement programme." Requirements Engineering 3.2 (1998): 121-129.

SUM4: This article mainly describe a specific industrial RE process for packaged software, called REPEAT (Requirements Engineering Process at Telelogic). REPEAT is a requirements enginnering process which can be used to manage the requirement in the release cycle.And REPEAT is focus on how to select the requirement and also the release planning. There are several actors in the REPEAT:
      
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

Good: As a methods in 1998, REPEAT process consider lots of perspective during the requirements engineering, and this REPEAT process almost decide the normal process(such as elicitation, specification, prioritization)。

Bad: As a methods in 1998, I think REPEAT process is good enough for the RE in that time, but with the development of software, this method will come out with lots of problem, so the limitation of REPEAT process is not very clear. Also for each phases, I think the description for each process is not complete enough so maybe there will be some problem when we are dealing with real case.

———————————————————————————————————————————————————————



Seminars Two
———————————————————————————————————————————————————————

Q1: Read up on GAP/CVA/IVA Analysis.

A1:
      GAP Analysis: GAP analysis is to identify and manage both the positive and negative gaps between the current product and customer expected one. Gap will appear in the detail function, feature and the related quality requirements. And positive gap means that the product we developed is more than the customter expected one and the negative gap means that the product we developed is not enough to satisfy the customer. GAP analysis can help the project team to think about how to improve the current product during the development based on the customers' requirements.
      
      CVA Analysis: Customer Value Analysis, an important thing need to be done in successful customer realtionship management, which will based on the analysis of customer history and lifecycle, find out the most valuable current potential customers, or meet the customers' real needs, and improve the retention of customer. The result of this analysis is:
             
             1. Define what is the requirement of customers.
             2. The suppliers which is makeing positive or negative effect on the requirements
             3. Your competitive strength.
             4. The improvement you can do to satisfy the customers.
             5. The right way of communication with your customers.
             
      IVA Analysis: Internal Value Analysis, this is a process of identifying and evaluating an organization's specific characteristics for example, Resources(Financial resource, Human resource and etc), capabilities and core competencies and so on. And the IVA's goal is to find out the company's current vision, mission and strategies.

And IVA will find out what do we have, CVA will find out what customers' wants, and gap analysis will find out the difference between them.

Reference:

      1.Tony Gorschek, Alan M.Davis. "Requirements engineering: In search of the dependent variables", Information and Software Technology, Volume 50, Issues 1-2, January 2008, Pages 67-75.
      
———————————————————————————————————————————————————————

Q2: What tools are available for Continuous Integration?

A2: There are lots of tools are available for Continuous Integration, for example, CruiseControl, LuntBuild, TeamCity, Bamboo, QuickBuild, Hudson and so on. And from the selection of several free tools, I download the QuickBuild for trying. After I trying it, I find out that QuickBuild is little bit different from other tools, first of all, QuickBuild doesn't have the concept of project, QuickBuild use configuration instead, but to be honest, I didn't understand very well about the configuration, but I think it's similar with the root node of tree. The three main processes in the QuickBuild are CheckOut, Build, Publish Artifacts. And since the QuickBuild is based on configuration, so I can set child node to make the tree structure of project. Because I just download the free version of QuickBuild, so I just can set max 16 configuration. And also QuickBuild can simply copy the configuration, it's very convenient to use.

———————————————————————————————————————————————————————

Q3: What is technical product management?

A3: Technical product management is a kind of product management way that requires the managers have technical background. Regular product manager can be familar with the management of project and also have some experience, but without the technical background. There will be some problems when working together with the developer. And the technical product manager do not need to design or develop the software since they are actually the product management role working together with the software development team. Technical product management is an approach that let the product manager have more knowledge about the real development work. So the manager can manage the process more reasonable and efficient, and improve the plan with his knowledge, technical skills and experience. And Technical product management should focus on the business side of role. As we said before, techincal product manager have technical skills, so the communication between manager roles and development rolos will be easier.

Reference:
 
      1. Tony Gorschek,"Requirements Engineering Supporting Technical Product Management", 2006
———————————————————————————————————————————————————————

Q4: What is roadmapping? How can you do it large scale?

A4: Roadmapping is a way to create the product strategies for the long-term development which also means to plan for a product. Roadmapping combine early information, current knowledge and customer priorities and also the long-term goal to make a plan in order to deliver the right products to the right markets at the right time. Roadmapping is not only just aim for current product, but also to satisfy the company long-term business goals. There are four advantages of roadmapping:

      1. It provide a low cost and low risk methods for company to gain the feedback from customer and market.
      2. It provide a framework about the future plan of product.
      3. It provide a framework about how much resource we need to deliver the feature or function in the roadmap
      4. It provide a relatively stable method to deal with the uncertain factor during the development.
In large scale, there will be lots of uncertain things, it means we need to continuous modify the roadmap, that requires the product manager to make a particularly detailed roadmap, and every change in the roadmap need the data support(market situation, customer value and so on).

Reference:

      1. Tony Gorschek,"Requirements Engineering Supporting Technical Product Management", 2006
      2. Suomalainen, Tanja, et al. "Software product roadmapping in a volatile business environment." Journal of Systems and Software 84.6 (2011): 958-975.
———————————————————————————————————————————————————————

AR1: Tony Gorschek, Claes Wohlin，"Requirements Abstraction Model", Requirements Engineering, 2006, Volume 11, Number 1, Page 79

SUM1: In recently development, market-driven incremental product development and release is becoming very common in software industry. Incremental product development means choosing an optimal subset of requirements in a certain release including what is the requirement, when should the requirements released, and how much resource we need for these requirements, how the customer involving into the development to improve the quality. And as the sources of requirements are very different and also requirements sometimes are indirect in the process. It's hard to get the requirement since they have different forms and shapes at what we called different levels of abstraction. So in the market-driven incremental product development, the product manager should be able to solve the problem that how to make the continuous incoming stream requirement ranging from abstract form to the detailed form. To solve the problem, author think RAM is the best solution. 
RAM is model to provide product manager the requirment engineering model to help their work. RAM can support the situation which will deal with lots of continuous incoming stream requirement. Using different types for inputing requirements and divide these abstract requirements into some detail and readable requirements. There are four main advantages of RAM:
      
      1. In RAM, every requirements will be compare with the company or project strategy. So every product will not influence the total management target. There will be early selection for requirements.
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

Good: Requirements Abstraction Model compare every requirements with the requirements of other abstraction level in order to find out whether the incoming requirements are related to the current product and the strategy of prodcut. In other words, it can be seen as a early selection for incoming requirements.

Bad: Requirements Abstraction Model, in my opinion, is too complex and cost too much time in practice, especially in large scale requirements engineering. And abstraction levels of different requirements are little bit hard to identify in practice. It's better if we can use other method to do the first selection for the incoming requirements to reduce the number of requirements, then use RAM.

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

Good: The authors did not use one-size-fit-all philosophy when they are creating the MERTS, so it's possible for any company to use MERTS based on their own situation and degree needed.

Bad: The bad for MERTS in my opinion is its effect, would MERTS provide good effect in practice? and how to balance the benefits of MERTS and the costs of MERTS? In these two question, I expect more research.

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

Good: Author come out with some new idea which is really good I think, It show us that every incoming requirements need to be judged based on its relationship between other levels. And also the conclusion of this article is really good. Just like the goal of roadmapping that the value of every requirements need to be considered about based on the strategy。 

Bad: In author's conclusion of this article, author said that they create a taxonomy of levels on which the impact of RE process changes can be assessed. I agree that author create a raxonomy of levels, but I think it is just a structure to tell us which factor will influence the RE process, but it cannot used to assess the RE process, for example, in the project level, author mentioned that poor estimation techniques should be a cause, but author didn't show us what is poor estimation techniques or what is good estimation techniques, to assess something I think we need a reference point, we need to know what is good, then we can think about the distance between good one and ours. So I think author just point out the influencing factor, cannot use for evaluating or checking.


———————————————————————————————————————————————————————

AR4:R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935

SUM4: Since the increases of different software and also the increases of complex of software, requirements engineering process become more and more important, and the product is based on its functional requirements and quality requirements. A success product means good function with good quality. We cannot just ignore the quality. Quality will also influence the market competitive strength. So the quality of product is very important but in fact, lots of company didn't consider about it. And this article will research on the 22 staffs from 11 different company in Sweden to know how these company deal with the quality. There are two kinds of company, first kind is to develop and sell software to other company. Another kind of company is to develop product for market.
Then the author describe his research methodology and validty ways, and following are the conclusion:

      1. For B2C, usability is the most important and for B2B, safety is the most important. So the most important quality requirements should be consider about based on company itself.(but the research target is small, so the result of this conclusion is limited,for example, safety is very important in lots of company, but is not for all the company)
      2. From the result of research, B2B company think that REQUIRES is the most important interdependency type and B2C think CVALUE is the most important interdependency type.
      3. For the cost estimation of QR, the result of research show that there is no direct difference between FR and QR. And the expert opinion is still the main method.
      4. There are almost 20% QR are dismissed in some phase during the whole project.
More attention to QR will directly increase the market competitive strength of product. So the author think the company should focus on it.

Good: Simple reaserch, but lead to a very serious result, from the result of research we can see that recently company begin to pay more attention to the QR, but beginning is not enough, and also company didn't go very deep or quality requirement engineering. 

Bad: Research target is little bit small, so the scope is little bit small, so the result of this research will be limited in different situation. For example, there are several company are similar with their domain, it's better if user choose some company with the different domain, then the result of research will be more convincing.

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
      
———————————————————————————————————————————————————————


Seminars Three
———————————————————————————————————————————————————————

Q1: Read up on the Boston Matrix

A1: Boston Matrix is a methodology to plan the product portfolio. Boston Matrix based on two factor that could decide the product, the market gravity and enterprise. The main goal of this methodology is to solve the problem of how to make the product variety and structure of the enterprise meet the changes of market demand, only to follow the market situation, the production can be meaningful. Also Boston Matrix provide a good help for company to effectively allocate the resource to the development of product, which is also the key for company to gain more competitive strength. There are four combination of business unit: Question Marks, Stars, Cash Cows, Dogs. Question Marks are growing rapidly but low market shares. Stars means the high grow rate and strong relative market share. Cash Cows means the return on assets will larger than the market growth rate. Dogs means the business with low market share and low growth rate.

Reference:

I didn't find some article good for describe the Boston Matrix, so my answer is based on following websites:
http://www.netmba.com/strategy/matrix/bcg/
https://en.wikipedia.org/wiki/Growth%E2%80%93share_matrix

———————————————————————————————————————————————————————

Q2: How do you connect your requirements to your architecture?

A2: In product management, first of all. we need to do the portfolio management to make a decision for the product lifecycle and product line. And the product lifecycle and product line will be the reference when the product manager doing product roadmapping. And every incoming requirements need to be judged based on the dependency with the product roadmap. In other words, a critical requirement need to related to requirements in other level(process, product, company, society). And the requirements come from situation of market, the customer and company itself, which are all the important role in my architecture. And after the requirements engineering work. the requirements list will be the reference to set the release plan, which is also a kind of connection to architecture. In my opinion, requirements are the basic element of my architecture, and all the work for requirements (elicitation, specification, prioritization, selection, deliver and so on)are going to make my architecture better.

Reference:

1. De Weerd, I. Van, et al. "Towards a Reference Framework for Software Product Management." Requirements Engineering (2006): 319-322.
2. Tony Gorschek, Alan M.Davis. "Requirements engineering: In search of the dependent variables", Information and Software Technology, Volume 50, Issues 1-2, January 2008, Pages 67-75.

———————————————————————————————————————————————————————

Q3: Can you connect all requirements directly? What do you do if you cannot?

A3: Of course I cannot connect all requirements directly. There are two main reason. First is that there are too many requirements especially in large scale requirement engineering, it's impossible to connect all of them into architecture since the limitation of time and resource. Second is that not every requirements is valuable enough for put into architecture to consider about. I will firstly do the early selection work on these requirements, methods can be lots of, but the goal is to find out the valuable requirements(valuable for roadmap, for company strategy, for market situation). Secondly evaluating the requirements based on its cost and its value. Finally organize the requirements based on module, dependency, requirements level. 

Reference:

1. De Weerd, I. Van, et al. "Towards a Reference Framework for Software Product Management." Requirements Engineering (2006): 319-322.

———————————————————————————————————————————————————————

AR1: De Weerd, I. Van, et al. "Towards a Reference Framework for Software Product Management." Requirements Engineering (2006): 319-322.

SUM1: Recently, the software product management become more and more important with the development of software technology. And the work for product management become more and more complex. To solve this problem, author come out with a reference framework for software product management. Following are the key processes of this framework.
      
      1. Portfolio management: This process set the existing products, look for new products based on market and company strategy, and decide the product lifecycle.
      2. Product roadmapping: This process plan and portray the use of every resources and the relationship between the "road" in a long-term time.
      3. Requirements management: This process is used to elicit the requirements, specify the requirements and organize the incoming requirements.
      4. Release planning: This process is to prioritize the requirements and select the requirements for next release.

Good: This reference framework is very good for me now. After read lots of article about the product management, I was little bit confused about the relationship between different process. And this framework especially the Figure 1 inside this article, directly show me the relationship and also give a better understanding about the process of product management.

Bad: At the past I think that author need to add a factor called "Competitor" into the figure1, because I think competitor is a important influencing factor for software product management, but with the learning, I think actually author didn't put lots of other factors which is less important in this figure. So I understand that author just want to show several most important factor. So my advice now is that add a factor called "Others", and shortly name, describe the other factor by text may be a good improvement for the reference framework.

———————————————————————————————————————————————————————

AR2: Björn Regnell, Sjaak Brinkkemper, "Market-Driven Requirements Engineering for Software Products", "Engineering and Managing Software Requirements", pp 287-308.

SUM2: With the increasing of software development needs in open market, the market-driven development have became the challenge of RE process, so in this article, author describe the special element that will influence the process and also introduce the requirements state models.
MDRE have some typical characteristics, the development team will make all the decision and take all the risks, there will be lots of incoming requirements, so the number of requirements are large. And there will be multiple release planning focusing on time-to-market and return-on-investment.
Then author focus on the process quality, and divide the requirements into Alfa requirement and beta requirements. Alfa requirement means the requirement have very high inherent quality and should be selected. Beta requirements are those that should be rejected cause its low quality. So in MDRE, we need to find out the Alfa requirements and give up the Beta requirements. Also, we should not judge the value and cost of a requirements just based on itself, we need to think about the its relationship to other requirements.
And this article also propose a process quality model used for requirements selection, a typical requirements state model used in progress tracking, a typical requirements repository used for data management.

Good: This article is a introduction for the MDRE, there is no good or bad on MDRE, so we need to focus on whether the author introduce the MDRE in different aspect comprehensively. And after read the article, I think author describe the MDRE very well. Description of MDRE is detailed.  Key elements of MDRE are presented. Challenge and problem also been described. 

Bad: Different project will have different product with different requirement, no two projects are same. The working structure can be one-size-fits-all, but still need some adjust when we use it in practice. It's same with RE methods, I know that there is some good one-size-fits-all methods that is because they divide the requirements into very detailed types. But in this article, author want to just divide the requirements into Alfa and Beta which I think is too broadly. It may be fits for little project, but not all.I know the author just want to propose a idea about to find out valuable requirement . But the evaluation of value of requirements is very complex. I think it's better if we can add more division into it or using other way to judge it. For example, as I read before, we can think about it in different abstraction level. Based on the relationship with high level requirements.

———————————————————————————————————————————————————————

AR3: http://www.scaledagileframework.com/about/
http://www.cio.com/article/2936942/enterprise-software/introducing-the-scaled-agile-framework.html

SUM3: Scaled agile framework is a framework for developing as an agile team at enterprise scale. It provide a unified view for the product manager, to let them have a better understanding for the trends and analysis. And this framework allow large company to move towards a agile way. A scaled agile framework team might be 8 to 10 people responsible for everything including deliver software, requirements engineering, coding, testing and deployment. And scaled agile framework suggest that in program portfolio management, there should be one office which is responsible for the strategy, program management and investment funding. Following are the benefits of scaled agile framework and these benefits have been proved by lots of company.
      
      1. Increase the productivity of project team.
      2. Increase the quality of the project(process and product).
      3. Reduce the time.
      4. Increase the engagement and satisfaction of team members.

Good: Lots of good thing for Scaled agile framework:
      
      1. Free to use.
      2. The effort have been proved by lots of real project.
      3. Lots of benefits(mentioned in summary).
      4. Still continuously evolving based on world situation
 
Bad: Nothing bad for scaled agile framework, but there are less description about what is scaled agile, in my opinion, scaled agile means that there are several agile teams need to work together. And to be honest, there is still some different opinion for what is the better or best method for scaled agile. As I know, for example, Scrum of Scrums(SoS), Large Scale Scrum(LeSS) and other the Scaled Agile Framwork(SAFe).
Difference：
     
      1. SoS and LeSS only rely on Scrum, so it's good for some team that want to use Scrum in larger scale, but SAFe is based on Agile, think agile in a overall viewpoint. Transform the small agile team into large organization environment.It adapt different method(Scrum, Kanban and so on) for different team.
      2. SoS is good for small organization, LeSS and SAFe are suitable for larger one.
      3. SoS just define the least level structure, LeSS think about the portfolio level and SAFe think about the all company levels.
      4. SoS and LeSS are suitable for low cost implementation team, and SAFe is suiatble for high one.
We need to choose the way by identify the current situation of company.

———————————————————————————————————————————————————————

AR4: Bjarnason, Elizabeth, Krzysztof Wnuk, and Bjorn Regnell. "Are you biting off more than you can chew? A case study on causes and effects of overscoping in large-scale software engineering." Information & Software Technology54.10 (2012): 1107-1124.

SUM4: With the development of MDRE, there are more and more challenge come out that a product management must to face. Since there are lots of new and changed incoming requirement based on market situation and development of technology, that how to choose the requirement into next release become a huge problem. These chosen requirements sometimes will directly influence the scope of product. And scope of product will continuously change during the progress. But problem of overscoping happend a lot. Overscoping means that team set the scope that requirement more resources than the resource we have. So author make this case study to find out the answer for three questions. What lead to overscoping? what is the result of overscoping? how agile RE impact the overscoping?
And the main research method is interviews and the result of interviews will be validated by questionnaire.
The research target , in other words, the case company is a company has around 5000 employees and mainly develop the embedded systems for a global market.
And the result of this case study is that the overscoping is caused by too fast moving MDRE, and caused by lots of incoming requirements. And overscoping will lead to some bad effort such as quality problem, delay progress and cannot satisfy the customer. And agile RE will close some communication gaps but also lead some problem such as more difficult in cost estimation.

Good: I will describe the good thing in two part. First is the method part, this case study mainly use interview and questionnaire but they set the questionnaire as the validation of interview result which is good in my opinion. Second is the result part, the result of this case study is fully based on the real situation of the case company.

Bad: Nothing bad about the result since the result is based on the case company, but the bad is also the case company. Scope management and overscoping are not the particular problem. It's a common problem. So I think if author want to know more about them, author need to focus on multiple case company. Compare the different and same part for different company. They can get more precise result.

———————————————————————————————————————————————————————

AR5: Wnuk, Krzysztof, et al. "Exploring factors affecting decision outcome and lead time in large-scale requirements engineering." Journal of Software: Evolution and Process 27.9 (2015): 647-673.

SUM5: In MDRE, the product must be consistent with the target market requirements in order to create meaningful product. But in MDRE, the frequently change of market and customers' need will directly influence the decision making. It's important to analyze and make change to deal with the change fast. And the time need to make a decision and the effort of decision are very important in this situation, so the author want to find out the factor that influence them. In this article, author use two stage case study to find out the result. 
First case study, authors analyze more than one thousands decision log to find out whether these factor(number of products, release number, and type of customer)will influence the lead time and decision. 
Second case study, authors make a survey on 50 respondents, find out the factor influencing the decision and lead time, also validate the result from first case study.
And the final result of these case studies can be summarized as:
     
      1. The number of products will influence the lead time, more number of products will increase the lead time.
      2. There is no relationship between the number of release and lead time. But the influence of project' size, the process and the company's context still need more research to validate.
      3. The result show when make a decision for large customer, the lead time will be shorter.
      4. In the factor of acceptance(affects more number of product, change requests affecting late releases), two case study shows different result, still need more research to validate.
      5. Rejecting a decision cost less time than accepting a decision, but two case study shows different result. Company want to please as many customer as possible, so the result are different in different case study. 

Good: Methods good, result good, one more thing I want to say good personally. That is about the number of release. In the article "The art and science of release planning", I come out with a idea that the number of release will influence something in RE, release planning, or something related. I try to search some article but it seems there is no article about it. But in this article, the author think about it too. At least, it show me that the number of release will not influence the lead time and decision from the case study. That solve part of my problem. 

Bad: Two bad thing about the result. First, only one case company which is large company using the SPL approach, that means from the case study, we cannot find out the relationship between the size of company, the process and the lead time. Second, there is a result that shows that the lead time will reduced if the decision is for a large customer, I think author should give a detail description about what is "large" customer. I think just use large or small is not enough.

———————————————————————————————————————————————————————

AR6: Carlshamre, Par, et al. "An industrial survey of requirements interdependencies in software product release planning." Requirements Engineering (2001): 84-91.

SUM6: With the incremental systems development strategies become more and more popular, release planning is become more important, and there are six parameters of release planning: available resources, delivery time, requirement interdependencies, requirement priority, system architecture and dependencies to the code base. And this article is focus on the requirement interdependencies and requirement priority. Since the requirement priority is a important factor in release planning, but the interdependencies of requirement will also make influence on the selection of requirement. And author make a survey on five different companies(different size and different domain), and use a simple visualization technique of RQ interdependencies to five case.
And based on the previous interviews, there are 6 interdependency type, AND, REQUIRES, TEMPORAL, CVALUE, ICOST, OR.
The results of this research are following:
      
      1. There is no doubt that the interdependencies of requirements will influence the selection of requirement.
      2. Very few requirements are responsible for a large number of interdependencies.
      3. There are more functionality-related interdependencies(AND, REQUIRES) in bespoke software development, and more value-related interdependencies(ICOST, CVALUE) in product development.

Good: Good thing is that this article research on five different case, so the result is comprehensive in my opinion. Another good thing is author divide the interdependencies into functionality-related and value-related. That means product manager can based on this research to distribute the resource and time more logical.

Bad: Bad thing in my opinion, the division of six interdependency type is not good. I have read some article talked about interdependency. One article named "Requirements Interdependencies: State of the Art and Future Challenges " present a division of interdependency which I think is more detail and comprehensive. It divide the interdependency into Structural Interdependencies(Refined_to, Change_to, Similar_to, Requires), Constrain Interdependencies(Requires, Conflicts_with), Cost/Value Interdependencies(Increases/Decreases_cost_of, Increases/Decreases_value_of).

———————————————————————————————————————————————————————

Seminar 4

AR1:Krzysztof Wnuk, Bjorn Regnell, Lena Karlsson, "What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting", 2009 17th IEEE International Requirements Engineering Conference.

SUM1: With the development of software, every single software or a complex systems will contain thousands requirements and more. But the time and resource of development team is always not enough. So before every development project start or the next release, we need to decide which requirements need to be implement. And the process of selection called scoping which is a key process in the product development. And the change of scope will be influenced by changing market or the developing technologies. But the requirement management tool in lots of company cannot visualize and characterize this change. So author propose the Feature Survival Chart(FSC) to solve it.
FSC is a chart that X-axis means that the scope changes over time, and the Y-axis means the different features. So the FSC will dynamically show the scope changes of every features over time. In this article, green color means in the scope, and red color means out the scope. And through this graph, we can directly see which decisions have been made when and how large impact on the scope they had. Also by using this graph, we can define the measurements which is used to indicate the quality of scoping.
And three case company using this FSC and the result shows that the dominant trend is descoping or negative scoping. And need more understanding about the scope. So the author use quantitative characterization and qualitative rationale for scoping decisions to improve the visualization technique.

Good: First good thing for FSC is its visible, we can directly see the how the decision we make and when the decision we make will influence the scope of product. Second good thing is FSC can give a real-time feedback to the project team so we can continually improve the process and product. Third good thing for FSC is that it is easy to learn and use. 

Bad: Bad thing is that the generalization, in this research, author just use this FSC in one company, so the result of research cannot show that FSC can be used in lots of other case, the uncertain limitation is the first bad thing I think. 

———————————————————————————————————————————————————————

AR2:Krzysztof Wnuk, Tony Gorschek, Showayb Zahda, "Obsolete software requirements", Information and Software Technology, Volume 55, Issue 6, June 2013, Pages 921-940.

SUM2: With the fast change of business environment, the high volatility and quick evolution of requirements become two huge problem, and lots of requirement become obsolete before the completion of project. And to cope with the fast change of requirement, the company need to identify the obsolete software requirements as soon as possible in order to pay more attention to the other requirements. So identification, handling and removal of these obsolete requirement is very important. And this article mainly present the result from an empirical study based on 219 respondents from different companies by survey, and the main target of the survey is to find out how these companies deal with the obsolete software requirements.
And following are the result of this empirical study:
     
     1. The respondents think that OSR means the software requirement which is no longer required for now and future, don't have any business value for customers and users.
	    2. Lots of respondents think OSR will influence the company whose domain is to develop software intensive products.	
	    3. Lots of respondents reported they never deal with OSR before.
	    4. The requirements for laws or standards seems to be more stable than the uncertain requirements.
    	5. The requirements from domain expert seems to be more stable than the requirements from customer or internal staff.
	    6. Identification of OSR is mainly done as manual activity.
	    7. Lots of respondents think we cannot just delete the OSR because we can use them for reference or tracking something. Instead they think it's better to store the OSR and sign it as Obsolete.
	    8. Lot of respondents reported that there is no tools for identification and handling of OSR.
	    9. The identification of OSR seems to be passive.
	    10. OSR seems to make more influence to the large scale requirement project.
	    11. Most of respondents think that we need to deal with the OSR in requirement analysis phase and validation phase.
	    12. Latency may not be the main factor for the problem of OSR.

Good: Good thing is obviously, that author think about the OSR, to be honest, I read lots of articles and books to teach reader how to deal with the new incoming requirement, this is the first time I find someone is thinking about the OSR, and this article is just a report for the survey so it may not bring some knowledge or conclusion to me. But at least, this article show me a new area in requirement engineering and it's interesting.

Bad: Just a report for the survey and the summary of conclusion is based on the result of survey. I really don't know whether the OSR will make bad influence to the project. I mean it's hard to balance the cost and benefit of dealing with OSR. So at least now, I didn't find something bad in this article, especially the idea about to deal with OSR.
