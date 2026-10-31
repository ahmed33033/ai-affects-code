#review #positive 

How you can integrate AI into different parts of your coding workflow?

`A good dev with AI is more efficient than a good dev without AI`

- Architecture
	- previously: requirements, rough planning in whiteboard, team review, then spec in doc 
	- now: use chatgpt to add your documents and let it design some diagrams for you. "you're the source of truth".
		- If you're adding a feature, you want context, so you CC or cursor
		- **tell ai to challenge you**
- Scaffolding 
	- previously: buy a template, or use a `npm create`
	- now: use app generation tools like v0, lovable, bolt.new, or chef.convex, to create ui that fits your existing code
		- these tools differ by preferred tech stack
		- replit deleted customer database
- Writing code
	- now: ide-based coding assistants like vscode, itellij, zed, or cli like cc, codex, opencode, or browser-based but it got no context 
		- `always review the code`, b/c responsibility is still on you, and commit often
		- auto-completions 
		- assign tasks to ai
- Web scraping: 
	- now: director.ai, prompt in nl 
- Debugging:
	- now: ai writes test cases for you, but you have to tell it the edge cases 
		- let ai `npm run dev` for you, and you break the program
- mcp servers:
	- now: ai connected to your data sources and tools
- code review:
	- prev: you submit pr, ping your teammates on slack and wait for review
	- now: tools like coderabbit and greptile automatically reviewing PR's for you
		- engineers can now focus on the bigger picture
- documentation
	- now: ai can automate it for you, but you need to add the context. ai for the "what", you for the "why"
- git
	- now: let cc run git commands for you
- api development
	- now: cc can create api's for you matching your spec, they're better with edge-cases. 
- SQL development
	- now: cc is pretty good at sql
- Devops and deployment 
	- now: ai can write yaml files for you. but you need to review it like your job depends on ti
- security and monitoring:
	- now: author mentions that best ai tools are ones that take an existing tool and improve it. codeql is an example, and it helps give you a human explanation for the error

general pitfalls:
- skills atrophy: getting worse at something,
- ai introducing bugs, so always review
- pick up one skill at a time

---
nice overview of the different ways AI is used. liked that he broke down all the different parts of software dev. a lot of them seem to resolve to just using CC to do the job, but there are some specific tools mentioned

crazy how he mentioned using cc to commit and push. why? isn't that a simple 2 liner?

i also like how we emphasized some stages need more of a careful review than others. CI/CD and deployment being one. he also mentioned that code reviews cant be automated. 