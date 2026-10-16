# AI-agent
Project Beacon: AI Agent Evaluation

Project Scope:
This project tests how reliably an AI agent can complete a realistic, multi-step business task: writing a two-page monthly status report for senior leadership from meeting notes, a metrics export, last month’s report, and a standards file. All data is fictional. The agent also had to ignore an outdated roadmap and keep a work log of its checks and decisions.

Five traps were planted to test careful reading: 
1. a moved launch date- (Nov 15th vs Dec 1st in the meeting notes)
2. a completion-rate mismatch- (78% in notes vs. 71% in data),
3. an unowned contract risk- (no owner assigned for a approaching deadline project)
4. an unapproved $18k cost- (already used 80% of the budget)
5. a distractor file- (last year's roadmap)

Work Completed:
I designed the task, assembled the context package, wrote the prompts, and ran the agent three times. After each run I reviewed both the report and the work log, then diagnosed each failure as a context, workspace, or instruction problem.

Run 1: Polished but unverified. It invented owners and dates, missed the mismatch, and called the budget “healthy.”
Run 2: Added required checks and no-invention rules. The agent worked from truncated files.
Run 3: Added a completeness check and pasted full contents into the chat. The agent caught the date change and scope growth, with minor errors remaining.

Key Takeaway:
Fixing one lever often exposes the next problem. Work logs make failures traceable.
