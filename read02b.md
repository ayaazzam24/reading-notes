# Version Control
 a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

# Local Version Control
Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

# Centralized Version Control
The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients.

# So, what is Git?
> ## ***Snapshots***

***Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.***
> ## ***Local Operations***

***Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.***
> ## ***Tracking Changes***

***Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.***
> ## ***Loss of Data***

***Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.***
>  ## ***States***

***Files in Git can reside in three main states:***
1. Committed : Data is securely stored in a local database .
2. Modified : File has been changed but not committed to the database .
3. Staged : Flagged a file’s changed version to be committed in the next snapshot .

![image1](https://miro.medium.com/max/500/1*9hNsHV22lsi03i9Ah92KmQ.png)


# Workflow
## Local Repository Structure
**The local Git repository has three components:**

* Working Directory: The actual files reside here.
* Index: The area used for staging
* Head: Points to the most recent commit


# Saving Changes
**All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.**

> Tracked
Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

> Untracked
Untracked files were not in the last snapshot and do not currently reside in the staging area.

**After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.**

# The Life Cycle of File Status

![image2](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

# Check File Status
To determine the state of files, utilize the **git status** command:
     
     - $ git status
On branch master

nothing to commit, working directory clean

**This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.**

# Tracking and Staging a New File
## Single File
Track one file only by using the following format:

     - git add filename

**After using these commands, files are tracked and staged for committing.**
 
After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the  **git status** command
 
  
     - $ git status

     - On branch master
     
     - Changes to be committed:

        - (use "git reset HEAD ..." to unstage)
        
# Pushing Changes 

Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example :
    
    - $ git push origin master

This command pushes changes from the local **“master”** branch to the remote repository named **“origin”**.

For cloned repositories, Git will automatically give the name **“origin”** to the server from which you cloned and the name **“master”** to your local repository. However, these names can be changed by the user.

     
   








