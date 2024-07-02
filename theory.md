1.	What is Git? Git is a distributed version control tool used for tracking changes in computer files. It is an open source and installed locally on the system. Git is generally used for source code management in software development.
2.	What is GitHub? GitHub is a repository hosting service which runs on the cloud. It's used for storing, tracking, and collaborating on software projects. It enables developers to share code files and collaborate with fellow developers on open-source projects. 
3.	What is the difference between git/GitHub? Git is a free open-source version control system installed locally on a personal computer/system; while GitHub runs on the cloud and is a webhosting service for git repositories.
4.	Explain the importance of git/GitHub? Git allows developers to track changes to their code and manage branches, while GitHub provides hosting for Git repositories. It enables collaboration and ensures team members can view recent versions of their work in real time.
5.	Examples of Git best practices
Make increment small changes – Decreases the likelihood of conflicts. Efficient roll back in case it does not work.
Keep commits atomic – This makes code reviews faster
Develop using branches – Changes can be made without affecting the main code line
Write descriptive commit messages
Obtain feedback from code reviews

1.	Working directory – This is the folder where all project files are stored
2.	Difference between local repo and remote repo? Local repo is hosted on the local system and can only be accessible by the user as the user is the only one who can make edits. However remote repo is accessible by the team; changes can be made by multiple users and is hosted in the cloud.
3.	Staging – This is where a modified file has been marked in its current version before it is pushed to the local repository.
4.	Git init – This command initializes a new repository and ensures that the folder or working space is tracked by Git.
5.	Diff between git clone and git pull? Git clone duplicates work from the remote repository however git pull stores in on the local machine

Branch, Merge, Conflict Homework 6/15/24 class
9.	What is a merge conflict and how do you resolve it? This is whereby two branches being merged have changes to the same parts of the same files and Git cannot reconcile the differences. Manual intervention resolves merge conflicts. These include, Smaller commits, Communication, Frequent Pulling and Merging

Continuation of the assignment from 6/15 class
2.	How do you clone a repository? git clone <repository name_url>
3.	How do you check the status of your Git repository? git status
4.	How do you stage and commit changes? git commit -am
5.	How do you create a new branch? git branch <branch name>
13.	How do you find a specific commit in the history? git log