# 🚀 Essential GitHub Commands

Welcome to the **Essential GitHub Commands** guide! This document serves as a quick reference for the most commonly used Git commands that every developer should know. Whether you're just starting with Git or need a refresher, this guide will help you navigate the basics and enhance your productivity on GitHub.

---

## 📚 Table of Contents

1. [📥 Cloning a Repository](#cloning-a-repository)
2. [🌱 Creating a New Repository](#creating-a-new-repository)
3. [🔄 Staging Changes](#staging-changes)
4. [📝 Committing Changes](#committing-changes)
5. [🗂 Branching](#branching)
6. [🔀 Merging Branches](#merging-branches)
7. [📊 Viewing Status](#viewing-status)
8. [🗑 Deleting a Branch](#deleting-a-branch)
9. [🔍 Viewing Commit History](#viewing-commit-history)
10. [🌐 Pushing Changes](#pushing-changes)
11. [📥 Pulling Changes](#pulling-changes)
12. [🧩 Pull Requests](#pull-requests)

---

## 📥 Cloning a Repository

To clone a repository from GitHub to your local machine, use the following command:

```bash
git clone <repository-url>
Example:

bash
Copy code
git clone https://github.com/username/repo.git
This command creates a copy of the specified repository in a directory with the same name as the repository.

🌱 Creating a New Repository
To create a new Git repository, navigate to the desired directory in your terminal and run:

bash
Copy code
git init <repository-name>
Example:

bash
Copy code
git init my-new-repo
This initializes a new Git repository in the specified folder.

🔄 Staging Changes
Before committing your changes, you need to stage them. To stage a specific file, use:

bash
Copy code
git add <file-name>
To stage all changes, run:

bash
Copy code
git add .
📝 Committing Changes
Once your changes are staged, you can commit them with a descriptive message:

bash
Copy code
git commit -m "Your commit message here"
Example:

bash
Copy code
git commit -m "Fix bug in user authentication"
🗂 Branching
To create a new branch, use:

bash
Copy code
git branch <branch-name>
To switch to that branch, run:

bash
Copy code
git checkout <branch-name>
Example:

bash
Copy code
git branch feature-xyz
git checkout feature-xyz
You can also create and switch in one command:

bash
Copy code
git checkout -b <branch-name>
🔀 Merging Branches
To merge changes from one branch into another, first switch to the target branch, then run:

bash
Copy code
git merge <branch-name>
Example:

bash
Copy code
git checkout main
git merge feature-xyz
📊 Viewing Status
To check the status of your repository, use:

bash
Copy code
git status
This command shows which files are staged, unstaged, or untracked.

🗑 Deleting a Branch
To delete a branch that you no longer need, use:

bash
Copy code
git branch -d <branch-name>
Example:

bash
Copy code
git branch -d feature-xyz
🔍 Viewing Commit History
To view the commit history of your repository, run:

bash
Copy code
git log
This command shows a list of all commits, including the commit message and author information.

🌐 Pushing Changes
To push your local changes to the remote repository, use:

bash
Copy code
git push origin <branch-name>
Example:

bash
Copy code
git push origin main
📥 Pulling Changes
To pull the latest changes from the remote repository, use:

bash
Copy code
git pull origin <branch-name>
Example:

bash
Copy code
git pull origin main
🧩 Pull Requests
To create a pull request, go to your GitHub repository and click on the Pull Requests tab, then follow the prompts to create a new pull request from your feature branch.

📌 Conclusion
With these essential GitHub commands at your fingertips, you can efficiently manage your projects, collaborate with others, and keep your codebase organized. Happy coding!

💬 Need Help?
If you have any questions or need further assistance, feel free to reach out!
