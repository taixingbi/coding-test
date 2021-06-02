 #### 1. What is Git?
Git is a **version control system** for tracking changes in computer files and is used to help **coordinate work among several people** on a project while tracking progress over time.

#### 2. What do you understand by the term ‘Version Control System’?
A version control system (VCS) is a system that **records all changes made to a file or set of data**, so a specific version may be called later if needed.

#### 3. git vs github
| Git  | Github |
| ------------- | ------------- |
| version control system for tracking changes in computer files. The main point of Git is to manage projects, or a set of them when changes are made over time. It helps to track progress over time and coordinate work among several people on a project.  |  provides a web-based graphical interface. GitHub helps every team member to work together on the project from anywhere, making collaboration easy.  |


#### 4. Explain the git push command.
The Git push command is used to **push the content in a local repository to a remote repository**. After a local repository has been modified, a push is executed to share the modifications with remote team members.

#### 5. Difference between git fetch and git pull.
| Git fetch | Git pull |
| ------------- | ------------- |
| Git fetches only downloads new data from a remote repository | Git pull updates the **current HEAD branch with the latest changes** from the remote server |
| It does not integrate any of these new data into your working files | Downloads new data and integrate it with the current working files. |
| Can be done any time to update the remote-tracking branches | Tries to merge remote changes with your local ones |

#### 6. What is a merge conflict in Git?
A merge conflict is an event that takes place when Git is unable to **resolve differences in code between the two commits automatically**. 

#### 7. What is the difference between fork, branch, and clone?
| Fork | Branch | Clone |
| ------------- | ------------- |------------- |
| The fork is the process when a copy of the repository is made. It's usually experimentation in the project without affecting the original project. They’re used to **advise changes or take inspiration from someone else’s project**. | Git branches refer to **individual projects within a git repository**. If there are several branches in a repository, then each branch can have entirely different files and folders. | Git clone refers to creating a clone or a **copy of an existing git** repository in a new directory. Cloning automatically creates a connection that points back to the original repository, which makes it very easy to interact with the central repository. |

#### 8.  What is the difference between git merge and git rebase?
Incorporates all the new commits in the master branch
Rewrites the project history by **creating brand new commits for each commit in the original branch**

