# Project Management

## Brainstorm
- Project Lifecycle
	- Design Sprint
		- Identify Must-Have's
		- Identify Overall goal
	- The Product Lead role is architecture (data architecture, development patterns, issue priorities, scrum master)
	- Phase 1 - MVP
		- Goal: Results first
		- Setup CI
		- Working code
		- Acceptable bugs
		- Development patterns are respected but loose
		- The linter can be wrong
		- Should be short with only a handful of features
		- How?
			- Collaboration is key in chaotic environments which is what is happening in this phase
			- Daily push
			- Daily 15-minute meeting to talk about each developers' active branch
			- Weekly code review of particular patterns/snippets
			- Taxonomy for branches and PRs
			- `master` branch is where everyone is merging and branching from
			- `production` branch is customer-ready code only
			- Product Leads need to intervene branches often and aggresively if necessary
			- Product Leads need to do exploratory tests
			- Developers should not waste time testing because features can still change
			- Core functions should be tested
			- Descriptive styles
			- TODO annotations
			- Component Documentation
		- The code needs to have space to evolve
			- if the objective is to show hello world, we can do that with a simple HTML file and present that, then we can figure out how to make it render fast, and after that we can figure out how to scale it
		- At the end of the day, everyone should have accomplished at least one thing
	- Phase 2 - Refactor + Feedback + QA
		- Goal: Make it maintainable and squash bugs


