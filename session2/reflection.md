# Session 2 Reflection

## Q1. How do Issues and pull requests support change control?

An Issue explains why a change is needed and what counts as done. A pull request shows the actual change and lets someone review it before merging. When the PR says "Closes #1", the change is linked to its reason. So anyone can see why a change was made, what was changed, and who checked it.

## Q2. Why did the conflict in Part 4 happen, and how can a team reduce it?

The conflict happened because branch-a and branch-b both started from main and changed the same line in conflict-demo.md differently. Git could not decide which one was correct, so I had to choose. A team can reduce conflicts by pulling often, keeping branches small and short, and talking about who is working on which file.

## Q3. What would be lost if people merged straight into main without a pull request?

There would be no review, so mistakes could go straight into main. There would also be no discussion or record of who approved the change. The link between the change and its Issue would be lost, which makes it hard to trace why something was changed later.
