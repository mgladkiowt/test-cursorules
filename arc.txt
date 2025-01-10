How to build quality products fast?

TG Architecture guides us to build quality software products fast by:

Maximizing Quality: This includes both the external quality, which users experience directly through the software's performance and interface, and the internal quality, which, though invisible to users, is crucial for developers and managers in terms of system maintainability and adaptability.

Improving Speed of Delivery: This involves reducing setup times, implementing default decisions and tactics, and minimizing overheads during software modifications. A well-designed software is easy to modify and understand. 

What makes good Software Architecture? 

Good software architecture can either support or hinder a system's quality attributes. The quality attributes fall into two* groups: quality attributes at development and quality attributes at runtime. For a typical OWT project, several specific quality attributes are selected in each category. However, attributes like Integrability or Sustainability may be optional for certain projects. Architects are responsible for prioritizing these based on project needs.





* note there will be a 3rd group of qualities introduced in context of internal projects, a.k.a. https://openwt.atlassian.net/wiki/spaces/~712020f1a74b2daf424243928e3b72e79acc9c/pages/11117690888  

Quality Attributes

Quality at development

Quality at development refers to the internal quality during the build process. While not externally visible, it manifests in how quickly we can deliver and make changes.

Modifiability

How costly and risky is to make changes in software.

Testability

Ease with which we can demonstrate faults. Testable - reveals its faults easily.

Deployability

Ease and time to make a transition of given software change to production. 

Integrability

How costly and risky are the anticipated and unanticipated future integration tasks.

Quality at runtime

Quality at runtime refers to the external quality of the software when it is operational, visible to users through its performance, reliability, and user experience.

Availability

Software is there and ready to carry out its task when one needs it to be.

Performance

Ability to meet timing requirements.

Security

Ability to protect data from unauthorized access while providing data to authorized parties.

Usability

How easy it is for the user to accomplish a desired task.  

Cost Efficiency

Ability to keep the costs low throughout lifecycle of the system.

Environmental Sustainability

Measure of environmental impact throughout lifecycle of the system.



Architecture canvas







Usage and contribution

How to use the guidelines?

https://openwt.atlassian.net/wiki/spaces/DEL/pages/11362533452

 

How to contribute to the guidelines?

https://openwt.atlassian.net/wiki/x/GIBLpQI

 

Rollout plan

The TG architecture deliverables are divided into three steps. The first step guides us through architectural decisions using a checklist of questions. The second step provides answers to these checklists, sharing expertise, insights and recommendations. The third step involves providing tooling and automation for typical scenarios.



Step 1
Checklist

Step 2
Guidelines

Step 3
Automations

Goal

Guides us to quality and speed ensuring key areas considered

Speeds up set up providing default decisions & best practices (knowhow)

Speeds up set up of typical typical projects and chores

Deliverable

Checklist = list of questions to ensure Quality Attributes

Guidelines = list of answers to ensure Quality Attributes

tooling, automations

Change management

In order to streamline the rollout, in the  

Weekly TG Architecture intro Presentation (introduce vision of TG, Quality Definition, Architecture Canvas) 

Organize regular meetings with HODs 

Deep dive presentation

Test the methodology on existing projects

Architecture Canvas monitoring 

Landscape

Checklist and Guidelines live amongst projects and people, serving a clear purpose to fulfill specified quality attributes. The key elements and their relationships are outlined below. 

Quality Attribute is a measurable or testable property of a system that is used to indicate how well the system satisfies the needs of its stakeholders beyond the basic function of the system.

Checklist is composed of questions designed to assess compliance with a given Quality Attribute. For instance, to ensure modifiability in a new project, an architect might consider questions like: “What stack to use for mobile?”, “How to document architecture?”, and “What branching strategy to use?”

Guidelines provide specific answers to these questions, encapsulating our accumulated know-how and best practices. 

Projects in OWT, project bits, templates and external projects are linked directly to relevant guidelines to facilitate easy access to expertise and see the given guideline “in action”.

Stakeholders are individuals or groups who influence, are impacted by, or have an interest in a particular question.

Advocates promote specific guidelines.



https://openwt.atlassian.net/wiki/spaces/~712020f1a74b2daf424243928e3b72e79acc9c/database/11267014770

https://openwt.atlassian.net/wiki/spaces/~712020f1a74b2daf424243928e3b72e79acc9c/database/11266818160





FAQ
- why don’t we use AWS or Azure architecture guidelines? → avoid vendor lock, not covering every aspect.

