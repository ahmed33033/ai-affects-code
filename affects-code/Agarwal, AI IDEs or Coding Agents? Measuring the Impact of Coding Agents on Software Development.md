#velocity #coding-agents #ide #code-quality
summary: the effect of coding agents on velocity and code quality, and the difference in the aforementioned when compared to folks who used AI IDEs and folks who didnt'

makes the case that coding agent form a significant difference from AI in IDE's. The latter was studied, but the former needs to be studied some more. coding agents are presented as more autonomous and submitting larger changes

method: uses the "AIDev" dataset, and an agent submitted PR as explicit evidence of using coding agents.

they scan for "ide first" repos by looking at the most recent commit on a monthly basis

i didnt understand some of their methods section around propensity scores

they found about an 18% rise in static analysis warnings and 37% in cognitive complexity for all IDE-AI assisted and Coding agent repos. these numbers are from sonarqube.

they didnt find a substantial benefit for folks using AI-assisted IDEs when they upgraded coding agents.

---

using an AI generated PR as evidence of coding agents is poor imo.  coding agents development can happen locally and not necessarily using git, or make PRs. 

also AI generated PR is a poor signal and doesn't include the depth of coding agents use. example: just using coding rabbit vs full on cc max

just looking at the most recent commit for AI-IDE usage? crazy

by get a look at some sonarqube stats for code quality?

i didnt like the paper that much. doesnt really apply much to my rq, but it at least it helps give me a mental difference between IDE's with AI assistance and coding agents that are more autonomous 