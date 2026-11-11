#definition 

summary: defining the terms technical, cognitive and intent debt

technical debt: problems in code
- makes code harder to change
cognitive debt: the team's lack of understanding of the codebase
- makes systems hard to understand 
intent debt: lack of system design goals and constraints
- makes it difficult to know what the system is supposed to do

technical debt
- age old problem, most visible, easiest to deal with 

cognitive debt
- points to the long-term erosion of a team's understanding of the codebase
- "comprehension debt' is similar and it's used to describe how much of ai generated code can be understood
- cognitive debt is not new, what's new is the rate at which GenAI builds it
- experienced through emotions like confusion or lack of confidence in changing software
- understanding unfamilliar code is a taxing activity, so AI-gen code can lead to cognitive surrender: approving ai-gen code with minimal scrutiny
- some ways to mitigate is:
	- treating understanding as a deliverable
	- pair programming
	- human PRs
	- retrospectives when things break
	- reimplementation to help improve understanding 
	- communication during implementatoin, onboarding and offboarding

intent debt
- missing goals and constraints that answer to the "why"
- results from missing plans, docs, specs and tests
- "context debt" with ai often includes intent debt
- ways to avoid:
	- BDD (behavioural driven dev)
	- Architectural design records (ADRs): the what, why  and what not, of a system
	- Domain driven design (DDR): modelling software after  domain concepts
	- agent context artifacts and meeting notes


--- 

the definition of technical debt is initially vaguely definied. the linked citation from Cunningham explains it well: "Shipping first time code is like going into debt" (Cunningham, 1992). the more time spent on the code, you're gooing more and more into debt. the debt is repaid with a rewrite. the context of the article was using objects through Smalltalk, an object oritented langauge, to allow for easier revisions to the code. it was proposed as a balance between waterfall method (expensive, getting it right from the first time) and shipping first time code. 

doesnt really discuss the implications of cognitive debt and intent in terms of studies conducted. i know the paper is introducing new terms, so ofc they wont be discussed in the literature, but even pointing to studies that potentially show pitfalls in software dev and linking them back to cognitive or intent debt would've been nice

otherwise cool paper, enjoyed it!