# Mastring GET .. 

**A. Learning version control..** 

*the mean of **version control** : is a system that allows you to revisit various versions of a file or set of files by recording changes.*

**Some other Possibility of version control :**

1- *one can revert a file or project to a previous version.*

2- *track modifications and modifying individuals.*

3- *compare changes.*

**Types of version control :**

1- *Local Version Control.*

2- *Centralized Version Control.*

3- *Distributed Version Control.*

*for more info go the link here : [Link](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#2)*

**B. History of get..**

*Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.*


**C. Geting Starting..**

*just Follow the [Link](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#4) and do the instruction carfully.*



**D. Setting up a Git Repositry..**

1- **Importing:**


A. *Switch to the target project’s directory*


**Example:**
$ cd test (cd = change directory)

B. *Use the git init command* :
> $ git init



C. *start tracking these repository files*

 *perform an initial commit by typing the following:*

> $ git add *.c

> $ git add LICENSE

> $ git commit -m “any message here”

2- **Cloning:**

A. *You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:*

> $ git clone https://github.com/test

B. *To clone a repository into a directory with another name of your choosing, use the following command format:

>$ git clone https://github.com/test mydirectory

**E. Workflow of GIT:**

1- **Local Repository Structure:** it have 3 components.

a. *Working Directory: The actual files reside here.*

b. *Index: The area used for staging.*

c. *Head: Points to the most recent commit.*

2- **Saving Changes:** the file can be tracked or untracked.

a. *Tracked :Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.*

b. *Untracked :Untracked files were not in the last snapshot and do not currently reside in the staging area.*

3- **The Life Cycle of File Status:**

a. *After you edit a file, Git flags it as modified because of changes made after the previous commit.*

b. *You stage the modified file.*

c. *Then, you commit staged changes.*

4- **Check File Status:**

a. *Track one file only by using the following format:*

> git add filename

b. *After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:*

> $ git status

> On branch master

> Changes to be committed:

  > (use "git reset HEAD ..." to unstage)
new file: EXAMPLE


5- **Commiting a file:**

* just do the following format :
> $ git commit -m

6- **Committing All Changes:**

* just do the following format :
> $ git commit -a


7- **Pushing Changes:**

* just do the following format :
> $ git push origin master

