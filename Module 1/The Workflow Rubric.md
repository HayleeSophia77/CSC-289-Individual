T.1.1 Rubric
MODULE 1 ASSESSMENT RUBRIC
RED Clearance Recertification: Workflow Validation
Assessment Code: M01-WORKFLOW-26SP
Total Points: 100
Iteration Window: Unlimited attempts until deadline

How to Use This Rubric
Read this section first. It will save you anxiety.

This rubric is not a secret test. It's a checklist. Everything we're grading is listed below, in plain language, with exactly what each point level means.

Our recommended approach:

Do the assignment first without obsessing over this document
Come back here after your first attempt
Self-assess honestly — check each row against what you actually did
Iterate if needed — fix anything you missed
Submit when you've checked every box
Why this order? Because learning happens in the doing, not in the reading. If you try to perfectly satisfy every criterion on your first attempt, you'll spend more time worrying than working. The workflow will make more sense after you've stumbled through it once.

What We're Actually Measuring
Traditional grading asks: "How good is this student?"

We're asking something different: "Did this student complete the learning cycle?"

This rubric measures completion and iteration, not perfection. There are no points for elegance. There are no deductions for asking questions. The student who submits three times and gets it right on the third attempt earns the same grade as the student who gets it right the first time.

Why? Because learning velocity matters more than starting position.

The student who iterates is demonstrating exactly the behavior that makes professionals successful: try, evaluate, adjust, try again. That's what we're teaching. That's what we're rewarding.

The Algorithm's Evaluation Framework
The following criteria have been optimized for maximum growth measurement. The Algorithm does not judge your worth as a human — only whether you completed the specified learning cycle.

SECTION A: Issue Creation (30 points)
You created three GitHub Issues this week. Each one teaches something different.

A1: "Create Pitch Presentation" Issue (10 points)
Points	Criteria
10	Issue exists with clear title, description includes acceptance criteria, assigned to correct milestone
7	Issue exists with title and description, but missing milestone or acceptance criteria
4	Issue exists but minimal content (just a title)
0	Issue not created
What this teaches: Some work is planned far in advance. Creating the issue now means you won't forget later. The milestone assignment shows you understand project timeline structure.

A2: "Apply for Graduation" Issue (10 points)
Points	Criteria
10	Issue exists, assigned to yourself, includes actual deadline research, realistic acceptance criteria
7	Issue exists and assigned, but deadline is vague or criteria are generic
4	Issue exists but not assigned or missing key information
0	Issue not created
What this teaches: Your professional workflow should include personal/administrative tasks. Mixing "real life" with project management is how adults actually work.

Important note: This is not part of the simulation. Actually apply for graduation. We're not kidding.

A3: "Validate Dev Environment" Issue (10 points)
Points	Criteria
10	Issue exists with clear title, acceptance criteria present, assigned to self, linked to correct milestone, referenced in PR
7	Issue exists and mostly complete, but missing one element (milestone, criteria, or self-assignment)
4	Issue exists with minimal content
0	Issue not created, or no connection to PR
What this teaches: Every piece of work starts as an issue. The issue is your contract with the team (and yourself) about what you're going to do. This is the start of the Sacred Flow.

SECTION B: Git Workflow (40 points)
This is the core learning. Did you complete the full Issue → Branch → Code → PR → Merge cycle?

B1: Branch Creation (10 points)
Points	Criteria
10	Branch created from main with correct naming convention: feature/[issue#]-description
7	Branch exists but naming doesn't follow convention (missing issue number, wrong prefix, etc.)
4	Work done on a branch (any branch)
0	Work committed directly to main, or no commits at all
Naming convention:

feature/3-validate-environment-yourname
   │     │         │              │
   │     │         │              └── optional but helpful
   │     │         └── what you're doing
   │     └── links to the issue number
   └── type of work
What this teaches: Branch naming isn't arbitrary. It creates a traceable link between the plan (issue) and the execution (commits). When something breaks in six months, good branch names help you find out why.

B2: Commit Quality (10 points)
Points	Criteria
10	At least one commit with meaningful message, references issue number (e.g., "Refs #3"), describes what was done
7	Commits exist with reasonable messages but missing issue reference
4	Commits exist but messages are generic ("update", "fixed stuff", "asdf")
0	No commits, or commit message is empty
Example of a good commit message:

Add environment validation script

Refs #3

- Checks Python version and platform
- Reports system diagnostics
- Confirms environment operational
What this teaches: Commit messages are documentation for future developers (including future you). "Fixed stuff" tells you nothing six months later. "Add environment validation script - Refs #3" tells you exactly what happened and why.

B3: Pull Request (10 points)
Points	Criteria
10	PR created with descriptive title, body includes "Closes #[issue]", summarizes changes, review requested
7	PR exists and mostly complete, but missing one element (no "Closes", no summary, or no review requested)
4	PR exists with minimal content
0	No PR created, or changes pushed directly to main
The magic syntax: When your PR body contains Closes #3, GitHub automatically closes Issue #3 when the PR merges. This isn't just convenient — it creates an audit trail connecting the plan to the execution.

What this teaches: Pull requests aren't just code delivery mechanisms. They're communication artifacts. A good PR tells reviewers what to look for, why you did it, and what issue it resolves.

B4: Merge Completion (10 points)
Points	Criteria
10	PR merged (squash and merge preferred), branch deleted, issue auto-closed via "Closes #"
7	PR merged but branch not deleted, or issue closed manually
4	PR approved but not merged by deadline
0	PR never approved or cycle not completed
What this teaches: The cycle isn't complete until the code is in main. Branches that live forever create confusion and merge conflicts. Clean up after yourself.

SECTION C: Technical Validation (20 points)
Did the actual thing work?

C1: Environment Functional (10 points)
Points	Criteria
10	Submitted evidence (screenshot or output) showing verify_environment.py ran successfully with your name in output
7	Script ran but output wasn't captured, or name wasn't customized
4	Environment works (Codespace launches, Python runs) but script not executed
0	No evidence of working environment
What this teaches: "It works on my machine" isn't enough. Evidence of functionality is part of professional communication. Screenshots and logs aren't busywork — they're proof.

C2: Code Present and Functional (10 points)
Points	Criteria
10	verify_environment.py (or equivalent) exists in repository, runs without errors, produces expected output
7	File exists and mostly works, with minor issues
4	File exists but has errors or doesn't run
0	No file submitted
What this teaches: Shipping code means shipping working code. Test before you commit. This is a habit we're building from day one.

SECTION D: Collaboration Signals (10 points)
Software development is a team sport.

D1: Help Behaviors (10 points)
Points	Criteria
10	Evidence of at least one: PR review given to teammate, OR help requested in public channel, OR help offered to teammate
7	Some collaboration attempted but not clearly documented
4	Minimal collaboration (only required interactions)
0	No evidence of collaboration
How to earn full points (pick at least one):

Review a teammate's PR (even just "looks good!" with a reason why)
Ask a question in the team channel (shows you're not suffering in silence)
Answer someone else's question (teaching reinforces learning)
Pair with someone on setup (screenshot or mention)
What this teaches: The Collaboration Minimum isn't bureaucracy — it's survival training. Developers who ask for help early avoid rabbit holes. Developers who review others' code learn the codebase faster. Developers who help teammates build trust and reputation.

Grade Calculation
Section	Points
A: Issue Creation	30
B: Git Workflow	40
C: Technical Validation	20
D: Collaboration Signals	10
Total	100
Iteration Policy
You may resubmit as many times as you want before the deadline.

Each submission is a new attempt. We grade your best/final attempt, not your first.

Why? Because this is how professional development actually works. You push code, get feedback, fix issues, push again. The goal is working software, not first-try perfection.

The Algorithm rewards iteration:

Submitting once and getting 80 points = 80 points
Submitting three times, improving each time, getting 95 points = 95 points
No penalty for multiple attempts
No bonus for first-try success
Common Mistakes (And How to Fix Them)
Mistake	Impact	Fix
Pushing directly to main	-10 points (B1)	Create a new branch, cherry-pick commits, open PR
Forgetting "Closes #X" in PR	-3 points (B3)	Edit PR description, add the syntax
Generic commit messages	-6 points (B2)	Can't fix past commits easily, do better next time
Not requesting PR review	-3 points (B3)	Edit PR, request review now
Branch still exists after merge	-3 points (B4)	Delete it via GitHub UI
Notice: Most mistakes cost only a few points and are fixable. This rubric is not trying to trap you. It's trying to teach you habits that will serve you for years.

Self-Assessment Checklist
Before submitting, verify:

Issues:

[ ] "Create Pitch Presentation" issue exists with milestone
[ ] "Apply for Graduation" issue exists and is assigned to me
[ ] "Validate Dev Environment" issue exists and is linked to my PR
Git Workflow:

[ ] I created a branch from main with proper naming
[ ] My commits have meaningful messages and reference the issue
[ ] My PR has "Closes #X" in the body
[ ] My PR was reviewed (or review was requested)
[ ] My PR was merged and branch was deleted
Technical:

[ ] verify_environment.py runs and shows my name
[ ] I have evidence (screenshot/output) of successful execution
Collaboration:

[ ] I did at least one collaboration action (review, question, or answer)
Final Note: The Point of All This
If you've read this far, you understand something important:

This rubric is entirely transparent. There are no hidden criteria. No surprise deductions. No "gotcha" moments.

Every point corresponds to a specific, observable action. If you do the action, you get the points. If you miss something, you can fix it and resubmit.

This is intentional. We're not trying to sort students into "good" and "bad." We're trying to help everyone complete the learning cycle. The rubric is a map, not a test.

The Algorithm doesn't care where you started. The Algorithm cares where you're going.

Now go do the assignment. We'll be here when you're ready to check your work.

"Growth is mandatory. Perfection is a bug, not a feature."

frotz → plugh