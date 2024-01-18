# Awesome GitHub Commands Cheatsheet

Welcome to our GitHub repository! Here's a handy cheatsheet to help you navigate and contribute to our project seamlessly.

## GitHub Basics

### 1. GitHub Login
To log in to your GitHub account, use the following command:
```bash
git login
```

### 2. Pushing to Any Branch
Push your changes to a specific branch with the following command:
```bash
git push <remote-name> <branch-name>
```
Example:
```bash
git push origin main
```

### 3. Pulling from Any Branch
Fetch and merge changes from a remote repository to your current branch:
```bash
git pull <remote-name> <branch-name>
```
Example:
```bash
git pull origin feature-branch
```

### 4. Fetching Changes
To fetch changes from a remote repository without merging, use:
```bash
git fetch <remote-name>
```
Example:
```bash
git fetch origin
```

### 5. Switching Branches
Switch between branches using:
```bash
git checkout <branch-name>
```
Example:
```bash
git checkout develop
```

### 6. Creating a New Branch
Create and switch to a new branch:
```bash
git checkout -b <new-branch-name>
```
Example:
```bash
git checkout -b feature-new-feature
```

### 7. Checking Status
Check the status of your working directory and staging area:
```bash
git status
```

## Collaboration

### 8. Cloning a Repository
Clone a remote repository to your local machine:
```bash
git clone <repository-url>
```
Example:
```bash
git clone https://github.com/username/repo.git
```

### 9. Forking a Repository
Fork a repository to create your copy on GitHub:
- Click the "Fork" button on the repository page.

### 10. Pull Request
Create a pull request to propose changes to the main project:
- Fork the repository and create a new branch.
- Commit changes to the new branch.
- Open a pull request on GitHub.

## Tips and Tricks

### 11. Ignoring Files
Create a `.gitignore` file to specify files or directories to be ignored:
```bash
touch .gitignore
```

### 12. Viewing Branches
List all local branches:
```bash
git branch
```

List all remote branches:
```bash
git branch -r
```

## Troubleshooting

### 13. Undoing Changes
Discard changes in the working directory:
```bash
git checkout -- <file-name>
```

### 14. Discard Uncommitted Changes
Reset the working directory to match the last commit:
```bash
git reset --hard
```

## Collaboration Etiquette

Please follow these guidelines when collaborating on this project. Happy coding!

---
