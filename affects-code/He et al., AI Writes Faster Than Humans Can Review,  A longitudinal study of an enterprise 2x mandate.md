#enterprise #longitudinal #code-reviews 

summary: the paper tracks a b2b company with a cto that announced a 2x PR mandate with the power of ai. they ask 3 questoins:
1. can they do it
	1. yes they can
		1. heavier use of AI led to more PRs
2. is ai adoption uniform
	1. yes generally but manager adopted ai a lot more, meaning they could now ship code more readily
3. how they dealt with additional throughput, and how it affects review and code quality
	1. ai authored PRs become 90% of total prs
	2. num of PRs grew 3x while devs only grew 1.5x
	3. automated merge requests grew
	4. the load on reviewers doubled
	5. the paper did pick up a PR review bottleneck, but mentioned ai-approved prs can change this

--- 

## the company mentioned in the paper

The company discussed in the paper is suspected to be fin, previously intercom.

In an interview with Brian Scanlan, an engineer at fin, he mentioned the 2x PR mandate that his company reached after 9 months, after the CTO made an announcement, which matches with the company details revealed in the paper. 

fin is a customer service ai bot.

On fin's website, they show a 7% increase in customer service resolution from june 2025, to april 2026, the 9 month period mentioned in paper. if you take the same time period before june 2025, they achieved a 13% to 16% increase in customer service resolution

## adjacent skills

the authors mentions the need to develop adjacent skills when shifting work. they give the example of IT teams having to develop different workflows and pick up new skills to see good gains.

anthropic and openai recently shared news stories of building a scalable git. this shows that added code resulting in added demand for PRs meant many downsteam dev tasks need to shapeshift to meet them.

this is a good place to step back and realize the whoole product cycle. going from customer pain-point to observation, study, prototype, test, prototype, execution, testing, PR, merge, release, and maintainence. speeding up execution means speeding up testing, PR reviews, merges, releases and maintainence tasks. the value proposition, however, is not necessarily going up b/c that is drived by solving the customer pain point. 

