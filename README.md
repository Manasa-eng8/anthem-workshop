# National Anthem Project

This project is created for the Git and GitHub practice workshop.

Team Members:
- Manasa: Team Lead
- Jyothika: Developer
- Reethu: Tester

Topics Covered:
- Git initialization
- GitHub repository
- Push and pull
- Branching and merging
- Merge conflict resolution
🇮🇳 NATIONAL ANTHEM PROJECT

Git & GitHub – Practice Workshop

Workshop Topics: Branching, Pushing, Pulling, Merging and Merge Conflict Resolution
🇮🇳 NATIONAL ANTHEM PROJECT

Git & GitHub – Practice Workshop

Workshop Theme: Branching • Pushing • Pulling • Merging • Merge Conflict Resolution

Project Repository: "National Anthem Workshop" (https://github.com/Manasa-eng8/anthem-workshop)

---

📌 1. PROJECT OVERVIEW

The National Anthem Project is a practical Git and GitHub workshop designed to provide hands-on experience in version control and collaborative software development.

The project uses India's National Anthem, Jana Gana Mana, to demonstrate how developers create and manage files, maintain project history, share code, work on separate branches, and resolve merge conflicts using Git and GitHub.

This workshop covers the complete development workflow, starting from user configuration and repository creation to collaboration, merging, conflict resolution, and recovery of committed work.

🎯 2. PROJECT OBJECTIVES

- Understand the fundamentals of Git and GitHub.
- Create and manage a GitHub repository.
- Initialize and configure a local Git repository.
- Create, add, track, and commit project files.
- Connect a local repository to GitHub.
- Perform push, pull, and clone operations.
- Understand Git branches and merging.
- Practice collaboration between multiple team members.
- Create and resolve merge conflicts.
- Understand Git history and commit recovery.

👥 3. TEAM MEMBERS

Sl. No.| Team Member| Designation| Responsibilities
1| Manasa M Nadiger| Team Lead| Repository management, team coordination, reviewing changes, merging and conflict resolution
2| Jyothika| Developer| Application development, creating files, updating code and implementing features
3| Reethu K P| Tester| Testing files, checking changes, identifying issues and verifying project updates

💻 4. TECHNOLOGIES, PROGRAMMING LANGUAGES AND TOOLS USED

Programming and Markup Languages

Technology| Usage
Python| Basic programming and Flask application development
HTML| Creating the National Anthem webpage
Markdown| Writing project documentation in README.md

Tools and Platforms

Tool / Platform| Purpose
Git| Version control and tracking changes
GitHub| Online repository hosting and collaboration
Ubuntu Linux| Operating system for workshop activities
Linux Terminal| Executing Git and Linux commands
Nano Editor| Creating and editing project files
Python 3| Executing Python programs
Flask| Developing the National Anthem web application exercise
AWS EC2| Providing the Linux environment for workshop activities

📁 5. PROJECT STRUCTURE

The current GitHub repository contains the following files:

anthem-workshop/
│
├── README.md
├── add.py
├── anthem.py
├── anthem.html
└── tt.txt

File Descriptions

File Name| Description
README.md| Contains project overview, documentation, tools and workshop details
add.py| Python program demonstrating addition of two numbers
anthem.py| Python file used for the National Anthem exercise
anthem.html| HTML file related to the National Anthem webpage
tt.txt| Text file containing the National Anthem text

Additional workshop exercise files: The Flask application activity also requires creating "app.py" and "templates/index.html". These are part of the workshop instructions and are not currently listed among the repository's existing files.

⚙️ 6. PROJECT REQUIREMENTS

A. Hardware Requirements

Sl. No.| Requirement
1| Laptop or desktop computer
2| Stable internet connection
3| AWS EC2 instance for the Linux environment

B. Software Requirements

Sl. No.| Software / Platform| Requirement
1| Ubuntu Linux| Linux environment
2| Git| Installed and configured
3| Python 3| Installed
4| Nano Editor| Installed
5| GitHub| Active account
6| Personal Access Token (PAT)| GitHub authentication
7| Flask| Required for the Flask application exercise

C. Team User Requirements

The workshop uses three separate Linux user accounts to demonstrate collaboration and individual commit histories.

Sl. No.| Linux User| Team Member| Role| Main Responsibility
1| manasa| Manasa M Nadiger| Team Lead| Creates and manages the repository, reviews contributions, merges branches and resolves conflicts
2| jyothika| Jyothika| Developer| Creates the application, develops features and pushes code changes
3| reethu| Reethu K P| Tester| Pulls updates, tests files, improves content and verifies changes

Configuration required for all three users:

- Each user must have a separate Linux account.
- Each user must configure their Git username and email.
- The default branch should be configured as "main".
- Git authentication must be configured for pushing changes.
- Each member should work using their own Linux account to maintain individual commit history.

🔄 7. WORKSHOP WORKFLOW

The following flowchart represents the overall process followed in the workshop.

       START
         |
         v
  Configure 3 Users
         |
         v
  Create Git Repository
         |
         v
  Add Project Files
         |
         v
  Commit and Push
         |
         v
  Clone Repository
         |
         v
  Pull Latest Changes
         |
         v
  Develop and Update Files
         |
         v
  Create Feature Branch
         |
         v
   Commit and Push Branch
         |
         v
    Merge Branches
         |
         v
  Resolve Merge Conflict
         |
         v
  Recover Committed Work
         |
         v
  Verify Final Repository
         |
         v
        END

🚀 8. WORKSHOP ACTIVITIES – STEP-BY-STEP

👤 PART 0: CONFIGURATION OF THREE LINUX USERS

Objective: Configure separate user accounts and Git identities for collaborative development.

Activities:

1. Check whether the three Linux users exist.
2. Create the users if they are not available.
3. Configure Git username and email for Manasa, Jyothika and Reethu.
4. Set the default Git branch to "main".
5. Configure Nano as the Git editor.
6. Configure Git authentication and credential storage.
7. Verify all three Git usernames.

Expected Result: All three users should have correctly configured Git identities.

📤 PART 1: REPOSITORY CREATION, PUBLISHING AND CLONING

Objective: Create a Git repository and share it with team members.

Activities:

1. Create a project directory named "anthem-workshop".
2. Initialize Git using "git init".
3. Create "anthem.txt" containing "Jana Gana Mana".
4. Add the file using "git add".
5. Commit the file using "git commit".
6. Create a GitHub repository named "anthem-workshop".
7. Connect the local repository to GitHub using "git remote add origin".
8. Push the project using "git push -u origin main".
9. Clone the repository using the other team members' accounts.
10. Verify repository history, remote URL and branch tracking.

Expected Result: All three users should have access to the same GitHub project and its commit history.

🔁 PART 2: PUSH AND PULL BETWEEN TEAM MEMBERS

Objective: Understand how changes made by one team member are shared with others.

Activities:

Jyothika – Developer

1. Pull the latest repository changes.
2. Create the Flask application file "app.py".
3. Create the folder "templates".
4. Create "templates/index.html".
5. Add the National Anthem heading and first stanza.
6. Stage and commit the application files.
7. Push the changes to GitHub.

Reethu K P – Tester

1. Pull Jyothika's latest changes.
2. Check the application files.
3. Update the HTML page with the next line of the stanza.
4. Review the changes using "git diff".
5. Stage, commit and push the updated file.

Manasa M Nadiger – Team Lead

1. Pull the latest changes.
2. Check the contributions made by the other members.
3. View commit history using "git log".
4. View individual contributions using "git shortlog".
5. Check file-level authorship using "git blame".

Expected Result: All members should be able to share and receive project updates through GitHub.

🌿 PART 3: BRANCHING, MERGING AND BRANCH DELETION

Objective: Understand how branches support independent development.

Activities:

Jyothika – Developer

1. Pull the latest changes.
2. Create a feature branch named "feature/second-stanza".
3. Add the next stanza to the HTML page.
4. Commit the changes separately.
5. Push the feature branch to GitHub.
6. Switch between "main" and the feature branch to compare files.

Manasa M Nadiger – Team Lead

1. Pull the latest changes.
2. Fetch remote branches using "git fetch origin".
3. Review available branches.
4. Merge the feature branch into "main".
5. Verify the commit history.
6. Push the merged changes.
7. Delete the remote feature branch.
8. Verify the final branch list.

Expected Result: The feature branch should be merged into "main", and the unnecessary remote branch should be deleted.

⚔️ PART 4: CREATING AND RESOLVING A MERGE CONFLICT

Objective: Understand how Git identifies conflicting changes and how team members resolve them.

Activities:

Jyothika – Developer

1. Switch to the "main" branch and pull the latest changes.
2. Create a branch named "title-english".
3. Change the HTML heading to "Jana Gana Mana - National Anthem of India".
4. Commit and push the branch.

Reethu K P – Tester

1. Start from the same original commit on "main".
2. Create another branch named "title-bilingual".
3. Change the same HTML heading to "Bharat ka Rashtragan - Jana Gana Mana".
4. Commit and push the branch.

Manasa M Nadiger – Team Lead

1. Fetch both remote branches.
2. Merge "title-english" first.
3. Merge "title-bilingual" next.
4. Identify the merge conflict in "templates/index.html".
5. Examine the conflict markers.
6. Select the required final heading.
7. Remove all conflict markers.
8. Stage and commit the resolved file.
9. Push the final merge commit.
10. Verify that no conflict markers remain.

Expected Result: The conflicting changes should be resolved, and the final HTML file should contain the selected heading without conflict markers.

♻️ PART 5: UNDO AND RECOVER CHANGES

Objective: Learn how Git handles lost work and how committed changes can be recovered.

Activities:

1. Understand the difference between committed and uncommitted work.
2. Add a temporary line to demonstrate uncommitted changes.
3. Use "git reset --hard HEAD" to discard those uncommitted changes.
4. Create a new commit with a sample change.
5. Note the commit hash.
6. Use "git reset --hard HEAD~1" to move the branch back one commit.
7. Use "git reflog" to locate the previous commit.
8. Recover the committed work using the saved commit hash.
9. Verify the recovered commit and repository status.

Expected Result: Understand how committed work can be recovered using Git reflog and why regular commits are important.

🧰 9. IMPORTANT GIT COMMANDS USED

Command| Purpose
"git init"| Initialize a local repository
"git config --global user.name"| Configure Git username
"git config --global user.email"| Configure Git email
"git status"| Check repository status
"git add ."| Stage changes
"git commit -m "message""| Save changes in Git history
"git log --oneline"| Display commit history
"git remote -v"| Display remote repository details
"git remote add origin URL"| Connect local repository to GitHub
"git push"| Upload changes to GitHub
"git pull"| Download and integrate remote changes
"git clone URL"| Copy a remote repository
"git branch"| Display branches
"git switch -c branch-name"| Create and switch to a branch
"git fetch origin"| Retrieve remote updates
"git merge branch-name"| Merge another branch
"git diff"| Display file differences
"git blame filename"| Display line-by-line authorship
"git shortlog -sn"| Display contribution counts by author
"git reflog"| Display reference history
"git reset --hard HEAD"| Reset working tree to current commit
"git merge --abort"| Cancel an unfinished merge

📊 10. WORKSHOP CHECKPOINTS AND TIME ALLOCATION

Workshop Part| Activity| Duration
Part 0| Configure three users| 10 minutes
Part 1| Repository publishing and cloning| 20 minutes
Part 2| Push and pull between members| 25 minutes
Part 3| Branching, merging and deletion| 25 minutes
Part 4| Merge conflict creation and resolution| 30 minutes
Part 5| Undo and recovery (if time permits)| 15 minutes
| Total planned time| 125 minutes

🎓 11. EXPECTED LEARNING OUTCOMES

After completing the workshop, the team should be able to:

- Create and manage Git repositories.
- Work with local and remote repositories.
- Perform push, pull and clone operations.
- Maintain project history through commits.
- Collaborate using separate user accounts.
- Create, switch, merge and delete branches.
- Identify and resolve merge conflicts.
- Understand committed and uncommitted changes.
- Recover committed work using Git reflog.
- Understand the importance of version control in software development.

🏁 12. CONCLUSION

The National Anthem Project provides practical experience with Git and GitHub through collaborative development activities.

Throughout the workshop, the team learns repository creation, Linux user configuration, file management, version control, pushing, pulling, cloning, branching, merging, conflict resolution and commit recovery.

By completing these activities, Manasa M Nadiger, Jyothika and Reethu K P gain practical knowledge of how developers collaborate, maintain project history and manage changes efficiently using Git and GitHub.

---

🔗 13. PROJECT REPOSITORY

Project Name: National Anthem Project – Git & GitHub Practice Workshop

GitHub Repository:
https://github.com/Manasa-eng8/anthem-workshop

Team Details

Team Member| Role
Manasa M Nadiger| Team Lead
Jyothika| Developer
Reethu K P| Tester

Thank You! 🇮🇳
