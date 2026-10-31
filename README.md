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

---

1. Project Overview

The National Anthem Project is a practical Git and GitHub workshop project designed to provide hands-on experience with version control and collaborative software development.

The project uses India's National Anthem, Jana Gana Mana, as an example to demonstrate how developers can create files, maintain project history, share code, work on separate branches and resolve conflicts while collaborating through GitHub.

The workshop covers the complete workflow, from configuring users and creating a repository to recovering committed work.

2. Objectives

- Understand the fundamentals of Git and GitHub.
- Create and manage a GitHub repository.
- Initialize a local Git repository.
- Create, add, track and commit project files.
- Connect a local repository to GitHub.
- Learn pushing and pulling changes.
- Understand Git branches and merging.
- Practice collaboration between multiple team members.
- Create and resolve merge conflicts.
- Understand Git history and commit recovery.

3. Team Members

Sl. No.| Team Member| Role| Responsibility
1| Manasa M Nadiger| Team Lead| Repository management and team coordination
2| Jyothika| Developer| Development and project file management
3| Reethu| Tester| Testing, checking files and identifying issues

4. Technologies, Languages and Tools Used

Programming and Markup Languages

Technology| Purpose
Python| Basic programming and application development exercises
HTML| Creating the National Anthem webpage
Markdown| Writing project documentation in README.md

Tools and Platforms

Tool| Purpose
Git| Version control and tracking changes
GitHub| Online repository hosting and collaboration
Ubuntu Linux| Operating system used for workshop activities
Linux Terminal| Executing Git and Linux commands
Nano Editor| Creating and editing files
Python 3| Running Python programs
Flask| Building the web application exercise
AWS EC2| Providing the Linux environment for the workshop

5. Project Structure

The repository contains the following files:

anthem-workshop/
│
├── README.md
├── add.py
├── anthem.py
├── anthem.html
└── tt.txt

File Description

File Name| Description
README.md| Project overview, documentation, tools and workshop details
add.py| Python program demonstrating addition of two numbers
anthem.py| Python file used for the National Anthem exercise
anthem.html| HTML file related to the National Anthem webpage
tt.txt| Text file containing the National Anthem text

Note: The workshop also includes creating "app.py" and "templates/index.html" as part of the Flask application exercise. These are workshop exercise files and are not listed as existing files in the repository structure above.

6. Requirements

Hardware Requirements

- Laptop or computer.
- Internet connection.
- AWS EC2 instance for the Linux workshop environment.

Software Requirements

- Ubuntu Linux environment.
- Git installed.
- Python 3 installed.
- Nano text editor installed.
- GitHub account.
- GitHub Personal Access Token (PAT) for authentication.

User Requirements

Three Linux user accounts are used in the workshop exercises:

- Satish – Team Lead role in the workshop instructions.
- Rajesh – Developer role in the workshop instructions.
- Ramesh – Tester role in the workshop instructions.

Each user must have Git username and email configured correctly.

7. Workshop Activities – Step-by-Step

Part 0: Configure Three Linux Users

- Check whether the three Linux users exist.
- Configure Git username and email for each user.
- Set the default branch to "main".
- Configure the Git editor and authentication helper.
- Verify that all three Git usernames are displayed correctly.

Part 1: Repository Creation, Publishing and Cloning

- Create a local project directory named "anthem-workshop".
- Initialize Git using "git init".
- Create "anthem.txt" containing "Jana Gana Mana".
- Add and commit the file.
- Create a GitHub repository named "anthem-workshop".
- Connect the local repository to GitHub using a remote.
- Push the project to GitHub.
- Clone the repository using the other two users.
- Verify repository history and remote configuration.

Part 2: Push and Pull Between Team Members

- Developer pulls the latest repository.
- Create the Flask application file "app.py".
- Create the HTML template "templates/index.html".
- Add the National Anthem heading and first stanza.
- Track and commit the application files.
- Push changes to GitHub.
- Tester pulls the latest changes.
- Update the HTML page with the next line of the stanza.
- Commit and push the updated file.
- Team Lead pulls and checks the changes.
- Use Git history and blame commands to identify contributions.

Part 3: Branching, Merging and Branch Deletion

- Understand how Git branches work.
- Create a feature branch named "feature/second-stanza".
- Add the next stanza to the HTML page.
- Make separate commits for the changes.
- Push the feature branch to GitHub.
- Switch between "main" and the feature branch.
- Verify that unfinished changes do not affect "main".
- Merge the feature branch into "main".
- Delete the remote feature branch.
- Verify the final branch list and commit history.

Part 4: Creating and Resolving a Merge Conflict

- Create two branches from the same starting commit.
- Change the same HTML heading in different ways.
- Commit and push both branches.
- Merge the first branch successfully.
- Merge the second branch to produce a conflict.
- Identify conflict markers in the HTML file.
- Compare both versions of the heading.
- Select the correct final heading.
- Remove all conflict markers.
- Add, commit and push the resolved file.
- Verify that no conflict markers remain.

Part 5: Undo and Recover Changes

- Understand the difference between uncommitted and committed work.
- Use "git reset --hard HEAD" to demonstrate discarding uncommitted changes.
- Create a commit and note its commit hash.
- Use "git reset --hard HEAD~1" to move back one commit.
- Use "git reflog" to locate the previous commit.
- Recover the committed work using its commit hash.
- Verify the recovered commit and clean working tree.

8. Important Git Commands Used

Command| Purpose
"git init"| Initialize a repository
"git status"| Check repository status
"git add ."| Stage changes
"git commit -m "message""| Save changes in Git history
"git log --oneline"| View commit history
"git remote -v"| View remote repository
"git push"| Upload changes to GitHub
"git pull"| Download and integrate changes
"git clone"| Copy a remote repository
"git branch"| List branches
"git switch -c branch-name"| Create and switch to a branch
"git merge branch-name"| Merge a branch
"git fetch"| Retrieve remote updates
"git diff"| View file differences
"git blame filename"| View line-by-line authorship
"git shortlog -sn"| View contributions by author
"git reflog"| View reference history
"git reset --hard"| Reset working tree and current branch

9. Expected Learning Outcomes

After completing the workshop, participants should be able to:

- Create and manage Git repositories.
- Work with local and remote repositories.
- Perform push, pull and clone operations.
- Maintain project history using commits.
- Collaborate with multiple developers.
- Create, switch, merge and delete branches.
- Identify and resolve merge conflicts.
- Understand the difference between committed and uncommitted changes.
- Recover committed work using Git reflog.
- Understand the importance of version control in software development.

10. Conclusion

The National Anthem Project provides practical experience with Git and GitHub through a collaborative development activity.

The workshop demonstrates repository creation, user configuration, file management, version control, pushing, pulling, branching, merging, conflict resolution and commit recovery.

By completing these activities, the team gains an understanding of how developers collaborate, maintain project history and manage changes efficiently using Git and GitHub.

---

11. Project Repository

GitHub Repository:
https://github.com/Manasa-eng8/anthem-workshop

Project: National Anthem Project – Git & GitHub Practice Workshop

Team Members: Manasa M Nadiger, Jyothika and Reethu Kundur P
