# practice_repo

Good 👍 — now I fully understand your frustration.

You **don’t want explanation**.
You want:

✅ **ONLY Git Branch Strategy**
✅ **Step-by-step practice**
✅ Like real company workflow
✅ What to do → command → action → next action
✅ Practice until muscle memory

Perfect.
Now I will train you **exactly like company onboarding**.

---

# 🚀 REAL COMPANY GIT PRACTICE (STEP-BY-STEP)

From now:

👉 You are **DevOps Engineer**
👉 Repo already created
👉 Developers working
👉 You must manage Git flow

---

# ✅ STEP 0 — Create Practice Repository

Create empty repo:

```
enterprise-git-practice
```

Clone:

```bash
git clone https://github.com/yourname/enterprise-git-practice.git
cd enterprise-git-practice
```

---

# ✅ STEP 1 — Company Branch Strategy (YOU CREATE)

You MUST create **5 branches**.

## 🎯 Target Structure

```
main
develop
release
feature/*
hotfix/*
```

---

## ✅ Create main branch

```bash
git checkout -b main
```

Create file:

```bash
touch README.md
git add .
git commit -m "Initial commit"
git push origin main
```

✅ Production branch ready.

---

# ✅ STEP 2 — Create DEVELOP Branch

Company rule:

> All development happens in develop

```bash
git checkout -b develop
git push origin develop
```

✅ Integration environment ready.

---

# ✅ STEP 3 — Developer Starts Feature (REAL PRACTICE)

### Ticket:

```
DEV-101: Create login feature
```

You simulate developer work.

---

Create feature branch:

```bash
git checkout develop
git checkout -b feature/login-service
```

Create files:

```
login.py
config.yaml
Dockerfile
```

Commands:

```bash
touch login.py config.yaml Dockerfile
```

Commit:

```bash
git add .
git commit -m "Added login service"
git push origin feature/login-service
```

✅ Developer finished work.

---

# ✅ STEP 4 — Pull Request Simulation (IMPORTANT)

NOW REAL COMPANY FLOW.

Feature **cannot go directly to main**.

Merge → develop.

---

Switch:

```bash
git checkout develop
```

Merge:

```bash
git merge feature/login-service
```

Push:

```bash
git push origin develop
```

✅ DEV environment deployment triggered.

---

# ✅ STEP 5 — Create SECOND FEATURE (Practice Again)

Ticket:

```
DEV-102: Payment Service
```

---

```bash
git checkout develop
git checkout -b feature/payment-service
```

Create:

```bash
mkdir payment
touch payment/app.py
```

Commit:

```bash
git add .
git commit -m "Payment service added"
git push origin feature/payment-service
```

Merge again:

```bash
git checkout develop
git merge feature/payment-service
git push origin develop
```

---

# ✅ STEP 6 — Release Branch Creation (VERY IMPORTANT)

Company decision:

> Move DEV → UAT testing

Create release branch:

```bash
git checkout develop
git checkout -b release/v1.0
git push origin release/v1.0
```

✅ UAT environment ready.

---

# ✅ STEP 7 — BUG FOUND IN UAT

Ticket:

```
BUG-201: Payment crash
```

Fix inside release branch.

---

```bash
git checkout release/v1.0
```

Edit file.

Commit:

```bash
git add .
git commit -m "Bug fix payment issue"
git push origin release/v1.0
```

✅ UAT fixed.

---

# ✅ STEP 8 — Production Deployment

Client approved ✅

Merge release → main

```bash
git checkout main
git merge release/v1.0
git push origin main
```

🔥 Production deployed.

---

# ✅ STEP 9 — Production Emergency (HOTFIX)

REAL COMPANY MOST IMPORTANT STEP 🚨

Ticket:

```
PROD-501: Login failure in production
```

---

Create hotfix from main:

```bash
git checkout main
git checkout -b hotfix/login-fix
```

Fix issue.

```bash
git add .
git commit -m "Hotfix login issue"
git push origin hotfix/login-fix
```

---

Merge BACK to main:

```bash
git checkout main
git merge hotfix/login-fix
git push origin main
```

---

VERY IMPORTANT ⚠️
Also merge to develop:

```bash
git checkout develop
git merge hotfix/login-fix
git push origin develop
```

✅ Sync completed.

---

# ✅ FINAL COMPANY FLOW (MEMORIZE)

```
feature → develop
develop → release
release → main
hotfix → main + develop
```

---

# 🧠 REAL PRACTICE RULE (DO THIS 3 TIMES)

Repeat complete cycle:

✅ Create feature
✅ Merge develop
✅ Create release
✅ Fix bug
✅ Deploy main
✅ Hotfix

Do again with:

```
feature/cart
feature/order
feature/search
```

---

# 🔥 AFTER THIS YOU WILL KNOW

✅ Git like real engineer
✅ PR flow
✅ Release management
✅ Production fix handling
✅ Enterprise Git workflow

---

## ⭐ NEXT LEVEL PRACTICE (VERY POWERFUL)

Next I can give you:

✅ **Daily Git Company Tasks**
(example:)

```
Day 2:
Developer deleted file accidentally.
Recover using git.
```

```
Day 3:
Wrong commit pushed to main.
Fix without history loss.
```

```
Day 4:
Release rollback required.
```

---

Say:

👉 **"Give me Git real company daily tasks"**

and I’ll make you **industry-ready Git expert**.
Good 👍 — now I fully understand your frustration.

You **don’t want explanation**.
You want:

✅ **ONLY Git Branch Strategy**
✅ **Step-by-step practice**
✅ Like real company workflow
✅ What to do → command → action → next action
✅ Practice until muscle memory

Perfect.
Now I will train you **exactly like company onboarding**.

---

# 🚀 REAL COMPANY GIT PRACTICE (STEP-BY-STEP)

From now:

👉 You are **DevOps Engineer**
👉 Repo already created
👉 Developers working
👉 You must manage Git flow

---

# ✅ STEP 0 — Create Practice Repository

Create empty repo:

```
enterprise-git-practice
```

Clone:

```bash
git clone https://github.com/yourname/enterprise-git-practice.git
cd enterprise-git-practice
```

---

# ✅ STEP 1 — Company Branch Strategy (YOU CREATE)

You MUST create **5 branches**.

## 🎯 Target Structure

```
main
develop
release
feature/*
hotfix/*
```

---

## ✅ Create main branch

```bash
git checkout -b main
```

Create file:

```bash
touch README.md
git add .
git commit -m "Initial commit"
git push origin main
```

✅ Production branch ready.

---

# ✅ STEP 2 — Create DEVELOP Branch

Company rule:

> All development happens in develop

```bash
git checkout -b develop
git push origin develop
```

✅ Integration environment ready.

---

# ✅ STEP 3 — Developer Starts Feature (REAL PRACTICE)

### Ticket:

```
DEV-101: Create login feature
```

You simulate developer work.

---

Create feature branch:

```bash
git checkout develop
git checkout -b feature/login-service
```

Create files:

```
login.py
config.yaml
Dockerfile
```

Commands:

```bash
touch login.py config.yaml Dockerfile
```

Commit:

```bash
git add .
git commit -m "Added login service"
git push origin feature/login-service
```

✅ Developer finished work.

---

# ✅ STEP 4 — Pull Request Simulation (IMPORTANT)

NOW REAL COMPANY FLOW.

Feature **cannot go directly to main**.

Merge → develop.

---

Switch:

```bash
git checkout develop
```

Merge:

```bash
git merge feature/login-service
```

Push:

```bash
git push origin develop
```

✅ DEV environment deployment triggered.

---

# ✅ STEP 5 — Create SECOND FEATURE (Practice Again)

Ticket:

```
DEV-102: Payment Service
```

---

```bash
git checkout develop
git checkout -b feature/payment-service
```

Create:

```bash
mkdir payment
touch payment/app.py
```

Commit:

```bash
git add .
git commit -m "Payment service added"
git push origin feature/payment-service
```

Merge again:

```bash
git checkout develop
git merge feature/payment-service
git push origin develop
```

---

# ✅ STEP 6 — Release Branch Creation (VERY IMPORTANT)

Company decision:

> Move DEV → UAT testing

Create release branch:

```bash
git checkout develop
git checkout -b release/v1.0
git push origin release/v1.0
```

✅ UAT environment ready.

---

# ✅ STEP 7 — BUG FOUND IN UAT

Ticket:

```
BUG-201: Payment crash
```

Fix inside release branch.

---

```bash
git checkout release/v1.0
```

Edit file.

Commit:

```bash
git add .
git commit -m "Bug fix payment issue"
git push origin release/v1.0
```

✅ UAT fixed.

---

# ✅ STEP 8 — Production Deployment

Client approved ✅

Merge release → main

```bash
git checkout main
git merge release/v1.0
git push origin main
```

🔥 Production deployed.

---

# ✅ STEP 9 — Production Emergency (HOTFIX)

REAL COMPANY MOST IMPORTANT STEP 🚨

Ticket:

```
PROD-501: Login failure in production
```

---

Create hotfix from main:

```bash
git checkout main
git checkout -b hotfix/login-fix
```

Fix issue.

```bash
git add .
git commit -m "Hotfix login issue"
git push origin hotfix/login-fix
```

---

Merge BACK to main:

```bash
git checkout main
git merge hotfix/login-fix
git push origin main
```

---

VERY IMPORTANT ⚠️
Also merge to develop:

```bash
git checkout develop
git merge hotfix/login-fix
git push origin develop
```

✅ Sync completed.

---

# ✅ FINAL COMPANY FLOW (MEMORIZE)

```
feature → develop
develop → release
release → main
hotfix → main + develop
```

---

# 🧠 REAL PRACTICE RULE (DO THIS 3 TIMES)

Repeat complete cycle:

✅ Create feature
✅ Merge develop
✅ Create release
✅ Fix bug
✅ Deploy main
✅ Hotfix

Do again with:

```
feature/cart
feature/order
feature/search
```

---

# 🔥 AFTER THIS YOU WILL KNOW

✅ Git like real engineer
✅ PR flow
✅ Release management
✅ Production fix handling
✅ Enterprise Git workflow

---

## ⭐ NEXT LEVEL PRACTICE (VERY POWERFUL)

Next I can give you:

✅ **Daily Git Company Tasks**
(example:)

```
Day 2:
Developer deleted file accidentally.
Recover using git.
```

```
Day 3:
Wrong commit pushed to main.
Fix without history loss.
```

```
Day 4:
Release rollback required.
```

---

Say:

👉 **"Give me Git real company daily tasks"**

Perfect 👍
Now we move to **REAL DEVOPS / SENIOR GIT ENGINEER PRACTICE**.

⚠️ This is **exact company-level training**.
Do **step-by-step in terminal**.
Do NOT skip steps.

You will practice **6 critical real-world Git situations**.

---

# 🚀 PRACTICE 1 — WRONG COMMIT PUSHED TO MAIN

## 🎫 Scenario

Developer pushed test code directly to `main`.

Production affected.

---

## ✅ Step 1 — Go main

```bash
git checkout main
git pull origin main
```

---

## ✅ Step 2 — Simulate mistake

```bash
echo "BAD CODE" >> production.txt
git add .
git commit -m "mistake commit"
git push origin main
```

🚨 Production broken.

---

## ✅ Step 3 — Fix SAFELY (Company Method)

See commits:

```bash
git log --oneline
```

Example:

```
abc123 mistake commit
195d439 stable commit
```

---

Rollback:

```bash
git revert abc123
```

Push:

```bash
git push origin main
```

✅ Production restored
✅ History safe
✅ Team unaffected

---

# 🚀 PRACTICE 2 — DELETED BRANCH RECOVERY

## 🎫 Scenario

Developer deleted feature branch accidentally.

---

Delete branch:

```bash
git branch -D feature/login-v2
```

😈 Code gone locally.

---

## ✅ Recover using reflog

```bash
git reflog
```

Output example:

```
9f0c372 HEAD@{2}: commit: feature modification
```

---

Recover:

```bash
git checkout -b feature/login-v2 9f0c372
```

Push again:

```bash
git push origin feature/login-v2
```

✅ Branch recovered.

---

# 🚀 PRACTICE 3 — RECOVER LOST CODE

## 🎫 Scenario

Developer ran hard reset 😱

Simulate:

```bash
git reset --hard HEAD~1
```

Commit disappears.

---

## ✅ Recovery

```bash
git reflog
```

Find lost commit:

```
260de0c
```

Restore:

```bash
git reset --hard 260de0c
```

✅ Code restored.

---

# 🚀 PRACTICE 4 — CHERRY-PICK HOTFIX (VERY IMPORTANT)

## 🎫 Scenario

Bug fixed in develop.
Production needs ONLY that fix.

---

Go develop:

```bash
git checkout develop
```

Create fix:

```bash
echo "critical fix" >> fix.txt
git add .
git commit -m "critical hotfix"
```

Copy commit id.

---

Go production:

```bash
git checkout main
```

Apply ONLY that commit:

```bash
git cherry-pick COMMIT_ID
```

Push:

```bash
git push origin main
```

✅ Only fix moved to production.

🔥 Used daily in companies.

---

# 🚀 PRACTICE 5 — REBASE WORKFLOW (FAANG STYLE)

Companies prefer clean history.

---

Create feature:

```bash
git checkout develop
git checkout -b feature/search
```

Commit:

```bash
echo "search1" >> search.txt
git add .
git commit -m "search step1"
```

---

Meanwhile develop updated:

```bash
git checkout develop
echo "update" >> update.txt
git commit -am "develop update"
```

---

Now rebase feature:

```bash
git checkout feature/search
git rebase develop
```

✅ Feature moved on latest develop.

Push safely:

```bash
git push --force-with-lease
```

(Not normal force push)

---

# 🚀 PRACTICE 6 — SQUASH COMMITS (CLEAN PR)

Bad history:

```
fix typo
fix again
update
minor fix
```

---

Run:

```bash
git rebase -i HEAD~4
```

Editor opens:

```
pick
pick
pick
pick
```

Change to:

```
pick
squash
squash
squash
```

Save.

Now:

```
Single clean commit ✅
```

---

# 🚀 PRACTICE 7 — PR APPROVAL SIMULATION

Feature completed.

---

Push feature:

```bash
git push origin feature/search
```

---

Simulate review:

```
feature/search → develop
```

Merge locally:

```bash
git checkout develop
git merge --no-ff feature/search
git push origin develop
```

✅ PR approved workflow.

---

# 🧠 WHAT YOU JUST PRACTICED

You now know:

✅ Production rollback
✅ Branch recovery
✅ Lost commit restore
✅ Hotfix deployment
✅ FAANG rebase flow
✅ Clean PR history
✅ Enterprise merge strategy

This equals **2–3 years Git experience**.

---

# 🔥 NEXT (ULTRA REAL)

Next I can simulate:

✅ Multiple developers conflict war
✅ Production release freeze
✅ Emergency midnight hotfix
✅ Git strategy used in Amazon
✅ DevOps interview live scenarios

Say:

👉 **"Give me DevOps real company simulation"**

and we’ll run you like **working engineer**.
Excellent 👍
Now we start **REAL DEVOPS COMPANY SIMULATION**.

From this point ❗
I will behave like **DevOps Manager**
You are **DevOps Engineer (L2)** working in company.

No theory.
Only **REAL WORK + REAL INCIDENTS**.

---

# 🏢 COMPANY SIMULATION START

**Company:** TechNova Pvt Ltd
**Product:** E-Commerce Platform
**Users:** 2 Million/day
**Infra:** Git + Docker + Kubernetes + Jenkins

You are responsible for:

✅ Git workflow
✅ Deployment
✅ Release
✅ Hotfix
✅ Production stability

---

# 📅 DAY-1 — MORNING (9:30 AM)

## 🎫 Ticket: DEVOPS-401

> Developers completed 3 features.
> Prepare DEV integration deployment.

Features ready:

```
feature/cart-service
feature/payment-v3
feature/order-service
```

---

# ✅ TASK 1 — Create Features (Simulate Developers)

---

## Developer 1

```bash
git checkout develop
git checkout -b feature/cart-service
```

```bash
mkdir cart
echo "cart service" > cart/cart.py
```

```bash
git add .
git commit -m "DEV: cart service added"
git push origin feature/cart-service
```

---

## Developer 2

```bash
git checkout develop
git checkout -b feature/payment-v3
```

```bash
mkdir payment_v3
echo "payment v3" > payment_v3/pay.py
```

```bash
git add .
git commit -m "DEV: payment v3"
git push origin feature/payment-v3
```

---

## Developer 3

```bash
git checkout develop
git checkout -b feature/order-service
```

```bash
mkdir order
echo "order service" > order/order.py
```

```bash
git add .
git commit -m "DEV: order service"
git push origin feature/order-service
```

---

# 🧑‍💻 YOUR ROLE — DEVOPS ENGINEER

You must integrate all.

---

# ✅ TASK 2 — Merge to DEVELOP

```bash
git checkout develop
```

Merge one by one:

```bash
git merge feature/cart-service
git merge feature/payment-v3
git merge feature/order-service
```

Push:

```bash
git push origin develop
```

✅ DEV environment ready.

---

# 🚨 DAY-1 — AFTERNOON INCIDENT (2 PM)

## Ticket: INCIDENT-778

QA reports:

```
Payment service crashing in DEV
```

---

# ✅ TASK 3 — Create Fix Branch

Never fix directly.

```bash
git checkout develop
git checkout -b bugfix/payment-crash
```

Fix:

```bash
echo "bug fixed" >> payment_v3/pay.py
```

Commit:

```bash
git add .
git commit -m "BUGFIX: payment crash resolved"
git push origin bugfix/payment-crash
```

---

Merge back:

```bash
git checkout develop
git merge bugfix/payment-crash
git push origin develop
```

✅ DEV stable.

---

# 📅 DAY-2 — RELEASE PREPARATION

Manager says:

> Prepare UAT Release v3.0

---

# ✅ TASK 4 — Create Release Branch

```bash
git checkout develop
git checkout -b release/v3.0
git push origin release/v3.0
```

✅ UAT deployment triggered.

---

# 🚨 DAY-2 NIGHT INCIDENT 😈

Production running old version.

Client reports:

```
Login security vulnerability
FIX IMMEDIATELY
```

---

# ✅ TASK 5 — HOTFIX (MOST IMPORTANT)

Hotfix ALWAYS from main.

```bash
git checkout main
git checkout -b hotfix/security-login
```

Fix:

```bash
echo "security patch" >> login.py
```

Commit:

```bash
git add .
git commit -m "HOTFIX: login security patch"
git push origin hotfix/security-login
```

---

Merge to production:

```bash
git checkout main
git merge hotfix/security-login
git push origin main
```

---

🔥 VERY IMPORTANT STEP

Sync develop:

```bash
git checkout develop
git merge hotfix/security-login
git push origin develop
```

✅ All environments aligned.

---

# 🚨 DAY-3 — PRODUCTION FAILURE

Deployment broke system.

Manager:

> Rollback immediately!

---

# ✅ TASK 6 — Production Rollback

Check:

```bash
git log --oneline
```

Find previous stable commit.

Rollback safely:

```bash
git revert BAD_COMMIT_ID
git push origin main
```

✅ Production restored.

---

# 🧠 WHAT YOU EXPERIENCED

You just simulated:

✅ Multi-developer workflow
✅ Integration management
✅ Bugfix lifecycle
✅ Release management
✅ Emergency hotfix
✅ Production rollback

This = **Real DevOps Job**.

---

# ⭐ NEXT LEVEL SIMULATION (DAY-4)

Next we simulate:

🔥 Jenkins pipeline failure
🔥 Deployment stuck
🔥 Kubernetes pod crash
🔥 Midnight production call
🔥 Manager escalation

Say:

👉 **"Start Day-4 Production Incident Simulation"**

Now you are training like **actual DevOps engineer**, not learner.


hi





hjh



✅ What you practiced already = 70–80% of Git used in real DevOps jobs
❌ But NOT fully enough yet for production-level mastery.

There are still critical Git skills DevOps engineers MUST know.

I’ll now give you FINAL GIT PRACTICE ROADMAP (REAL INDUSTRY LEVEL).

No theory — only practice missions.

🚀 DEVOPS GIT — COMPLETE PRACTICE LIST

You already learned ✅

Branch strategy

Merge

Rebase

Conflict resolve

Rollback

Hotfix

Cherry-pick

Now practice ADVANCED REAL CASES.

🔥 PRACTICE 1 — ACCIDENTAL FORCE PUSH RECOVERY
Scenario

Developer destroyed history.

Simulate:

git checkout develop
git reset --hard HEAD~3
git push --force

😈 Repo history broken.

Recover
git reflog

Find old commit.

Restore:

git reset --hard COMMIT_ID
git push --force-with-lease

✅ Production saved.

🔥 PRACTICE 2 — REMOVE SECRET FROM GIT HISTORY

REAL COMPANY ISSUE.

Accidentally committed password.

Create leak:

echo "AWS_SECRET=123456" >> secret.txt
git add .
git commit -m "secret added"
git push

Remove completely:

git filter-branch --force --index-filter \
'git rm --cached --ignore-unmatch secret.txt' \
--prune-empty --tag-name-filter cat -- --all

Push clean history:

git push origin --force --all

🔥 Very real DevOps task.

🔥 PRACTICE 3 — FIND WHO CHANGED FILE

Manager asks:

Who broke config yesterday?

Run:

git blame config.yaml

or

git log config.yaml

✅ Identify developer instantly.

🔥 PRACTICE 4 — PARTIAL COMMIT (PRO LEVEL)

Only commit selected lines.

Edit file.

Then:

git add -p

Choose lines interactively.

Used daily by seniors.

🔥 PRACTICE 5 — STASH WORK (VERY COMMON)

Emergency hotfix arrives.

Save unfinished work:

git stash

Switch branch:

git checkout main

Later restore:

git stash pop
🔥 PRACTICE 6 — TAG RELEASE VERSION

Production releases always tagged.

git tag -a v3.0 -m "Production release"
git push origin v3.0

Companies deploy using tags.

🔥 PRACTICE 7 — DETACHED HEAD RECOVERY

Simulate:

git checkout COMMIT_ID

Now you're detached.

Fix:

git checkout -b recovery-branch
🔥 PRACTICE 8 — CLEAN BAD COMMITS BEFORE PR
git rebase -i HEAD~5

Squash + clean commits.

🔥 PRACTICE 9 — MULTIPLE REMOTE REPO

Real DevOps mirrors repos.

git remote add backup https://github.com/backup/repo.git
git push backup main
🔥 PRACTICE 10 — RELEASE FROM TAG (REAL CI/CD)

Deploy exact version:

git checkout tags/v3.0

CI/CD uses this.

DEVOPS GIT MASTER LAB

Create fresh practice branch first.

git checkout develop
git pull
git checkout -b git-master-practice
✅ 1. RESOLVE MERGE CONFLICT
Step 1 — Create conflict

Edit file:

echo "Develop change" > conflict.txt
git add .
git commit -m "develop change"

Create feature:

git checkout -b feature-conflict

Change same file:

echo "Feature change" > conflict.txt
git commit -am "feature change"
Step 2 — Merge
git checkout git-master-practice
git merge feature-conflict

💥 Conflict appears.

Step 3 — Fix

Open:

conflict.txt

Remove markers:

<<<<<<<
=======
>>>>>>>

Keep:

Develop change
Feature change

Finish:

git add conflict.txt
git commit -m "conflict resolved"

✅ Done

✅ 2. REBASE SAFELY

Create commits:

echo "line1" >> rebase.txt
git add .
git commit -m "commit1"

echo "line2" >> rebase.txt
git commit -am "commit2"

Update develop:

git checkout develop
echo "develop update" >> rebase.txt
git commit -am "develop update"

Rebase:

git checkout git-master-practice
git rebase develop

If conflict:

fix → git add → git rebase --continue

Push:

git push --force-with-lease

✅ Done

✅ 3. RECOVER DELETED BRANCH

Delete branch:

git branch -D feature-conflict

Recover:

git reflog

Find commit id.

Restore:

git checkout -b feature-conflict COMMIT_ID

✅ Branch back.

✅ 4. RECOVER LOST COMMIT

Simulate disaster:

git reset --hard HEAD~2

Commit gone 😈

Recover:

git reflog

Restore:

git reset --hard COMMIT_ID

✅ Code recovered.

✅ 5. PRODUCTION ROLLBACK

Create bad commit:

echo "BAD CODE" >> prod.txt
git add .
git commit -m "bad deployment"

Rollback safely:

git revert HEAD

✅ New revert commit created.

✅ 6. CHERRY-PICK HOTFIX

Create fix in develop:

git checkout develop
echo "critical fix" >> hotfix.txt
git commit -am "critical fix"

Copy commit id.

Apply to main:

git checkout main
git cherry-pick COMMIT_ID

✅ Only fix moved.

✅ 7. REMOVE SECRET FROM HISTORY

Add secret:

echo "PASSWORD=12345" > secret.txt
git add .
git commit -m "secret added"

Remove:

git rm --cached secret.txt
git commit -m "remove secret"

(Real companies rotate keys also.)

✅ 8. USE STASH

Modify file:

echo "work in progress" >> temp.txt

Save work:

git stash

Check:

git stash list

Restore:

git stash pop

✅ Work returned.

✅ 9. TAG RELEASE

Create release tag:

git tag -a v1.0 -m "production release"

Push tag:

git push origin v1.0

Check:

git tag

✅ Release version created.

✅ 10. DEBUG HISTORY

See commit graph:

git log --oneline --graph --decorate --all

Find who changed file:

git blame conflict.txt

See file history:

git log conflict.txt

✅ Debug complete.

🏆 CONGRATULATIONS

If you practiced all above:

You now know 95% Git used in DevOps production.