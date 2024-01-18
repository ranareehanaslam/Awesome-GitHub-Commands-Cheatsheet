# Awesome GitHub Commands Cheatsheet

Welcome to the world of Git and GitHub! This cheatsheet provides you with essential commands to navigate through GitHub efficiently. Whether you're a beginner or an experienced user, these commands will help you streamline your workflow and collaborate seamlessly with others.


It looks like you're encountering an issue where the GitHub CLI can't find the Git executable in your system's PATH. This typically means that Git is not installed on your Windows machine or the installation path is not included in the PATH environment variable.

Here are the steps to resolve this issue:

### Install Git for Windows

1. Download Git for Windows from the official website: [Git for Windows](https://gitforwindows.org/).
2. Run the installer and follow the installation instructions.
3. During the installation, make sure to check the option to "Use Git from the Windows Command Prompt." This will add Git to your system's PATH.

## GitHub CLI Installation (Windows)

Before you get started, make sure you have GitHub CLI installed on your Windows machine. You can download and install it from [GitHub CLI official website](https://cli.github.com/).

## Basic GitHub Commands

### 1. GitHub Login

```bash
gh auth login
```

This command will prompt you to log in to your GitHub account and authenticate the CLI.

### 2. GitHub Push to Any Branch

```bash
gh repo view --web
git push origin <branch-name>
```

Use the GitHub CLI to view the repository in the browser and then push changes to a specific branch.

### 3. GitHub Pull to Any Branch

```bash
git pull origin <branch-name>
```

Pull changes from a remote repository to your local branch.

### 4. GitHub Fetch

```bash
git fetch
```

Fetch updates from the remote repository, allowing you to see changes without merging them.

### 5. Switch Branch

```bash
git checkout <branch-name>
```

Switch to a different branch in your local repository.

### 6. Create a New Branch

```bash
git checkout -b <new-branch-name>
```

Create and switch to a new branch in one command.

### 7. Commit Changes

```bash
git add .
git commit -m "Your commit message here"
```

Stage changes and commit them with a meaningful message.

### 8. GitHub Clone Repository

```bash
gh repo clone <repository-url>
```

Clone a repository from GitHub to your local machine.

### 9. GitHub Pull Request

```bash
gh pr create --base <base-branch> --head <head-branch> --title "Your PR title" --body "Your PR description"
```

Create a pull request using GitHub CLI.

### 10. GitHub Merge Pull Request

```bash
gh pr merge <pull-request-number>
```

Merge a pull request using GitHub CLI.

### 11. GitHub List Branches

```bash
git branch -a
```

List all branches in your local repository.

### 12. GitHub History

```bash
git log
```

View the commit history of your repository.

### 13. GitHub Remote URL

```bash
git remote -v
```

Display the URLs of the remote repositories associated with your local repository.

## Conclusion

This cheatsheet covers some of the basic GitHub commands to help you navigate through Git and GitHub efficiently. Feel free to explore more commands and options based on your workflow and requirements.

Happy coding! 🚀
