![image](https://github.com/user-attachments/assets/40aca868-f0bd-40fd-abae-1705789d0f3f)

SYSADM1 – Git Basics
Answer the following research questions about Git, GitLab desktop and GitHub.
1.	What is Git, and why is it important in software development?
   
•	Git is a distributed version control system that allows developers to track changes in their code, collaborate with others, and manage project versions efficiently. It is important in the software development because it makes collaboration easier, allowing changes by multiple people to all be merged into one source. 

2.	How does Git track changes in a project?
   
•	Git tracks project changes by taking snapshots of files at specific points in time, called "commits," stored in a local repository. It uses a staging area (index) to manage these snapshots, allowing selective file addition before committing, creating a history of changes within the project.

3.	What is the difference between a local repository and a remote repository in Git?
   
•	A local repository is a personal computer-based copy of a project's code, enabling changes and commits, while a remote repository like GitHub is a centralized server where developers can share and access changes.

4.	What are the basic Git commands? 
•	git init (create a new Git repository)

•	git status (check the current state of your files)

•	git add (stage changes to be committed)

•	git commit (save changes to the local repository)

•	git push (upload changes to a remote repository)

•	git clone (download a repository from a remote server)

•	git checkout (switch between branches)

•	git merge (combine changes from different branches)

•	git pull (fetch changes from a remote repository and merge them locally)


5.	How do you check the status of a Git repository?
   
•	The git status command displays the current state of the repository, including the working branch and files in the staging area that have not been committed.

6.	What is the purpose of branches in Git, and how do you create and switch between them?
   
•	Git branches offer a structured method for managing code changes, facilitating seamless integration of new features, bug fixes, and experimental ideas without disrupting the main codebase.

7.	What are GitLab Desktop and GitHub, and how are they different from Git?
    
•	GitHub is a repository hosting service tool for programmers, allowing collaboration and access control. GitLab is a repository hosting manager tool developed by GitLab Inc, used for software development, showcasing 
management and importing repositories from Google Code and Bitbucket.

8.	How do you connect a local Git repository to a GitLab or GitHub repository?
    
•	To connect a local Git repository to a GitLab or GitHub repository, create a new repository, add the remote repository URL to your local project, and push your local commits to the remote repository using the "git push" command.

9.	What are the steps to collaborate with others using GitLab or GitHub?
    
•	Review collaboration policy in the project

•	Fork the repo

•	Clone forked repo

•	Update master branch

•	Create a branch - Make our improvements

•	Create a pull request

•	Sync a fork

•	Rebasing a pull request 

10.	How do you resolve merge conflicts in Git?
    
•	Manually edit the conflicted files by removing the special conflict markers, choosing which changes to keep from each branch, and then stage and commit the changes to finalize the merge

11.	What is a pull request, and why is it used in GitHub?
    
•	A pull request is a proposal to merge changes from one branch into another, allowing collaborators to review and discuss the proposed changes before integrating them into the main codebase.

12.	What are some best practices for writing commit messages?
    
1.	Specify the type of commit:
   
•	feat: The new feature you're adding to a particular application

•	fix: A bug fix

•	style: Feature and updates related to styling

•	refactor: Refactoring a specific section of the codebase

•	test: Everything related to testing

•	docs: Everything related to documentation

•	chore: Regular code maintenance.[ You can also use emojis to represent commit types]

2.	Separate the subject from the body with a blank line
   
3.	Your commit message should not contain any whitespace errors
   
4.	Remove unnecessary punctuation marks
   
5.	Do not end the subject line with a period
   
6.	Capitalize the subject line and each paragraph
    
7.	Use the imperative mood in the subject line

8.	Use the body to explain what changes you have made and why you made them.
    
9.	Do not assume the reviewer understands what the original problem was, ensure you add it.
    
10.	Do not think your code is self-explanatory
    
11.	Follow the commit convention defined by your team





 
Sources:
•	Worsley, S. (2022, April 7). What is Git? - The Complete Guide to Git. Datacamp.com; DataCamp. https://www.datacamp.com/blog/all-about-git

•	Git - Recording Changes to the Repository. (2020). Git-Scm.com. https://git-scm.com/book/ms/v2/Git-Basics-Recording-Changes-to-the-Repository

•	10 Git Commands Every Developer Should Know. (2020, January 19). FreeCodeCamp.org. https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/

•	Basic Git Commands You Need to Know | Simplilearn. (n.d.). Simplilearn.com. https://www.simplilearn.com/tutorials/git-tutorial/git-commands

•	GeeksforGeeks. (2024b, July 23). Difference between GitLab and GitHub. GeeksforGeeks. https://www.geeksforgeeks.org/difference-between-gitlab-and-github/

•	McKenzie, C. (2024). How to git push an existing project to GitLab. Theserverside.com; TheServerSide.com. https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-add-and-push-an-existing-project-to-GitLab

•	How to collaborate with a GitHub project. (n.d.). Gist. https://gist.github.com/neklaf/9002d3acccf6b6e448db5c4c4e8764c0

•	About pull requests - GitHub Docs. (n.d.). GitHub Docs. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

•	Ayodeji, B. (2024, September 10). How to write good commit Messages: A practical Git guide. freeCodeCamp.org. https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/


