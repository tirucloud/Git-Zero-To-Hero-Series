# Welcome to git
## Day-01: Git-Zero-To-Hero_series

## Git Fundamentals & Setup (2 hours)
### 🕐 Hour 1 — Core Concepts
### 👉 Learn theory + visual understanding

### What is Git?

Distributed Version Control System

Tracks changes to files over time

Helps in collaboration and rollback

Difference between Git and GitHub

Git = tool (local)

GitHub = remote hosting service for Git repositories

### Key Git Concepts (Understand these clearly):

* Repository
* Commit
* Working directory, Staging area, and .git folder
* Branch
* Remote repository
* Merge and Pull
* HEAD (pointer to current commit)

### Visualize Git Workflow:

* Working Directory → Staging Area → Local Repository → Remote Repository.
  
###🕒 Hour 2 — Hands-on Practice
###👉 Practical setup and first Git operations

### Step 1. Install Git
On Ubuntu / WSL / Linux:
```
sudo apt update
sudo apt install git -y
```
On Windows: Install via https://git-scm.com/downloads
(Make sure to enable “Git Bash”)
Step 2. Configure Git (one-time setup)
```
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
git config --list
```
Step 3. Create Your First Repository
```
mkdir git-demo
cd git-demo
git init
```
Creates .git hidden folder (Git’s database)

Step 4. Add and Commit Files
```
echo "Hello Git" > hello.txt
git status
git add hello.txt
git commit -m "Initial commit - added hello.txt"
git log
```
Step 5. Modify and Track Changes
```
echo "Learning Git Day 1" >> hello.txt
git status
git diff
git add hello.txt
git commit -m "Updated hello.txt with learning message"
```
Step 6. View Commit History and Changes
```
git log --oneline
git show HEAD
```
✅ Day 1 Output Checklist
By the end of today, you should:
✔️ Know what Git is and how it works conceptually
✔️ Have Git installed and configured
✔️ Have created your first repository
✔️ Be able to track, commit, and view file changes
