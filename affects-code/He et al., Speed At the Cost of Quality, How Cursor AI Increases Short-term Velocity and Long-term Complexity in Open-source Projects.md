#difference-in-differences #longitudinal

summary: using cursor improved velocity in the short-term (3x-5x), but that slowed down after 2 motnhs. statistic warnings increased by 30%, and code complexity by 41%. 
	- the link? technical debt slows down velocity, in a self-enforcing cycle

they select repositories for the study by looking at which repos have a cursor files vs which dont. problem here is that the folks that they dont detect other uses of ai... so the comparison isn't ai vs no ai, its cursor vs maybe no cursor. 
- they peform "robustness" checks to check repos did really use cursor, and they found stronger effects
- they use propensity scores to match treatment and not treated (no cursor) repos

commits and lines added are used as measures of productivity, which is i dont like but it correlates with perceived productivity (no wonder).

they measure the interaction between code quality and complexity with number of commits and lines added. they suggest a self-fueling cycle betwen tehm, but that it can't be the only reason. so they suggest that it may be a: novelty: frustration, abondonment cycle happening with them

code quality is not scaling with lines of code generation. cursor may not necessarily introduce more code quality issues, except for complexity, which was particularly evident 

--- 

ok this is a cool study but it comes with a good bit of disclaimers:

claim: cursor leads to transient velocity increases

explanations:
- cursor adds many lines, leading to a bigger codebase, leading to more "technical debt", in the form of more code quality issues. this slows down velocity
	- disclaimer: ai may not necessarily introduce more code quality issues than project w/o cursor with same velocity. 
	- disclaimer 2: code complexity is a code quality issue of particular concern, and the study suggests cursor increases complexity even after accounting for increased velocity. they call this "complexity debt"
	- disclaimer 3: technical debt is not the only cause of decreased velocity. the authors of the paper suggest that it could be "novelty, frustration abondenment" cycle, esp since they used open soruce repos in their data, and they weren't focused on enterprise
	- disclaimer 4: their study is form late 2024 to mid 2025

practical implicatoins:
- quality assurance should scale with code generation