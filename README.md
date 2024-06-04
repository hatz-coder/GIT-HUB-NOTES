# GitHub Notes

## Creating a Repository from Local Folder

1. **Create a New Repository on GitHub:** Ensure not to initialize a README file.
2. **Navigate to the Terminal of the Folder.**
3. **Run the Following Commands:**

   _Initialize an existing directory as a Git repository_

```bash
git init
```

_Stage the current file changes for the next commit_

```bash
git add .
```

_Commit the staged changes with a meaningful message_

```bash
git commit -m "Add a descriptive message here"
```

_Link your local repository to a GitHub repository_

```bash
git remote add origin [URL]
```

_Rename the branch from master to main_

```bash
git branch -M main
```

_Push the committed changes to the GitHub repository_

```bash
git push origin main
```

**OR**

_This will make it current location so it doesn't had to be defined repetitively_

```bash
git push -u origin main
```

## Other Useful Commands

- `git remote -v`: Verify the remote link.
- `git branch`: Verify the branch name.
- `ls -a`: Verify if Git is initialized by checking for the .git file.
- `git status`: Display modified files in the working directory.
- `git pull`: Fetch and merge any commits from the tracking remote branch.
- `git clone [URL]`: Retrieve an entire repository from a hosted location via URL.

## Branching and Merging

- `git branch`: List all branches; an asterisk (\*) indicates the currently active branch.
- `git branch [branch-name]`: Create a new branch at the current commit.
- `git checkout`: Switch to another branch and check it out into your working directory.
- `git merge [branch name]`: Merge the specified branch’s history into the current one.

## Configuration

- `git config --global user.name "ADD THE USER NAME HERE"`: Set the GitHub username.
- `git config --global user.email "ADD THE EMAIL HERE"`: Set the GitHub email.
- `git config --list`: Verify if Git is configured correctly.
