# Git v GitHub

- **VCS** Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.
- **Git vs. Github** git is the recipe, github is the place where it serves the cake.
- **local vs remote** 
- **clone** You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
- **commit** same as Save As
- **ACP** Add, Commit, Push. 
- **deployment** creating git hub

Git is a DVCS that stores data in a file system made up of snapshots.

Commit = Save As 

HEAD = The label meaning "You are Here"
You can also assign messages to commits.
ACP frequently and often
# GitHub
GitHub is just a website, free to use.
- it's a way to share code with others
an online place to store your code

what is a repository? fancy word for a folder where you put the files.

## Workflow
### **The local Git repository has three components:**

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

**Tracked** - Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

**Untracked** Untracked files were not in the last snapshot and do not currently reside in the staging area.

### **The Life Cycle of File Status**
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. Then, you commit staged changes.

**git commit -a** : This command commits a snapshot of all modifications to tracked files in the working directory.

