# 🚀 DevOps Git Version Control Project

This project demonstrates a basic **Git and GitHub version-control workflow** as part of the DevOps Internship Task 4.

The project focuses on Git best practices such as:

- Git repository initialization
- Git commits
- Branching
- Feature branches
- Pull Requests
- Branch merging
- `.gitignore`
- Git tags
- Project documentation using Markdown

---

## 🎯 Objective

The objective of this task is to manage a DevOps project using **Git and GitHub best practices**.

---

## 🛠️ Tools Used

- Git
- GitHub
- Visual Studio Code
- Markdown
- HTML

---

## 📁 Project Structure

```text
DevOps-Git-Project/
│
├── index.html
├── README.md
├── .gitignore
│
└── screenshots/
    ├── git-init.png
    ├── branches.png
    ├── github-repository.png
    ├── pull-request.png
    ├── merged-pr.png
    └── git-tag.png

🌿 Git Branches

The following branches were used in this project:

1. main

The main branch contains the final and stable version of the project.

2. dev

The dev branch is used for development and integration of new changes.

3. feature/update-readme

The feature branch was created to make changes to the project README.

🔄 Git Workflow

The workflow used in this project is:

Feature Branch
      │
      ▼
Make Changes
      │
      ▼
Git Add
      │
      ▼
Git Commit
      │
      ▼
Git Push
      │
      ▼
Pull Request
      │
      ▼
dev Branch
      │
      ▼
Pull Request
      │
      ▼
main Branch
📝 Git Commands Used
Initialize Git Repository
git init

Initializes a new Git repository.

Check Repository Status
git status

Displays the current status of files and branches.

Add Files
git add .

Adds all changed files to the staging area.

Commit Changes
git commit -m "Initial project setup"

Saves the changes to the Git repository.

Create Main Branch
git branch -M main

Renames the current branch to main.

Create Development Branch
git checkout -b dev

Creates and switches to the dev branch.

Create Feature Branch
git checkout -b feature/update-readme

Creates and switches to the feature branch.

Push Branch to GitHub
git push -u origin feature/update-readme

Uploads the feature branch to GitHub.

Switch Branch
git checkout dev

Switches to the dev branch.

Pull Latest Changes
git pull origin dev

Downloads the latest changes from the remote dev branch.

🔀 Pull Request

A Pull Request was used to merge changes from the feature branch into the development branch.

Pull Request Workflow
feature/update-readme
          │
          ▼
     Pull Request
          │
          ▼
         dev

After the changes were reviewed and merged into dev, the dev branch was merged into main using another Pull Request.

dev
 │
 ▼
Pull Request
 │
 ▼
main
🏷️ Git Tag

A Git tag was created to mark the project version.

Tag used:

v1.0.0

Create the tag:

git tag v1.0.0

Check available tags:

git tag

Push the tag to GitHub:

git push origin v1.0.0

The tag represents version 1.0.0 of the project.

🚫 .gitignore

A .gitignore file was added to prevent unnecessary or sensitive files from being tracked by Git.

Example:

node_modules/
.env
*.log
.vscode/

The .gitignore file helps keep the Git repository clean and prevents unwanted files from being uploaded.

🌐 Project Files
index.html

The index.html file contains a simple web page created for this Git version-control project.

It demonstrates the project information and the tools used.

README.md

This file contains the complete documentation of the project, Git workflow, commands, branches, Pull Requests, and Git tags.

.gitignore

Contains files and directories that should not be tracked by Git.

📸 Screenshots

Screenshots of the important steps are stored in the screenshots folder.

Git Repository

Git Branches

GitHub Repository

Pull Request

Merged Pull Request

Git Tag

📚 What I Learned

Through this task, I learned:

How to initialize a Git repository
How to create and manage branches
How to create feature branches
How to make Git commits
How to push code to GitHub
How to create Pull Requests
How to merge branches
How to use .gitignore
How to create and manage Git tags
How to document a project using Markdown
🎯 Conclusion

This project demonstrates a basic Git and GitHub DevOps workflow using proper version-control practices.

The project follows the workflow:

Git Repository
      ↓
Branches
      ↓
Feature Development
      ↓
Commit
      ↓
Push
      ↓
Pull Request
      ↓
dev
      ↓
Pull Request
      ↓
main
      ↓
Git Tag

This workflow helps maintain organized code, track changes, collaborate with other developers, and manage project versions.

👨‍💻 Author

Harshad Shinde

DevOps & AWS Enthusiast

GitHub: harshadbshinde


### One important thing

Before you finish the task, make sure your actual GitHub repository matches the README. In particular, you should have:

```text
main
dev
feature/update-readme

and a tag:

v1.0.0
