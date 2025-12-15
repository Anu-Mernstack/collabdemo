Title: GitHub Account Creation & Git Installation and Configuration
Course Outcome (CO1):
Understand and demonstrate GitHub account creation, Git installation, initial setup, and basic version control usage.
________________________________________
🔹 1. What is Git?
•	Git is a Distributed Version Control System (DVCS).
•	Tracks code changes over time.
•	Allows collaboration, branching, merging, reverting, etc.
🔹 2. What is GitHub?
•	Cloud-based platform that hosts Git repositories.
•	Provides remote access, collaboration tools, issues, pull requests, and more.
________________________________________
Skill Manual / Tutorial
 Part A: GitHub Account Creation
🪜 Steps:
1.	Go to: https://github.com
2.	Click on Sign Up.
3.	Provide:
o	Valid email address
o	Username (unique)
o	Password
4.	Verify email address.
5.	Choose Free Plan (for students).
6.	Set up profile preferences.
7.	You now have a GitHub account!
 Tips:
•	Choose a professional username (e.g., firstname-lastname).
•	Use a recovery email.
________________________________________
 Part B: Git Installation (Windows)
Windows:
1.	Download Git from: https://git-scm.com/download/win
2.	Run the installer with default settings:
o	Use Git Bash only.
o	Line endings: Checkout Windows-style, commit Unix-style.
3.	After installation, open Git Bash.
 Part C: Git Configuration
Once installed, configure user info (required for commit metadata):
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
Verify settings:
git config --list
________________________________________
 Hands-on Activity
 Skill Practice 1: First Git Repository (Local)
mkdir my-first-repo
cd my-first-repo
git init
touch README.md
git add README.md
git commit -m "Initial commit"
________________________________________
Skill Practice 2: Connect to GitHub (Remote Repo)
1.	Go to GitHub → New Repository → Name: my-first-repo
2.	Don’t initialize with README
3.	Copy the repository URL (HTTPS preferred)
git remote add origin https://github.com/your-username/skill-1-repo.git
git branch -M main
git push -u origin main
________________________________________

<img width="629" height="328" alt="image" src="https://github.com/user-attachments/assets/2844edc4-16c0-4528-99b8-6c33fd6ebae4" />

________________________________________
 Understanding Git
Imagine Google Docs vs Microsoft Word:
•	Git (like Word) works offline – you make changes locally.
•	GitHub (like Google Docs) allows cloud storage and collaboration.
•	You need to save (commit) and upload (push) to see changes in the cloud (GitHub).
________________________________________
Final Checklist
 GitHub Account Setup
•	 GitHub account created
•	 Email verified
•	 Public profile set up
Git Installed and Configured
•	 Git installed successfully
•	 Configured user.name and user.email
•	 Verified with git config --list
GitHub Repository
•	 Created a repo on GitHub
•	 Cloned or pushed from local to remote
________________________________________
Submission (Lab Instructor Checklist)
Student Name	GitHub URL	Screenshot of Local Git Bash
