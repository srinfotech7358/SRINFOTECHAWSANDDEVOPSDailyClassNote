# SRINFOTECHAWSANDDEVOPSDailyClassNote










27/07/2025_Demo::
==================


In Demo session we have Overview of the all CI/CD tools & AWS Road Map


<img width="1909" height="725" alt="image" src="https://github.com/user-attachments/assets/61ba06cc-e465-488c-8611-05da91992c12" />


<img width="1504" height="574" alt="image" src="https://github.com/user-attachments/assets/c9549092-707d-44da-bab3-797f161a582e" />




01/08/2025_Tools Overview::
==============================



1.Overview about the all CI/CD & AWSDevOps Training flow

2.Discussed about the all the DevOps roles



<img width="1909" height="725" alt="image" src="https://github.com/user-attachments/assets/61ba06cc-e465-488c-8611-05da91992c12" />


<img width="1504" height="574" alt="image" src="https://github.com/user-attachments/assets/c9549092-707d-44da-bab3-797f161a582e" />


DevOps::
DevOps is a software development and operations (DevOps) methodology that combines these two to improve efficiency and speed up project deliverables, It's very important because it helps businesses/deliver software faster and with higher quality.

What is the key purpose of DevOps? 

The primary goal of DevOps is to bridge the gap between development and operations teams. It creates a streamlined, efficient workflow that delivers software faster and with higher quality. DevOps is a set of practices,tools that automate and integrate the processes between software development and IT teams.

DevOps Engineer Roles::
=========================

1)The devops engineer was responsibility to release the product to the market as soon as possible 

2) release the product speed to the market

3)Devops engineer was give continues feedback to the developers 

4) Devops engineer responsibility start from git and end with production

5) Design, build, and maintain Continuous Integration and Continuous Delivery (CI/CD) pipelines.

6) Automate the build, test, and deployment processes.


   
Benefits of DevOps ::
=======================

1) Faster software delivery

2)Reduces lead times and speeds up the software delivery process • 

3)Higher software quality

4)Addresses bugs quicker and improves software quality 

5)Better collaboration

6)Unifies development and operations teams, enhancing collaboration and efficiency 

7)Competitive advantage: Creates a more nimble software development lifecycle that gives businesses an advantage over their competitors





02/08/2025::
==============



What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security.


<img width="1200" height="633" alt="image" src="https://github.com/user-attachments/assets/f2b31798-6591-4464-9f7d-ecb9a7c96f96" />



Install Git in you local machine::
=====================================

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60c63d76-3cc5-4183-ab00-6284111858da" />





GitHub account creation::
=============================

For creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/96cb1d99-753a-4ff5-8221-29145a3f29e3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d8246f56-598d-424c-a752-28c72401c510" />


Github::
==========

Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: 
===================

storage area of your source code. Create a Repository on GitHub  

OR

Repositories::	
==============

Storage spaces for your project files and history. Think of it as a folder for a project.


Github Introduction::
==================

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: :: GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.


click Repositories


<img width="1276" height="648" alt="image" src="https://github.com/user-attachments/assets/529103b6-d817-43c6-ab26-38ef98339411" />


Click New

<img width="1325" height="655" alt="image" src="https://github.com/user-attachments/assets/148ac26f-214c-4a45-ae9f-ca7104ba9c7a" />


Enter Repository Name::SRINFOTECHDEMO

<img width="1311" height="662" alt="image" src="https://github.com/user-attachments/assets/4c8d604c-4fea-454c-b12f-fa295d1ab792" />


Public:: Anyone on the internet can see this repository.

<img width="1300" height="604" alt="image" src="https://github.com/user-attachments/assets/3c884a24-87bf-48b6-bd28-c4a6a67ab5d8" />

Private:: You choose who can see and commit to this repository.

select Add a README file

<img width="1346" height="699" alt="image" src="https://github.com/user-attachments/assets/73c29693-cf1f-40c4-bb41-d64f3a7fdc91" />


Click Create Repository

<img width="1315" height="702" alt="image" src="https://github.com/user-attachments/assets/934eec8d-6734-4111-b4c2-819ef835f57a" />

Repository Created SUccessfully with Default branch main

<img width="1317" height="697" alt="image" src="https://github.com/user-attachments/assets/ad4a2344-159b-49e4-a83e-e85df6fdbb53" />



04/08/2025::
==========


git commands::
================

git commands::

---git clone <github repository url>

>git clone https://github.com/srinfotechbatch3/DevOpsDemo.git

>git status

>git add --all

>git commit -m "i have added hello world .java class"

>git push

if we get any Access denied issues during push the changes from local to remote repository,please be authenticate below commands

>git config --global user.name "srinfotechbatch3"

>git config --global user.email "srinfotechbatch3@gmail.com"


Generate SSHKeys:: to Integarte Git to Github
==============================================

syntax::ssh-keygen -t ed25519 -C "your_email@example.com"


>ssh-keygen -t ed25519 -C "srinfotechbatch3@gmail.com"

Keys avaibale path and save the key (/c/Users/HP/.ssh/id_ed25519):

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/036b310b-0c16-4bc1-b4ef-0bd479450509" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/148e65ae-7023-4b85-9c43-3edbaa9c04c7" />


Please follow below links for more understanding 

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account

Go to -->Your Copilot


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c7a3749-757f-4adc-bcd8-ca328330858f" />




Click SSH and GPG Keys

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f7fb1aa6-52c0-47f6-a378-99475c0a9b43" />



click New SSH Key

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ad66cb42-82af-48ca-b1c3-01ab480e17a7" />



Add new SSH Key and click Add SSH Key


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/df130ae9-0e1b-4041-8dbd-a878088e69cf" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1adfb3b1-e41c-453d-a035-29a54dd67d77" />



Lab Practice::
==============

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3
$ git clone git@github.com:srinfotechbatch3/DevOpsDemo.git
Cloning into 'DevOpsDemo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3
$ cd DevOpsDemo

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'HelloWorld.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git commit -m "i have added hello world .java class"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HP@DESKTOP-3GU6R56.(none)')

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git config --global user.email "srinfotechbatch3@gmail.com"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git config --global user.name "srinfotechbatch3"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git commit -m "i have added hello world .java class"
[main b28db23] i have added hello world .java class
 3 files changed, 48 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 806 bytes | 268.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch3/DevOpsDemo.git
   5e31d17..b28db23  main -> main

HP@DESKTOP-3GU6R56 MIN



Fork in Github::
====================

In GitHub, forking is a way to create your own copy of someone else's repository. example please fork below project to your own github account

https://github.com/srinfotechbatch3/DevOpsDemo


steps to fork the project::
============================

Go to Above Project URL

https://github.com/srinfotechbatch3/DevOpsDemo

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45b0c823-863d-447b-943e-a32cbfc6cb65" />


at top right we can found Fork option in github Account 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/406477ce-4851-462c-9187-30e50320c4f7" />


Click on Fork and click create Fork 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f399adbd-d00c-4cd9-9dd3-9a0e16170aa5" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/59c07b24-f750-41ba-851c-4f2b6712ccaf" />


Successfully Fork done from someone else's repository 

once above steps done ,please clone the Project and Modified files and push to github repository





05/08/2025::
===============

Github branching strategy::
===========================

Github Branching Model::
-------------------------------

A GitHub branching model is a structured way of organizing branches in a Git repository to manage development workflows effectively. It helps teams work collaboratively, isolate features, manage releases, and deploy code more efficiently.

<img width="1738" height="779" alt="image" src="https://github.com/user-attachments/assets/38d0bb86-0465-462b-b6e2-85b9adb23d68" />


A GitHub branching strategy is crucial for maintaining an organized workflow in version control. There are different strategies depending on the size of the project, the number of team members, and the desired workflow. Here are some common branching strategies used in GitHub:

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.08.05

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.08.10

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.

cloning references::

![image](https://github.com/user-attachments/assets/87f6ed4a-095b-4faa-854a-7fcdc019f31f)



Create New Branch::
=================

Click Branches


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a795a257-a126-449e-9dba-22729bec940d" />

Find New Branch at Right side and click

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2b5fbd36-953e-45e0-baef-450c680b7e5f" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/17de84ed-cc93-4b01-8f32-5a1ff0ddf3ee" />

New feature Branch Formate----> feature/YYYY.MM.DD

feature/2025.08.05


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60902962-ec6c-4c9f-90eb-04c9835a64d0" />

click create New Branch 

Branch Created Successfully

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6821e5f-3b54-406d-a4ae-7f2fd885974f" />



Branches:
==============


main (or master): Always production-ready.

feature/*: Used for new features.

release/*: Prepares for a new production release.

main or master branch:: 
=====================

This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically. main or master branch always stable and live code

feature branch:: 
===============

It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: 
=============

feature/YYYY.MM.DD feature/2025.06.22

release branch:: 
====================

Based on the release we have created release branch accourdingly and starts the next release cycle. always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.07.20

hotfix branch:: 
==================

always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes


Raise PR (Pull Request) :: 
=================================

Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/baf5a7d7-f69d-44e8-87ad-ae67d082353f" />


Click New Pull Request::

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/68456b4f-bd40-41b6-a238-25439f97dff4" />


please select base & compare branches so here base branch is release/2025.08.10 and compare branch is feature/2025.08.05

i'm going to merge code changes from feature branch to release branch 


click create pull request

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b7a39c0-7a34-45c9-812b-ca518d1a441a" />


![image](https://github.com/user-attachments/assets/08a98671-c810-46fc-9024-17bae7538a61)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e36c29e8-3c38-4579-8073-58ac6304e6fd" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dc582d4a-e173-4648-a76c-3aebd7869b5b" />


click merge request

![image](https://github.com/user-attachments/assets/44a4b84e-1aef-4b19-a93e-64e48b362b29)

 Open
srinfotechbatch3 wants to merge 1 commit into main from feature/2025.08.05

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5a70ee7d-fc8e-45aa-bb28-6a445a223cf0" />


confirm merge

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6e9ab2f-30cc-4fe2-9754-03f6f6262786" />


Merged

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8dfb8ae-1a1c-4245-a4ee-944db6bbd07e" />


LAB Practice::
==============

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3
$ git clone git@github.com:srinfotechbatch3/DevOpsDemo.git
Cloning into 'DevOpsDemo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3
$ cd DevOpsDemo

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'HelloWorld.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git commit -m "i have added hello world .java class"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HP@DESKTOP-3GU6R56.(none)')

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git config --global user.email "srinfotechbatch3@gmail.com"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git config --global user.name "srinfotechbatch3"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git commit -m "i have added hello world .java class"
[main b28db23] i have added hello world .java class
 3 files changed, 48 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/SR Infotech Batch3/DevOpsDemo (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 806 bytes | 268.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch3/DevOpsDemo.git
   5e31d17..b28db23  main -> main





06/07/2025::
===============



Avoide conflicts in RealTime Scenarious::
=================



If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the  conflicts issues and how to resolved those conflicts issues in real time projects 


![image](https://github.com/user-attachments/assets/f2ebe341-83c5-486d-ba0d-329854190105)



<img width="1166" height="704" alt="image" src="https://github.com/user-attachments/assets/005333f6-17e0-4a81-a2e9-71ab93a96202" />


>git pull --->git pull command is use, copies changes from a remote repository directly into your working directory (local directory) and merged code changes from remote repository to local repository 

>git fetch ---->The git fetch command only fetch the changes into your local Git repo and it will not merged anything. just fetch the details

Please create developer1,developer2,developer3 directories in your local machine and clone the project code separately 

![image](https://github.com/user-attachments/assets/a0345422-a025-4c3a-84c5-737b98244a6a)


![image](https://github.com/user-attachments/assets/3296003f-c8c7-42c8-bdca-3270576aaa57)


![image](https://github.com/user-attachments/assets/7e786310-5092-4975-9eb9-7b18801353d8)

Editor steps for Resolved the conflicts::

resolved conflicts::

>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter

Developer1 Activity::
=====================

 git checkout feature/2025.02.27
error: pathspec 'feature/2025.02.27' did not match any file(s) known to git

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git pull
From github.com:parasa7358/spring-petclinic
 * [new branch]      feature/2025.02.27 -> origin/feature/2025.02.27
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git checkout feature/2025.02.27
branch 'feature/2025.02.27' set up to track 'origin/feature/2025.02.27'.
Switched to a new branch 'feature/2025.02.27'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Jenkinsfile

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git commit -m "Added jenkins file for Feb Release"
[feature/2025.02.27 9ad4ee0] Added jenkins file for Feb Release
 1 file changed, 22 insertions(+)
 create mode 100644 Jenkinsfile

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 483 bytes | 241.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:parasa7358/spring-petclinic.git
   e4b9aa2..9ad4ee0  feature/2025.02.27 -> feature/2025.02.27


Developer2  Activity::
=========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git pull
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 586 bytes | 293.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   9ad4ee0..ed57c5e  feature/2025.02.27 -> feature/2025.02.27


Developer3  Activity::
========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 33, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 1.14 KiB | 233.00 KiB/s, done.
Total 13 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 5 local objects.
To github.com:parasa7358/spring-petclinic.git
   ed57c5e..80681f1  feature


   Please be practice above 3 developers activity in real time bases 

>git fetch--->just fetch

>git pull -->fetch+merged


Git All the Commands::
==========================

Git commands::
==============
1.git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

9.git checkout <branchname>

   git checkout feature/2025.06.22
   
10.git pull  --->every devlioper beforre pushing their changes we should make sure git pull the every time   
  

clone      Clone a repository into a new directory

add        Add files

status     Show the working tree status

commit     Record changes to the repository

 pull       Fetch from and integrate with another repository or a local branch
 
 push       Update remote refs along with associated objects





07/08/2025
==============


Jenkins Introductiion::
============================
Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


<img width="1830" height="755" alt="image" src="https://github.com/user-attachments/assets/a4164755-6340-4024-9295-bcadc65a3000" />


Roles And Responsibilities::
================================
1)The devops engineer was responsibility to release the product to the market as soon as possible 

2)release the product speed to the market 

3)Devops engineer was give continues feedback to the developers 4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment 
when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Tutorials::
============

https://www.tutorialspoint.com/jenkins/jenkins_overview.htm https://www.geeksforgeeks.org/jenkins-tutorial/#prerequisites

Download JDK 17 ::
================

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	

https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Windows Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.516.1 LTS for:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ad241e7-3ae0-4f30-8ef2-33af47891c5b" />


Jenkins.war file is downloaded


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98751ae3-bfde-45fc-8863-1f1eb1d954eb" />



Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)





11/08/2025::
===============

Jenkins Introductiion::
============================
Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


<img width="1830" height="755" alt="image" src="https://github.com/user-attachments/assets/a4164755-6340-4024-9295-bcadc65a3000" />


Download JDK 17 ::
================

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	

https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Windows Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done


Maven setup::
=============

Maven is a powerful build automation and project management tool, primarily used with Java projects

Please follow the below link for more understading the Maven lifecycles OR maven Goals

https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html

MAVEN_HOME=C:\Users\HP\Downloads\apache-maven-3.9.9-bin\apache-maven-3.9.9

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fca1b236-b778-490e-abec-61298f74bb9d" />


Download link

https://maven.apache.org/download.cgi


Make sure we should setup the path at system variable 

JAVA_HOME & MAVEN_HOME

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c7c2c771-4be4-4488-83b4-c3b9172beca3" />



now verify the java version & maven version:: go to git bash and verify. below are refreenced screenshots

> java -version


C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/638553a1-2319-43c3-89e3-4e9cd949a634" />


> mvn -v

C:\Users\HP>mvn -v
Apache Maven 3.8.9 (e26b057cc3a17459358ef53e4d0e2e381bf08a1c)
Maven home: C:\Users\HP\Downloads\apache-maven-3.8.9-bin\apache-maven-3.8.9
Java version: 17.0.12, vendor: Oracle Corporation, runtime: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
Default locale: en_IN, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/329d0a8b-1d56-4d27-957d-a779c236224b" />



once above setup is ready then we will proceed to installe jenkins

Common Maven Commands::
==========================

1.mvn clean         # Clean up previous builds

2.mvn compile       # Compile source code

3.mvn test          # Run unit tests

4.mvn package       # Create a JAR/WAR

5.mvn install       # Install package into local repo
6.mvn clean install        # Deploy package to remote repo




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.516.1 LTS for:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ad241e7-3ae0-4f30-8ef2-33af47891c5b" />


Jenkins.war file is downloaded


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98751ae3-bfde-45fc-8863-1f1eb1d954eb" />



Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/8a80769d-672b-42c4-ad59-bdb5a288abc7" />


click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/e11ae91e-ec78-42e1-b64d-19696755931a" />



Create sample Freestyle project::
============================

Github Project URL:::
=====================

https://github.com/srinfotechbatch3/spring-petclinic



Click New Item

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e8a51a17-f3f8-4719-95f0-551ad8e2fb4f" />

Enter an item name     ---->This Should be Name of your Project

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/adebc306-828a-4920-bb47-63d8fe060c67" />


Click OK


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/515589a7-463e-4209-94e5-cf6c2ce6caab" />



General Section provide the Project/job description 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a92f0756-1444-490e-a60b-d3c48bc4be84" />


At SCM stage level select the Git and provide the github details


https://github.com/srinfotechbatch3/spring-petclinic

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6f736b3a-6179-4a86-a56b-08d76c22ffdd" />


Branches to build

main branch and this branch should match with github repository branch


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8d4094c2-e384-4a08-b699-1e4fc4625656" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b392b9e0-631c-404d-bcd7-3e26c096fb16" />


Build steps::select the Invoke top-level Maven targets

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/659cddb4-e8fd-44b8-a6c6-1e77a62eaf1b" />


Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

>mvn compile

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3444e4a2-865d-41ce-be9e-aa8e8da44d67" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d877e99a-1e20-4ddc-b061-81a585b67ea5" />




12/08/2025::
=================

Please find the Project Github URL's::
====================================

Spring-Petclininc::

https://github.com/srinfotechbatch3/spring-petclinic.git

Onlinebookstore::

https://github.com/srinfotechbatch3/onlinebookstore.git


Please try to create the New Job in Jenkins for Onlinebookstore Project and do the Build::
=========================================================================================


Click New Item

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e8a51a17-f3f8-4719-95f0-551ad8e2fb4f" />


steps::

Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


Enter Description

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f567edc3-95b2-4719-b331-8e7d5663dd0d" />


Provide the Repository URL

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a48dc090-ed74-4765-814e-edb68d495ec5" />

Provide the Specific Branch

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8cf5ff7b-0286-40a9-8c91-eb05cd6f2f1a" />


Build Steps----> select Invoke top-level Maven targets

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c6c30305-7713-4180-b717-00bb1b76527c" />


Click Save

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/91fdc2ce-42c2-437a-aafb-8f881133b9bc" />


Click Build Now

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3403704e-5790-427a-aac4-0d0c2df86a20" />


Build is Inprogress


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1c59da0f-85f4-4265-8979-a50536fc23af" />



Poll SCM ::
=================

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 


<img width="1118" height="641" alt="image" src="https://github.com/user-attachments/assets/39aa389b-fecf-4ea6-aa46-7fbe42ef5b58" />



POLL SCM ----* * * * * --every minute when every commit 



Create one sample POLL SCM jenkins job::
===========================================
Go to jenkins Dashboard

click New Item



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e8a51a17-f3f8-4719-95f0-551ad8e2fb4f" />


Description


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/759be7e4-4d08-449e-a6e4-1cf4ae894d77" />



Provide the Git URL

https://github.com/srinfotechbatch3/spring-petclinic.git

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3fdcb434-bd51-4b75-937b-febb013e5b31" />



Branch buiild

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4ba819e5-f109-4dea-8906-7ea252435297" />


POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8228751-5212-41f6-a7a5-cdca52d94afc" />


Crone Job URL::
==================

https://crontab.guru/examples.html

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8de3a3f9-a60e-4926-b10a-edc719724940" />



Build Steps----> select Invoke top-level Maven targets

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c6c30305-7713-4180-b717-00bb1b76527c" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/460714dc-e89c-4ad1-aa73-a4a91ec74938" />

Click Save

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/91fdc2ce-42c2-437a-aafb-8f881133b9bc" />


NOTE:: 
==========

Please Modified any code in project and push those changes to Github Repository , make sure should Enbaled POLL SCM then Automatic Build happend every new Commits.

POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository



LAB Practice::
=============

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3
$ git clone git@github.com:srinfotechbatch3/spring-petclinic.git
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 10774, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 10774 (delta 5), reused 4 (delta 4), pack-reused 10767 (from 2)
Receiving objects: 100% (10774/10774), 7.85 MiB | 527.00 KiB/s, done.
Resolving deltas: 100% (4049/4049), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3
$ cd spring-petclinic

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (main)
$ git checkout feature/2025.08.12
error: pathspec 'feature/2025.08.12' did not match any file(s) known to git

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (main)
$ git pull
From github.com:srinfotechbatch3/spring-petclinic
 * [new branch]      feature/2025.08.12 -> origin/feature/2025.08.12
Already up to date.

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (main)
$ git checkout feature/2025.08.12
branch 'feature/2025.08.12' set up to track 'origin/feature/2025.08.12'.
Switched to a new branch 'feature/2025.08.12'

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git status
On branch feature/2025.08.12
Your branch is up to date with 'origin/feature/2025.08.12'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git status
On branch feature/2025.08.12
Your branch is up to date with 'origin/feature/2025.08.12'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   pom.xml


HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git commit -m "updated pom.xml for artifacts formates"
[feature/2025.08.12 e1bd446] updated pom.xml for artifacts formates
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 328 bytes | 328.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch3/spring-petclinic.git
   30aab0a..e1bd446  feature/2025.08.12 -> feature/2025.08.12

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git status
On branch feature/2025.08.12
Your branch is up to date with 'origin/feature/2025.08.12'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git status
On branch feature/2025.08.12
Your branch is up to date with 'origin/feature/2025.08.12'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   pom.xml


HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git commit -m "reverted the artifact formate"
[feature/2025.08.12 ac7172d] reverted the artifact formate
 1 file changed, 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 295 bytes | 24.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch3/spring-petclinic.git
   e1bd446..ac7172d  feature/2025.08.12 -> feature/2025.08.12

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git commit -m "reverted the artifact formate"
[feature/2025.08.12 90cfd57] reverted the artifact formate
 1 file changed, 1 insertion(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Downloads/SR INFOTECH Batch3/spring-petclinic (feature/2025.08.12)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch3/spring-petclinic.git
   ac7172d..90cfd57  feature/2025.08.12 -> feature/2025.08.12



14/08/2025::
================

Poll SCM ::
================

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

![image](https://github.com/user-attachments/assets/6f436ad6-e92a-40e3-831a-23219c288217)

POLL SCM ----* * * * * --every minute when every commit 

Build Periodically:::	
============================

H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Please create a New Jenkins jobs both POLL SCM & Build Periodically 

https://github.com/srinfotechbatch2/spring-petclinic.git

https://github.com/srinfotechbatch2/onlinebookstore.git

Automatically Discard Old Builds:::
==============================
To automate the process of discarding old builds, you can configure the job’s settings to automatically delete old builds based on criteria such as the number of builds to keep or the age of the builds.

Follow these steps:

Open the Jenkins job (project).
Click on Configure (on the left-hand side).
Scroll down to the Build Discarder section (usually under the Build Triggers section).
Check Discard old builds.
Specify the following options:
Max # of builds to keep: Set the maximum number of builds to keep.
Max days to keep builds: Set the maximum age for builds to keep.
Save the configuration by clicking Save.


![image](https://github.com/user-attachments/assets/8d8c9cf9-988a-41e4-b052-539ef601171f)


Execute concurrent builds if necessary::
===================================

When this option is checked, multiple builds of this project may be executed in parallel.
By default, only a single build of a project is executed at a time — any other requests to start building that project will remain in the build queue until the first build is complete.


![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Here 5 builds execute parallel ,I kept executor is 5 this is same machine 

![image](https://github.com/user-attachments/assets/a840a224-5cbb-43cc-92c1-d135db4ce00f)


Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints 

build happened in Jenkins 

Execute the Jobs in Parallel::
==============================


1.By Default execute the Jenkins build jobs are sequence way,one by one 

2.Don’t do 2 projects build parallel  this is real time scenario but we can do parallel builds as well one job

Jenkins build parallel setup

Go job ---> configure ----> Generall ---> Execute concurrent builds if necessary


![image](https://github.com/user-attachments/assets/3216a68f-b10b-44cd-83b5-b62c27525296)


![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Here 5 builds execute parallel ,I kept executor is 5 this is same machine 

![image](https://github.com/user-attachments/assets/a840a224-5cbb-43cc-92c1-d135db4ce00f)


Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 

Create Sample Build peridiocally jenkins job::
=============================================

Description

![image](https://github.com/user-attachments/assets/5ad69478-039e-4ef7-a35f-cb18ed8364f1)

Git url::

![image](https://github.com/user-attachments/assets/b2cbdb7c-14ac-4fae-a240-90cc7a82c78d)

Build the branch

![image](https://github.com/user-attachments/assets/94230c57-b88f-4ab1-b894-151f30fa6d53)

every 5 mints build will trigger

Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 
![image](https://github.com/user-attachments/assets/a5321109-944b-4e79-9294-e28c2adfea0d)

click save 



Whenever you configure a build activities :::
=======================================

SCM::

	Where is your project

Build environment::

---all about your workspace folders 

Build Triggers::

--whenever code changes 
--periodic
---script calls 

Build steps::

Dev team will tell ,

Post build::

That aim is giving continue feedback to dev team



15/08/2025::
================


Published Artifacts & Test Results::
===================================


<img width="1009" height="591" alt="image" src="https://github.com/user-attachments/assets/db2cc6c4-ba76-4836-8d34-ce655fb6637c" />

Post build Action i want to published artifacts & test results

![image](https://github.com/user-attachments/assets/fcd3ea28-a352-431f-8e1b-86758787fe7a)

I'm going to created one free style job and configured Post-build Actions

In post build Action select the option Archive the artifacts

>target/*.war  OR target/*.jar  OR target/*.zip  OR target/*.ear

![image](https://github.com/user-attachments/assets/44f88d03-d9c8-4800-88e2-06217f721d5c)

![image](https://github.com/user-attachments/assets/7ed9efc9-6a45-4eff-a789-0b7fe50c6024)


In post build Action select the option Publish JUnit test result report for to published the test results

>target/surefire-reports/*.xml


![image](https://github.com/user-attachments/assets/e3c17557-410c-4915-bec3-2ec5edee6526)



I want to show test results ::
=================================


>ls target 

Post build action stage

Select archive the artifact
--target/*.jar

Junit test results::
--target/surefire-reports/*.xml

See test results & antifactory ::
===================================


![image](https://github.com/user-attachments/assets/819809c2-3611-45e0-abd0-0139b29d166b)




3.For every company will do sequence build on one project this is recommended approach



General  ---just descriptin

SCM

where is your project--github, bitbucket

Triggere

whenever code changes i want build the project given time

Environmant

--all about workspaces folders

Build Steps

dev team will tell which tool we are using in current project


Post Build

devops engineer is aim is given continue feedback to dev team via email notification


Parameterized Jenkins Jobs ::
===============================

Run the same job with different inputs without modifying the configuration manually

Go To New Item

![image](https://github.com/user-attachments/assets/695a7137-6283-462b-8ff7-37ffb4f6ff68)


Enter Job Name, Free style project and click ok

![image](https://github.com/user-attachments/assets/da12fe42-db98-40e1-af80-1ba335b50596)



Enter the description

![image](https://github.com/user-attachments/assets/cd3c1d8f-d403-4694-a830-1084796c80ad)


Select the option This project is parameterised

![image](https://github.com/user-attachments/assets/e2fb86d9-ea5b-4981-a3ee-81d4645d06c1)


Click Add Parameter

![image](https://github.com/user-attachments/assets/2702952d-1e31-4432-a405-88f509bfc58c)


Select optiions String parameter or choise parameter or boolean parameter you can select the ny options based on your requirement 

![image](https://github.com/user-attachments/assets/1b18b622-c141-4988-bdc3-785359a04e99)


select string parameter

![image](https://github.com/user-attachments/assets/33215729-9b13-46bf-bbbb-b08416979dd6)


Select Choise Parameter

![image](https://github.com/user-attachments/assets/59b8db99-1196-4024-9cdf-b3a80a358f81)


choise parameter

![image](https://github.com/user-attachments/assets/952de313-ebde-4b39-be7b-c31c6b0ca283)


Click Save

![image](https://github.com/user-attachments/assets/4f19f2ba-c85b-4adf-9dd0-16da436011dd)


You Can observed this project is parameterized 

![image](https://github.com/user-attachments/assets/fef0f526-c9f2-4dec-8d0e-960efc94d09c)


Click Build with parameter

![image](https://github.com/user-attachments/assets/1cbeb32c-bd23-4d87-87be-8e6d010bb968)


select deployment environment

![image](https://github.com/user-attachments/assets/af62b4d7-b107-4856-b567-d010efb3a11a)


select which versioj you want to deployment like tis you can configured real time parameterized project in jenkins

![image](https://github.com/user-attachments/assets/506da743-2efd-4e19-8082-67592c3c24b1)


Click Build

![image](https://github.com/user-attachments/assets/9554cd4a-ba9a-4821-af2e-638d554632a8)


![image](https://github.com/user-attachments/assets/28afabd9-1c84-4313-95c6-1ec8bd50488d)


Email Notifications::
=======================

1.Setting up Jenkins Email Notifications allows you to alert your team when a build passes, fails, or encounters issues. Here's a step-by-step guide to configure it

2. give continues Feedback to the Dev team via Email when a build passes, fails


<img width="1585" height="700" alt="image" src="https://github.com/user-attachments/assets/c771d171-c45a-486c-9a50-2573421a81d4" />


Steps::

Go to mail 


![image](https://github.com/user-attachments/assets/e6764012-c4e8-43ab-bea7-0fcf11c61f5e)

Click manage your google account

![image](https://github.com/user-attachments/assets/b2b0e9e5-66ff-4713-b95b-0cc3cc2ecf42)


Click Security


![image](https://github.com/user-attachments/assets/acc069d3-2944-43d7-a0d0-a0ae17b478d6)


Click protect your account


![image](https://github.com/user-attachments/assets/a80aa65d-210c-4920-ac59-bff59d001048)

Click Add phone number

![image](https://github.com/user-attachments/assets/d3839125-e302-40a0-a942-497f50f2e08a)

Click add phone

![image](https://github.com/user-attachments/assets/758cb87d-c0df-43d1-890a-6539046b86f7)

![image](https://github.com/user-attachments/assets/e532e1dd-fef8-4ed6-b46c-075d97cdd10d)

![image](https://github.com/user-attachments/assets/96dde956-0cb9-4125-bc16-9b18b5a47883)

Make sure your account is protected 

![image](https://github.com/user-attachments/assets/ef101b4f-f98a-4941-83bb-e99c98a7b583)


Make sure 2-steps Verification is ON


![image](https://github.com/user-attachments/assets/eb82b19f-0ae0-4df4-8c79-463769e0f2cf)


Credentials:

In search box App Password


![image](https://github.com/user-attachments/assets/20789330-ae4d-407d-b55c-201452435d33)

![image](https://github.com/user-attachments/assets/45634fa0-7198-4a55-9ce3-bd5c7c7b4c2d)


![image](https://github.com/user-attachments/assets/d9e2b041-0e63-42de-96be-0b2406113328)


![image](https://github.com/user-attachments/assets/814dc39c-290f-4035-bec8-6871cfd44467)


 we should provide this password in Jenkins Email configuration level


![image](https://github.com/user-attachments/assets/b1cde092-d3ed-4ae8-b9fb-e3fd32095fce)


Go to Jenkins  ---> Manage Jenkins

System configurations


![image](https://github.com/user-attachments/assets/e3467726-c6f8-45f5-b728-5012e2e906f3)



Go to Extended E-mail Notification



![image](https://github.com/user-attachments/assets/11351c43-ecf5-4327-86d9-a4bcde391589)


SMTP server  :: smtp.gmail.com

SMTP Port:: 465

Credentials::
Username:: Your Email
Password::Zvqxxvplduhrlffv

![image](https://github.com/user-attachments/assets/7e8c5e1a-785f-4b0e-b85c-f37b6f1123ce)



Select Use SSL

Default content type HTML

![image](https://github.com/user-attachments/assets/742a4252-a704-4a0c-ad2b-ae35e9c2a2e0)


Default Triggers

![image](https://github.com/user-attachments/assets/67d1fe48-b3f0-4d59-a842-054b11a3ed70)

E-mail Notification


![image](https://github.com/user-attachments/assets/dc3dfcd8-1454-434b-a88b-44acf32a3f56)


![image](https://github.com/user-attachments/assets/37414d6d-d388-4f21-840e-899b8c3e3bf1)


Use SMTP Authentication? –should selected

Use SSL select

Port 465

![image](https://github.com/user-attachments/assets/0c8e8c73-69bc-4a2b-a19e-f130e81f8c16)


Test configuration by sending test e-mail

![image](https://github.com/user-attachments/assets/b48d366e-5a52-458c-b80d-1c45b803e3ce)


Connection success

![image](https://github.com/user-attachments/assets/28f7fd8a-c85e-486a-b2f4-64af53b1db0a)


 Post build action


![image](https://github.com/user-attachments/assets/d386a9c7-a5cf-4a48-a6ab-5030c96288e0)


![image](https://github.com/user-attachments/assets/d200565f-7356-4470-b080-8ba7f731837c)


![image](https://github.com/user-attachments/assets/7cddd9fa-8498-47fa-a86b-5066ae058700)


![image](https://github.com/user-attachments/assets/60b129a8-5adf-43b1-9639-a293c59d929c)






18/08/2025::
===============


I want Build a 3 projects ::
===============================

<img width="1350" height="721" alt="image" src="https://github.com/user-attachments/assets/8065b647-87ab-4810-9aac-47a44c8dc2f5" />

Project-A, Projec -B, Projec - C

Once Project-A build is done, then it will start Project-B build and once Project-B build SUccess then it will start Project-C build ---for this we need to select Add post-build action and select "Build other projects" in drop down and provide Project-B details.


![image](https://github.com/user-attachments/assets/048a99bc-bcf6-47ca-9b27-ef23152eab97)


Projec A is  (Downstream project is ---Projec B)

Projec B is (UP Stream project is ----Projec A)

Projec C is (downstream project of --Projec B)

i created 3 free style project in jenkins 

Project-A ::
==============

Github URL::: https://github.com/parasa7358/spring-petclinic.git

![image](https://github.com/user-attachments/assets/e8073061-b815-4945-bd7f-c20b3a6576e2)

Post Build Action , select the option Build Other Project  Project-B

![image](https://github.com/user-attachments/assets/ef75f777-c273-4255-b063-f9853072dfcb)

Project -B ::
=============

Github URL:::https://github.com/parasa7358/onlinebookstore.git

![image](https://github.com/user-attachments/assets/2ee62e92-e677-4717-93be-77d6dd1ecbf9)

Post Build Action , select the option Build Other Project Project-C

![image](https://github.com/user-attachments/assets/ec7cfc18-002b-4dc3-8438-a75b12b9a438)


Project-C::
============


Github URL:::https://github.com/srinfotech7358/shopping-cart




Pipelines Introduction:::

A Jenkins pipeline is a series of automated steps or stages that define the process of continuous integration/continuous delivery (CI/CD) for your code. Jenkins, being a popular open-source automation server, uses pipelines to automate tasks like building, testing, and deploying code.

There are two types of Jenkins pipelines:

1. Declarative Pipeline

2. Scripted Pipeline

1. Declarative Pipeline::
The declarative pipeline syntax is simpler and more structured. It's the recommended style for most users because it's easy to read and maintain

Create Pipeline Project::
=======================

Steps

Click +New Item


![image](https://github.com/user-attachments/assets/43694be8-ac77-41a1-9d90-30175a91443f)

Enter the Project Name And Click OK

![image](https://github.com/user-attachments/assets/b21659a3-ff70-46ff-86b0-7a965b48197a)

At General Section Provide the Description

![image](https://github.com/user-attachments/assets/e0c5db89-597c-439e-91e1-7722bd4d5467)


At Definition, We need to select the Pipeline Script 

![image](https://github.com/user-attachments/assets/f9b35819-0b40-4d71-9678-949d35a4cd3e)



Here's an example of a simple declarative pipeline: Syntax

pipeline{

agent any

stages{

Stage ('Clone'){

steps{

// write code
}
}

Stage ('Build'){
steps{

// write code
}
// write code

}

Stage ('Test'){

steps{

// write code
}
// write code

}
Stage ('Execute test casea and get the results'){

steps{

// write code
}
// write code

}

Stage ('Generated Artifact'){

steps{

// write code
}
// write code

}

Stage ('Deploy'){

steps{

// write code
}
// write code

}

// write code

}

}

Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;


pipeline {

   agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
          stage('Test') {
            steps {
               bat 'mvn test'
            }
        }
        
          stage('Generate Junit Test Results') {
            steps {
               junit 'target/surefire-reports/*.xml'
            }
        }
        
          stage('Generate Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
    }
}


Plugins::
===============

Plugins in Jenkins are essential components that extend its core functionality, allowing you to customize Jenkins to meet specific CI/CD needs. Jenkins has a vast plugin ecosystem that supports building, deploying, and automating software projects across various platforms and tools

Install Plugins in Jenkins::
==============================

Step-by-Step:
Log in to Jenkins as an administrator.

Navigate to Manage Jenkins (usually on the left sidebar).

Click on Manage Plugins.

(Image reference from Jenkins documentation)

Go to the Available tab.

Use the search box to find the plugin you want.

Check the box next to the plugin name.

Click:

Pipeline: Stage View::
=================

Pipeline: Stage View Plugin in Jenkins
The Pipeline: Stage View plugin is a visualization tool in Jenkins that allows users to see a graphical view of each stage in a pipeline. It provides a real-time and historical overview of pipeline execution per stage, making it easier to debug, monitor, and analyze performance.


Click the Build Now and we can triggered the pipeline

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d267dd02-3b7e-48eb-bf13-142e3edd4bf1" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c264b007-283b-439f-a9fc-913ac56bed0c" />


Success all the stages & Steps

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82c6c941-91df-4313-8107-dc9115df3bd6" />



Key elements in the declarative pipeline:::
======================================
pipeline: This is the top-level structure.

agent: Specifies where the pipeline will run, such as on any available agent, a specific node, or a Docker container.

stages: Defines the different steps or stages in the pipeline (e.g., Build, Test, Deploy).

steps: Commands to be executed in each stage.






19/08/2025::
===============


Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;

pipeline {

agent any

stages {
    stage('Clone') {
        steps {
            git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
        }
    }
    
      stage('Build') {
        steps {
           bat 'mvn clean install'
        }
    }
      stage('Test') {
        steps {
           bat 'mvn test'
        }
    }
    
      stage('Generate Junit Test Results') {
        steps {
           junit 'target/surefire-reports/*.xml'
        }
    }
    
      stage('Generate Artifacts') {
        steps {
           archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
}
}


See test results & antifactory ::
================================

archive the artifact :: target/*.jar

Junit test results:: target/surefire-reports/*.xml

![image](https://github.com/user-attachments/assets/0649e7f3-4c6e-4767-8588-d561c5f9e685)


Pipeline as Code::
===================

Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.

![image](https://github.com/user-attachments/assets/7d3b20e8-e72f-41ff-94ce-0c912f51a93d)

![image](https://github.com/user-attachments/assets/edd96e0c-ac4d-438e-8a5b-97ae99ed1fda)




Pipeline as Code::
==================
Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.

Declarative pipeline with Jenkinsfile::
===============================

pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'git@github.com:parasa7358/spring-petclinic.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Test Results Reports') {
            steps {
                junit 'target/surefire-reports/*.xml'
            }
        }
        
        stage('Artifacts') {
            steps {
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}


This pipeline:::

1 Checks out the source code from your Git repository.

2. Builds the project using Maven.
   
3.Runs unit tests.

4.Deploys the application using a custom script.

JOb creation::

![image](https://github.com/user-attachments/assets/dacaf03a-5557-44ce-88ba-0b230ed061cb)

Branches to build

![image](https://github.com/user-attachments/assets/64065ba7-534e-4771-a667-00d5f64e5a4b)

Script Path::: This path is Jenkinsfiles where we maintained in github source code level

![image](https://github.com/user-attachments/assets/3b4783f0-c613-45d1-81a7-00712a79f5ad)


Scripted pipeline with Jenkinsfile::
===============================


node{

    stage('clone'){
        git branch: 'main', url: 'https://github.com/srinfotechbatch2/spring-petclinic.git'

    }

     stage('build'){

        bat 'mvn clean install'
    }

     stage('Test'){
      bat 'mvn test'
        
    }
     stage('Artifacts'){
     archiveArtifacts artifacts: 'target/*.jar', followSymlinks: false
        
    }
     stage('generated test reports'){
    junit 'target/surefire-reports/*.xml'
        
    }
}



![image](https://github.com/user-attachments/assets/90db8ef7-ded5-473a-bb1c-78fcd7c68f2f)


github sourcecode jenkinsfile 

![image](https://github.com/user-attachments/assets/44f93ca7-1d95-4efb-afad-cc262de61dbe)


Difference between Declarative and Scripted pipelines::
======================================================

The difference between Declarative and Scripted pipelines in Jenkins primarily lies in syntax, structure, and ease of use. Both are used to define CI/CD workflows, but they cater to different user needs and experience levels.


Declarative Pipeline::
=====================


1.Simpler, more structured syntax

2.Enforces a predefined, opinionated structure (pipeline, stages, steps)

3.Designed for readability and ease of use

4.Introduced later to make pipelines easier for users unfamiliar with Groovy


Scripted Pipeline::
=======================


1.More flexible, written in full Groovy

2.Gives access to full programmatic control (e.g., loops, conditionals, custom functions)

3.More complex and powerful, suited for advanced users





20/08/2025::
=============


Tomcat Web Server: Introduction
==============================

Apache Tomcat is an open-source web server and servlet container developed by the Apache Software Foundation. It is primarily used to serve Java applications and is one of the most popular servlet containers in the world.

Tomcat is an essential tool for anyone working with Java web applications. It provides a simple, reliable platform for deploying and managing Java Servlets and JSPs and is widely used in both development and production environments. Its ease of use, combined with powerful features and flexibility, makes it an ideal choice for many developers working on Java-based web applications.

Apache Tomcat is an open-source web server and servlet container that is primarily used to serve Java-based web applications. It implements several Java EE (Enterprise Edition) specifications, such as Java Servlet, JavaServer Pages (JSP), and WebSocket, among others. Tomcat is often used to run Java applications on the web because it's lightweight, easy to configure, and widely supported.

Here are some key points about Tomcat:

1. **Servlet Container**: Tomcat is a servlet container, meaning it manages the lifecycle of Java Servlets, which are small Java programs that run on a web server.
  
2. **JSP Support**: Tomcat also supports JavaServer Pages (JSP), a technology that allows for embedding Java code within HTML pages.

3. **Configuration**: It’s highly configurable through XML files, like `server.xml` for server settings, `web.xml` for application settings, and others.

4. **Lightweight**: Unlike full-fledged application servers like WildFly (formerly JBoss) or GlassFish, Tomcat is primarily a servlet and JSP container, which makes it lighter and easier to deploy for simpler Java web applications.

5. **Performance**: It’s known for good performance in handling static content, making it a popular choice for Java web developers.


Tomcat Download link::
--------------------

https://tomcat.apache.org/download-90.cgi


64-bit Windows zip

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76c04708-54fb-4cce-b5f9-1ab44dbb3f40" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45687889-b55c-433c-aa47-7be496451ec5" />



after downloaded the tomcat ,we need extrack the all the files

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/585a1ff6-5625-4793-b365-a82797749ade" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6e69bc25-36f7-4e96-b651-c7a389ca8b64" />


go to bin folder

C:\Users\HP\Downloads\apache-tomcat-9.0.105-windows-x64\apache-tomcat-9.0.105\bin

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4c4ff9e8-0c37-45cf-ae84-1ee282a9d6d9" />


navigate to CMD--command prompt


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f89d42cd-58c8-4b2a-9576-6329da35f272" />



run the command

>startup.bat

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6e8edc41-e322-4879-9e0c-d24d65a2289f" />



we can find tomcat server started

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a96b19b2-41a5-44c1-b1fc-6d71d1144920" />


we can navigate to browser

http://localhost:8080/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/14efdf7e-4a7d-4c93-8a0c-3b59f5015354" />



![image](https://github.com/user-attachments/assets/27e7023b-7544-41eb-9ed3-f04d2680d318)


Integrate Tomcat Jenkins::
==============================



<img width="1781" height="730" alt="image" src="https://github.com/user-attachments/assets/e73356b2-6037-4556-a8b1-28459191147b" />



Integrating Tomcat with Jenkins is a common use case for automating the deployment of Java-based web applications. Jenkins can be set up to deploy a web application to a Tomcat server whenever a new build is triggered.

Prerequisites:

Apache Tomcat should be installed and running on your server.
Jenkins should be installed and running.

Steps to integrate Jenkins with Tomcat:

1. Install the "Deploy to Container" Plugin in Jenkins:
The easiest way to deploy to Tomcat from Jenkins is by using the Deploy to Container plugin. This plugin allows Jenkins to deploy WAR files to a Tomcat server.

Go to your Jenkins dashboard.
Click on Manage Jenkins > Manage Plugins.
In the Available tab, search for Deploy to Container Plugin and install it.
Once installed, restart Jenkins to apply the plugin.

2. Configure Tomcat Server in Jenkins:
Now you need to tell Jenkins where your Tomcat server is running.

In Jenkins, go to Manage Jenkins > Configure System.
Scroll down to the Deploy to container section.
Click Add Tomcat Server.

Provide the necessary information:
Name: Give the Tomcat server a name (Tomcat9).
URL: The URL of your Tomcat server (e.g., http://localhost:8080).
Username: The username for Tomcat's manager app (usually admin).
Password: The password for that username (set in Tomcat's tomcat-users.xml).
Save the configuration.

3. Configure Tomcat’s tomcat-users.xml:
Make sure Tomcat is set up to allow Jenkins to deploy the application by editing the tomcat-users.xml file.

https://stackoverflow.com/questions/7763560/401-unauthorized-error-while-logging-in-manager-app-of-tomcat

tomcat-users.xml file::
=========================



![image](https://github.com/user-attachments/assets/61a0b6ae-1e6c-47d0-8852-b226d65f38a4)





  <role rolename="manager-gui"/>
  <role rolename="manager-script"/>
  <role rolename="manager-jmx"/>
  <role rolename="manager-status"/>
  <role rolename="admin-gui"/>
  <role rolename="admin-script"/>
  <user username="admin" password="admin" roles="manager-gui, manager-script, manager-jmx, manager-status, admin-gui, admin-script"/>




Restart Tomcat to apply the changes.

4. Create a Jenkins Job to Build and Deploy the Application:
Next, you need to create a Jenkins job that will build your web application (e.g., a WAR file) and deploy it to Tomcat.

From the Jenkins dashboard, click New Item.

Select Freestyle Project, give it a name, and click OK.

>TomcatServer Integrate With Jenkins

In the job configuration, go to the Build section and configure your build step, such as building a Maven project For Maven, you can use:

> mvn clean install

In the Post-build Actions section, add Deploy war/ear to a container.

In the WAR/EAR files field, provide the path to your WAR file (e.g., target/*.war).
In the Container field, choose the Tomcat server you configured earlier.
Set the Context Path (e.g., TomcatIntegartedWithJenkins), which is the URL path where the application will be accessible on Tomcat.
If you want Jenkins to deploy automatically after every successful build, check the option Deploy after every successful build.

please use below project to configured Tomcat integration

https://github.com/srinfotechbatch3/onlinebookstore.git

![image](https://github.com/user-attachments/assets/0692c308-09f1-4dec-9db7-b5c280e1b93c)


build steps

![image](https://github.com/user-attachments/assets/bf5bc2fc-7b95-48d4-9a35-cf074d6a2b33)

Post-build Actions

please select Deploy war/ear to a container in drop down


![image](https://github.com/user-attachments/assets/76756b66-a6a1-4178-911c-47c17e345695)

WAR/EAR files::: target/*.war

Context path:::TomcatIntegartedWithJenkins

containers::Tomcat 9.x Remote

please add tomcat credentials username and password

![image](https://github.com/user-attachments/assets/5641604b-6c0f-43c1-8249-0f96c0db8560)

Tomcat URL ::http://localhost:8080/

![image](https://github.com/user-attachments/assets/f3b90910-86d6-4c79-a015-843c05ba68d4)


![image](https://github.com/user-attachments/assets/68a490c3-37e1-427f-bade-e84ad096c991)


Save the job.

5. Trigger the Build and Deployment:
Go to the Jenkins job you just created and click Build Now to trigger a build.
After the build completes, Jenkins should deploy the WAR file to your Tomcat server.

![image](https://github.com/user-attachments/assets/e6ba9811-d613-47e7-bb7b-497ca0d2799c)


build success

[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  06:16 min
[INFO] Finished at: 2025-05-26T11:12:07+05:30
[INFO] ------------------------------------------------------------------------
[DeployPublisher][INFO] Attempting to deploy 1 war file(s)
[DeployPublisher][INFO] Deploying C:\Users\HP\.jenkins\workspace\TomcatServer Integrate With Jenkins\target\petclinic.war to container Tomcat 9.x Remote with context TomcatIntegartedWithJenkins
  Redeploying [C:\Users\HP\.jenkins\workspace\TomcatServer Integrate With Jenkins\target\petclinic.war]
  Undeploying [C:\Users\HP\.jenkins\workspace\TomcatServer Integrate With Jenkins\target\petclinic.war]
  Deploying [C:\Users\HP\.jenkins\workspace\TomcatServer Integrate With Jenkins\target\petclinic.war]
Finished: SUCCESS

![image](https://github.com/user-attachments/assets/61019ca1-6464-413d-9e26-34a0af06646c)

Once Build & Deployemnt completed go to Tomcat Server

http://localhost:8080/

Click Manager App

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5e915534-e599-4e32-8966-1d6e5658d4d4" />


You should found //SRINFOTECHONLINEBOOKSTORE

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/582dafb7-6ca9-4aff-a87a-4fbab04fd665" />


click //SRINFOTECHONLINEBOOKSTORE


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40bb4495-7931-4801-95f1-736b9c46ee47" />





Polling SCM (Source Code Management) and webhooks are two common methods used for integrating continuous integration (CI) systems or automating tasks based on changes in repositories.

1. Polling SCM
Polling SCM is a method where a system (like Jenkins, GitLab CI, etc.) periodically checks the source code repository for changes. If it detects changes, it triggers the build process or some other automated task.

How it works:

A job is set up to check the SCM (like GitHub, GitLab, Bitbucket, etc.) at regular intervals (e.g., every minute or hour).

The CI server pulls the repository to see if there are any new commits since the last poll.

If changes are detected, it triggers the CI/CD pipeline to build, test, or deploy the application.

2. Webhooks
Webhooks provide a more efficient method for triggering actions based on changes in the repository. Rather than the CI system polling for changes, the source control platform sends an HTTP POST request (webhook) to the CI system when an event (like a commit or pull request) occurs.

![image](https://github.com/user-attachments/assets/59e3f392-4da9-4fe3-8238-d2bd2fee5fc3)






21/08/2025::
=============


<img width="1781" height="730" alt="image" src="https://github.com/user-attachments/assets/d538193d-f2a7-4423-aa35-99da6428b193" />



Deploy Onlinebookstore/spring-petclinic applications to target server (Tomcat)::
=====================================================================================================================

please create one new pipeline job

Provide the Description

![image](https://github.com/user-attachments/assets/458b8076-ebce-4ac0-932e-64ee5a6e460b)

Enabled POLL SCM

![image](https://github.com/user-attachments/assets/5b5ae6d9-987a-4c54-9450-c3a89497be29)

In Pipeline Section write groovy script using Declarative style 


![image](https://github.com/user-attachments/assets/5d624b7b-9224-4d20-863f-0f3e4671916e)


Generate Deploy pipeline script::
====================================




Script::
=======

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main' url: 'https://github.com/parasa7358/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      sh 'mvn clean install'

    }
}

stage('Package'){

    steps{

      sh 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      sh 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      sh 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}


Run the job


![image](https://github.com/user-attachments/assets/f240a720-41dd-4bc0-955d-a247b1cf8918)

![image](https://github.com/user-attachments/assets/369955cf-0f1c-4ae1-bae3-3870edc0e282)

Integrate Jenkins with Tomcat using Declarative Approach::
=========================================================



To integrate Jenkins with Tomcat using the Declarative Pipeline approach, you'll be using Jenkins Pipeline syntax to automate the deployment process to a Tomcat server. This process typically involves building the application, packaging it, and then deploying it to Tomcat.

1. Jenkinsfile Configuration (Declarative Pipeline)

In your Jenkins project, you'll create a Jenkinsfile, which contains the Declarative Pipeline syntax. This file defines the steps involved in the CI/CD pipeline.

Please execute below script in jenkins pipeline job using Declarative style


Project URL::
====================

https://github.com/parasa7358/Petclinic.git

Declarative pipeline Script::
================================


pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'feature/2025.03.12', url: 'https://github.com/parasa7358/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      sh 'mvn clean install'

    }
}

stage('Package'){

    steps{

      sh 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      sh 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      sh 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}


Onlinebookstore::
==================

Project URL::
================

https://github.com/srinfotech7358/onlinebookstore.git

Pipeline Script::
===================



 pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master', url: 'https://github.com/srinfotech7358/onlinebookstore.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
         stage('Generate Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }

          stage('Deploy to Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'Tomcat', path: '', url: 'http://localhost:8080')], contextPath: 'SR INFOTECH SOLUTIONS PVT LIMITED', war: 'target/*.war'
            }
        }
    }
}


DevOps Web Project::
======================

Project URL::
================

https://github.com/srinfotechbatch3/devOpsWeb.git


Pipeline Script::
===================



 pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master', url: 'https://github.com/srinfotechbatch3/devOpsWeb.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
         stage('Generate Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }

          stage('Deploy to Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'Tomcat', path: '', url: 'http://localhost:8080')], contextPath: 'DevOpsWeb', war: 'target/*.war'
            }
        }
    }
}


ABove All 3 Projects are Deployed to Target Tomcat server Successfull using both Declarative & Scripted Approaches


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/00dd6bdc-bc26-4558-98e7-7fec40699bd0" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0f8c217f-1dea-4a2b-8265-2898525455cd" />





<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3a54c903-0f2c-4d84-b20b-41b56c85cb39" />




22/08/2025::
==============

Project URL's::
===================

https://github.com/srinfotech7358/Petclinic.git

https://github.com/srinfotechbatch3/onlinebookstore.git

https://github.com/srinfotechbatch3/devOpsWeb.git



SonarQube::
===============

Sonarqube installed link::

https://gist.github.com/dmancloud/0abf6ad0cb16e1bce2e907f457c8fce9

default U/P ---admin/admin


<img width="1783" height="747" alt="image" src="https://github.com/user-attachments/assets/14babfa3-f726-4abc-9d1c-6564165d8b4c" />



Introduction to SonarQube::
================================

SonarQube is an open-source platform developed by SonarSource that is used for continuous inspection of code quality. It helps developers and development teams identify bugs, code smells, vulnerabilities, and duplication in their codebases across multiple programming languages.

Key Features of SonarQube
Static Code Analysis
SonarQube analyzes source code without executing it, detecting issues like:

Bugs

Vulnerabilities

Code smells (bad design or coding practices)

Duplications

Technical debt


Sonarqube Integrate With Jenkins::
==================================

<img width="1852" height="758" alt="image" src="https://github.com/user-attachments/assets/cfe5963b-e3af-42e4-bdf4-a5825c65f72c" />

Sonarqube installed link::

https://gist.github.com/dmancloud/0abf6ad0cb16e1bce2e907f457c8fce9

default U/P ---admin/admin

default port number:: 9000

Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000

To integrate SonarQube with Jenkins, you need to ensure that Jenkins can communicate with your SonarQube server to perform static code analysis during your CI/CD pipeline. This will allow you to analyze your code quality and get reports from SonarQube as part of your build process.

Here's how you can integrate SonarQube with Jenkins:please follow below steps

1. Install the SonarQube Plugin in Jenkins
Before you start, ensure that you have the SonarQube Scanner Plugin installed in Jenkins:

Go to Jenkins Dashboard.
Click on Manage Jenkins → Plugins.
Go to the Available tab, and search for SonarQube Scanner.
Install it and restart Jenkins.

2. Configure SonarQube in Jenkins
Next, you need to configure SonarQube on Jenkins so it can communicate with your SonarQube server.



11/07/2025::
=============

Steps:
=====
Go to Jenkins Dashboard.
Click on Manage Jenkins → Configure System.
Scroll down to the SonarQube servers section and click Add SonarQube.

Fill in the following details:
=======================
Name::: Give your SonarQube instance a name (SonarQubeServer).
Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000
Server Authentication Token: You can generate a token in SonarQube by navigating to My Account → Security → Generate Tokens. Paste this token into Jenkins.
Click Save.

3. Configure the SonarQube Scanner in JenkinsSteps:
 ===============================================
In the Configure System page, scroll to the SonarQube Scanner section.
Click Add SonarQube Scanner and select SonarQube Scanner for Jenkins.

If you want to use a custom installation, specify the path to the SonarQube Scanner binary.
Click Save.

 Configure SonarQube Project::
 ========================
Go to your SonarQube server (e.g., http://localhost:9000).
Create a project or use an existing one.
Obtain the Project Key from the SonarQube project and update the pipeline script as shown in the sonar.projectKey parameter.

Go to Projects and click Local project

![image](https://github.com/user-attachments/assets/0b177021-0fc2-4ba4-a987-fee4a3420717)

Click Next

![image](https://github.com/user-attachments/assets/2cccbec2-463b-47ab-9379-f02244272f3a)

Selected Use the global setting

![image](https://github.com/user-attachments/assets/702766f0-01a9-4919-bbda-acb3a8996dcd)

Click Create Project

![image](https://github.com/user-attachments/assets/a614a64f-7171-43c3-b19e-787e13ee0c16)

Now Spring-petclinic Project created in Sonarqube

![image](https://github.com/user-attachments/assets/0f79347c-8bde-4fa3-8eaa-3ca91a27422d)

Click Locally

![image](https://github.com/user-attachments/assets/d6e4fa35-299c-4768-b291-c669d9b52995)

![image](https://github.com/user-attachments/assets/ba49dbeb-8f7f-4fb4-ab7d-8c4d3644a133)

Click Generate for Token

Analyze "spring-petclinic12": sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab


![image](https://github.com/user-attachments/assets/7e46dded-06da-467a-8838-62e9f0337a7a)

Click Continue

![image](https://github.com/user-attachments/assets/590c723c-0df3-48df-bf7d-77575e63614a)

![image](https://github.com/user-attachments/assets/ace61156-d25b-4d00-b248-d5bd0b1de835)

Selected Maven and copy below script from sonarqube and it will help to integrate Sonarqube with jenkins pipeline

![image](https://github.com/user-attachments/assets/1da2fbb2-5118-45e5-85ec-c7767a44529b)


mvn clean verify sonar:sonar \
  -Dsonar.projectKey=spring-petclinic12 \
  -Dsonar.projectName='spring-petclinic12' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab



 IntegrateSonarqubeWithJenkins::
  ==================================

  Go To jenkins and create new job IntegrateSonarqubeWithJenkins

  ![image](https://github.com/user-attachments/assets/dc7d3f1e-5852-4288-bf00-5537b6a4935c)

Please use below script to run the pipeline job

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main', url: 'https://github.com/parasa7358/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      bat 'mvn clean install'

    }
}

stage('Package'){

    steps{

      bat 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      bat 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      bat 'mvn test'

    }
}

stage('Sonarqube Analysis'){

    steps{

      bat 'mvn clean package'

    bat '''mvn sonar:sonar \
  -Dsonar.projectKey=spring-petclinic \
  -Dsonar.projectName='spring-petclinic' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_8d74d659dbf3d3bf2924a0d24104f5ddba914fac'''

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'Ifocus Solutions Pvt Ltd', war: '**/*.war'

    }
}

}
}



 

1. please start Jenkins on your machine & make sure Jenkins server is UP & Running state
2. please start Tomcat on your machine & make sure Tomcat server is UP & Running state
3. please start Sonarqube on your machine & make sure Sonarqube server is UP & Running state

once above steps done then we can execute below script

Working Scripts CI/CD::
===========================

pipeline{

    tools{

        maven 'Maven'
    }
agent any

stages{

    stage('Clone'){

        steps{

            git branch: 'main', url: 'https://github.com/srinfotech7358/Petclinic.git'
        }
    }

     stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }

         stage('Test Cases') {
            steps {
               bat 'mvn test'
            }
        }

         stage('Archive the Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
 stage('Sonarqube Analysis') {
            steps {
               
               bat 'mvn package'
              bat '''mvn sonar:sonar \
             -Dsonar.projectKey=spring-petclinic \
             -Dsonar.projectName='spring-petclinic' \
            -Dsonar.host.url=http://localhost:9000 \
            -Dsonar.token=sqp_96cf5222ab632b69c14baa5590210a7125185d5a'''
            }
        }


 stage('Deploy Application into Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'NewTomcat', path: '', url: 'http://localhost:8080/')], contextPath: 'Test', war: 'target/*.war'
            }
        }

}

}


Once sonarqube scanner done, please verify the sonarqube dashboard for reports & results

![image](https://github.com/user-attachments/assets/acc53857-78ca-4e07-becc-6aba969c61b4)

Go to Administration

![image](https://github.com/user-attachments/assets/e94cc57e-d8fe-4d4a-8110-6a0afa2164af)


Click Projects & Select Background Tasks


![image](https://github.com/user-attachments/assets/53d35e0d-abe2-462e-a608-4736b3cd06c4)

You can able to see all scanned projects status

![image](https://github.com/user-attachments/assets/7075a240-88a1-4c2b-b68d-c963e8f666aa)

Click on any Project, see the PASSED the quality gates

![image](https://github.com/user-attachments/assets/0d329366-3a10-4131-b5a4-e2fb7063647d)

Click on Overall Code option

![image](https://github.com/user-attachments/assets/8435ef6f-8152-42fc-85c4-ab3940473379)

![image](https://github.com/user-attachments/assets/3b454b9a-6c88-435f-b543-962f710b3f86)

see the results

![image](https://github.com/user-attachments/assets/adb4c7f2-70d5-4a85-903a-2d64e0ef5cbb)

here Code coverage is 

Coverage
82.7%

![image](https://github.com/user-attachments/assets/f5954fe3-2c85-4283-a736-0bc58308687d)

NOTE:: Coverage is greater than or equal to 80.0%, this should be maintained minimum % every project

NOTE:::Duplicated Lines (%) is less than or equal to 3.0%



Create My own Quality Gates::
=======================

Go to Dashboard click on Quality Gates

![image](https://github.com/user-attachments/assets/b7e1b1c1-e25e-4bf4-acb2-7d3f386df80c)

at left side we can see create & just click on it

![image](https://github.com/user-attachments/assets/b203f151-0ab2-4de3-84f8-a262f462a9c5)


Provide the Name & Click Create


![image](https://github.com/user-attachments/assets/a008a297-54ef-49b3-b5bf-a7df05d19c96)


Your own quality gates are created

![image](https://github.com/user-attachments/assets/f46d3c2a-dfa7-408b-a30d-5d1688de1891)

this is your own quality gates

![image](https://github.com/user-attachments/assets/dab980c2-3767-4d6b-867a-03b423593323)

nditions on New Code
Metric
Operator
Value
Issues
is greater than
0
Security Hotspots Reviewed
is less than
100%
Coverage
is less than
80.0%


Duplicated Lines (%)
is greater than


select your project

![image](https://github.com/user-attachments/assets/3f0aed8a-ebd7-4a27-8e13-4b7bbac978e1)

apply the Grant permissions to a user or a group

![image](https://github.com/user-attachments/assets/a098832f-e4eb-476d-9cbf-e9bbd0a356c5)


Apply all the permissions & click Add

![image](https://github.com/user-attachments/assets/77ce722c-f751-4a9f-844f-edeb677ccb01)

![image](https://github.com/user-attachments/assets/48485193-39d4-4e32-a7cb-c943d0d00ed6)

![image](https://github.com/user-attachments/assets/0b988e9d-df3a-4118-98b8-f4b0cd6e3262)


Create my own Quality Profile::
================================

go to Quality Profiles


![image](https://github.com/user-attachments/assets/9f3c55e8-566a-4f48-8dff-1e473ab0aee0)

select Language

![image](https://github.com/user-attachments/assets/44cc17f2-03f4-4ea0-83ff-8d97a36e1f2b)

total java Rules 527

![image](https://github.com/user-attachments/assets/40ff10ed-e1cf-4ccf-bd80-f9ff509a6ae4)


at right saide top click create

![image](https://github.com/user-attachments/assets/e786de8b-915f-466c-904f-7453eab9efab)

provide the Language & Name and click Create

![image](https://github.com/user-attachments/assets/1a2aaba8-1855-4f13-859e-3cc0b5f0367f)


your own profile

![image](https://github.com/user-attachments/assets/12c55b42-aa02-46c9-a31d-60b46d682e7e)

click Active More rules

![image](https://github.com/user-attachments/assets/d9f3dde5-92cd-466f-9d68-b4bbaae336d5)

Bulk Change

![image](https://github.com/user-attachments/assets/8e927220-c993-4b8f-8ca7-6d9884aa41c4)

Activate In Spring-pipeline project

![image](https://github.com/user-attachments/assets/55e0b2e6-7c53-4b98-b2ce-87f75f935246)

Sure Apply

![image](https://github.com/user-attachments/assets/637731b5-bcbe-4798-b87b-ca808f39f2c1)

Succcessfully Applied my own quality profile rules

Activate In Quality Profile (683 rules)

![image](https://github.com/user-attachments/assets/b530b33a-c75f-470e-9118-e0d49bcbfb96)

Now we are successfully onboarded spring-petclininc project to Sonarqube server

![image](https://github.com/user-attachments/assets/1d8bbf77-c70d-479a-8057-ff62984f23f7)

![image](https://github.com/user-attachments/assets/0c1ea5e5-fd03-46b3-aa51-0f283095ffa8)

![image](https://github.com/user-attachments/assets/45b7263c-0e82-45ff-b06f-915a2af9b464)


Running the Pipeline Once the pipeline is configured, Jenkins will execute the SonarQube analysis during the build process. After the build completes, you can view the analysis results in your SonarQube dashboard.



Code coverage Code smells Bugs Vulnerabilities Duplications These reports will be available in the SonarQube dashboard for your project.



26/08/2025::
================


AWS (Amazon Web Services)::
========================

Create AWS Free tier Account::
====================================
Please go throw the recorded video session and follow the steps to create the free tier AWS account.Let me know if anyone facing any issues.

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.


Jfrog Artifactory Overview::
========================

JFrog Artifactory is a universal artifact repository manager that serves as a central hub for storing, managing, and distributing software artifacts, binaries, packages, and other assets throughout the software development lifecycle, improving automation, and ensuring release integrity.


<img width="1745" height="762" alt="image" src="https://github.com/user-attachments/assets/0b25b0ad-4890-4486-987b-6d5e3ec7d6b4" />




Artifact Repository Management:

Allows for storing binaries and artifacts (e.g., libraries, packages, Docker images) in a centralized location.
Supports all major package types (e.g., Maven, Gradle, npm, NuGet, RubyGems, etc.).
Version Control:

Helps in managing versions of your artifacts and ensures the correct version is used during builds and deployments.
Integration with CI/CD:

Integrates seamlessly with CI/CD tools like Jenkins, Bamboo, GitLab CI, and others.
Enables automated publishing of artifacts as part of your continuous integration pipeline.
Access Control & Security:

Provides fine-grained access control and permissions for users and groups.
Supports user authentication, security, and audit trails to ensure compliance and secure artifact management.
Replication:

Allows you to replicate artifacts across multiple Artifactory instances, ensuring high availability and disaster recovery capabilities.
Remote Repositories:

Artifactory can proxy remote repositories, allowing you to cache and fetch external dependencies without re-downloading them each time.
Promotion & Release Management:

You can "promote" artifacts from one repository to another (e.g., from a development repository to a production repository), allowing for better control over releases.
Multi-Platform Support:

Artifactory supports multiple programming languages and platforms, making it a universal solution for managing software dependencies and releases.


Integrate Jfrog with Jenkins::
=================================


First Step:: 
https://jfrog.com/download-jfrog-platform/  ---download url

<img width="1745" height="762" alt="image" src="https://github.com/user-attachments/assets/91fd2e3d-5e50-4b90-a7eb-8a6266126a0e" />


previous versions link

https://jfrog.com/download-legacy/?product=artifactory&version=7.104.12

All zip version and search 6.12.1 OSS version

https://releases.jfrog.io/artifactory/bintray-artifactory/

jdk compatibility version with jfrog is::
=============================================
 
JDK 12.1.0
 
https://www.oracle.com/in/java/technologies/javase/jdk12-archive-downloads.html
 
artifactory-oss-6.12.1
 
All zip version and search 6.12.1 OSS version
 
https://releases.jfrog.io/artifactory/bintray-artifactory/



28/08/2025::
==============


jdk compatibility version with jfrog is::
=============================================
 
JDK 12.1.0
 
https://www.oracle.com/in/java/technologies/javase/jdk12-archive-downloads.html
 
artifactory-oss-6.12.1
 
All zip version and search 6.12.1 OSS version
 
https://releases.jfrog.io/artifactory/bintray-artifactory/


Jfrog Script::
===============

stage ('Artifactory Server'){
            steps {
               rtServer (
                 id: "Artifactory",
                 url: 'http://localhost:8081/artifactory',
                 username: 'admin',
                  password: 'password',
                  bypassProxy: true,
                   timeout: 300
                        )
            }
        }
        stage('Upload'){
            steps{
                rtUpload (
                 serverId:"Artifactory" ,
                  spec: '''{
                   "files": [
                      {
                      "pattern": "*.war",
                      "target": "srinfotech-batch3"
                      }
                            ]
                           }''',
                        )
            }
        }
        stage ('Publish build info') {
            steps {
                rtPublishBuildInfo (
                    serverId: "Artifactory"
                )
            }
        }


installed plugin for artifactory (Jfrog)::
 =====================================


![image](https://github.com/user-attachments/assets/542a6be0-9059-4935-9658-81ce27634337)

After installed Artifactory plugin 

Go to Manage Jenkins--> System configuration find JFROG

 ![image](https://github.com/user-attachments/assets/5ddbd986-aaee-478b-8a03-e117f53a7b3a)

Click JFrog Platform Instances

![image](https://github.com/user-attachments/assets/c176ad14-5982-4ea3-b960-468d00f851c7)

For user name and password


Default Jfrog U/P----admin/password

![image](https://github.com/user-attachments/assets/83204f3d-bf7b-4bd5-b616-61eaf03ae216)


![image](https://github.com/user-attachments/assets/2af4f08d-5778-4517-8b90-43037eb6ecce)


![image](https://github.com/user-attachments/assets/c104f1c1-6cd0-4911-8eef-b9243a2dd41f)


I need to setup target in Jfrog

srinfotech-batch3

click Local repository

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53f74cd8-b34c-4063-a434-52f1f648836c" />



Select maven

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/46cdec7f-4326-4b0f-86cb-45370397bec2" />


Repository key  :::: srinfotech-batch3

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3aa08db9-d518-49d5-bb31-2d4fda2650a3" />


Click save and finish

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/67d49f71-cbaa-40ff-93aa-90e5454a9f23" />



Go to artifacts and check repository is created with name -srinfotech-batch3

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9b2e35b7-ec96-48a2-bbbf-a182ba295dad" />



CI/CD all tools ans stages script:: create new job in jenkins and execute below script 
=====================================


pipeline{
agent any
 
tools{
 
    maven 'Maven'
}
 
stages{
    stage('Clone The Project'){
        steps{
            git branch: 'main', url: 'https://github.com/srinfotechbatch2/Petclinic.git'
        }
    }
    stage('Build'){
        steps{
             bat 'mvn clean install'
        }
    }
     stage('Test'){
        steps{
             bat 'mvn test'
        }
    }
     stage('Generated the test reports'){
        steps{
             junit 'target/surefire-reports/*.xml'
        }
    }
     stage('published the Artifacts'){
        steps{
            archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
 
    stage('SonarQube Analysis'){
        steps{
        bat 'mvn package'
      bat '''mvn sonar:sonar \
  -Dsonar.projectKey=spring-petclinic \
  -Dsonar.projectName='spring-petclinic' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_b4f05b06814df65b8d3f1a46'''
        }
    }
 
stage ('Artifactory Server'){

            steps {
            
               rtServer (
               
                 id: "Artifactory",
                 
                 url: 'http://localhost:8081/artifactory',
                 
                 username: 'admin',
                 
                  password: 'password',
                  
                  bypassProxy: true,
                  
                   timeout: 300
                   
                        )
            }
            
        }
        stage('Upload'){
        
            steps{
            
                rtUpload (
                
                 serverId:"Artifactory" ,
                 
                  spec: '''{
                  
                   "files": [
                   
                      {
                      
                      "pattern": "*.war",
                      
                      "target": "srinfotech-batch3"
                      
                      }
                      
                            ]
                            
                           }''',
                           
                        )
            }
            
        }
        stage ('Publish build info') {
        
            steps {
            
                rtPublishBuildInfo (
                
                    serverId: "Artifactory"
                )
                
            }
            
        }
 
 
    
    stage('Deploy to Tomcat Server'){
    
        steps{
        
            deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'tomcatcredential', path: '', url: 'http://localhost:8080')], contextPath: 'SRInfotechSpringpetclinicJfrog', war: 'target/*.war'
        }

        
    }
    
}

}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ed5c92a-cc09-4cd4-80da-1e4eb7ec0596" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/408c9aa6-882f-46cc-942e-1fa4f0d45e86" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d1ad9cc6-6657-48c7-b657-7e814b79ba02" />





29/08/2025::
===============


AWS (Amazon Web Services)::
====================

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.

AWS ---Amazon web services

compute services::
Amazon EC2 (Elastic Compute Cloud): Provides scalable virtual servers to run applications.
AWS Lambda: Lets you run code without provisioning or managing servers. It automatically scales based on usage.

Storage services::
Amazon S3 (Simple Storage Service): Object storage for storing and retrieving large amounts of data.
Amazon EBS (Elastic Block Store): Persistent block-level storage for EC2 instances.

Database::
Amazon RDS (Relational Database Service): Managed relational database service supporting multiple database engines (e.g., MySQL, PostgreSQL, MariaDB, etc.).
Amazon DynamoDB: A managed NoSQL database service.
Amazon Aurora: A high-performance relational database engine compatible with MySQL and PostgreSQL.

Network services::
Amazon VPC (Virtual Private Cloud): Lets you create isolated networks within AWS for secure connections.

Security ::

AWS IAM (Identity and Access Management): Controls user access and permissions for AWS resources.
AWS KMS (Key Management Service): Managed service for creating and controlling encryption keys.
Security groups ---inbound, outbould roles


Containers & kuberneties::
ECS  ---elastic containers servcies
EKS  ----estastic kuberneties services
AKS  ---Azure kuberneties services

Cloud watch --Metrics Monitoring

CloudWatch Metrics allows you to track the performance and utilization of AWS resources such as EC2 instances, RDS databases, Lambda functions, S3 buckets, and much more.
These metrics include CPU utilization, disk activity, network traffic, and others. You can create custom metrics for your applications or services as well.

cloud trail ---Security Monitoring:

Use CloudTrail logs to detect unauthorized access or activity in your AWS environment. You can track changes in security settings, unauthorized API calls, or unexpected configuration changes.

Developer Tools::
AWS CodeCommit: Source control service for managing your code repositories.
AWS CodeDeploy: Automates code deployments to EC2 instances and Lambda.
AWS CodePipeline: Continuous integration and continuous delivery (CI/CD) service for automating the release pipeline.

AWS EC2 ::
===========
Amazon Elastic Compute Cloud (Amazon EC2) is one of the core services provided by Amazon Web Services (AWS)

Wide Variety of Instance Types:

EC2 instances are grouped into families based on the type of workload they are optimized for. Some common instance families include:
General Purpose: e.g., t3, m5 instances (balanced CPU, memory, and networking).
Compute Optimized: e.g., c5 instances (great for high-performance computing tasks).
Memory Optimized: e.g., r5, x1e instances (designed for high-memory workloads like databases).


Master & Node communication Via SSH keys::
============================================

<img width="1804" height="756" alt="image" src="https://github.com/user-attachments/assets/73a38d69-e625-4fcd-889f-c3959817f391" />



create EC2 Ubuntu Linux Machine in AWS::
==================================

Go to AWS and Search EC2

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d5b19c0-19de-4328-b0df-05d959f5bd38" />


Click EC2

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d3db337-a36a-403c-8d61-0924ef82fa41" />


Go to instances at left side bar

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42d33ae6-1b84-4934-bc5b-df0122473433" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7197ab92-5618-4872-9d3d-988d7d468d43" />



Click Launch Instances, EC2  ---> Instances  -----> Launch an instance

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2e7cb8fb-a19f-4329-832b-7e2a9df13b16" />


Select Ubuntu

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be45dcf1-7819-4f7c-bbeb-520eb9c6c7c4" />


Select Amazon Machine Image (AMI)


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/de98facb-13b6-497e-af1e-940a4c3c473a" />



select Instance type,t2 medium


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/74b8b230-3e56-45d6-b2bf-31161447265b" />



Create new key pair and provide key pair name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bbcf96b5-15de-4242-b582-e323c915c077" />


click create pair

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05a3b15d-577e-49cc-a256-df090e685fe3" />


click launch instance

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d13215e0-a952-46b4-9eb2-ed0d4636e29d" />


instance will be created

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d8335ca6-e57c-4b23-8a4d-cd6271d85f63" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ae686a03-6233-4a68-88ea-688b513a4eac" />





01/09/2025::
==============


Master & Node communication Via SSH keys::
================================

i have to create 2 EC2 ubuntu machines in AWS

1. Jenkinsmaster

2. Node




<img width="1478" height="720" alt="image" src="https://github.com/user-attachments/assets/c2d9271e-ef7e-4795-a337-3a4652b49527" />


we have already .pem file dowloaded in you local machin

right click from .pem and click Open git bash here option
Now Go to AWS Ubuntu machine which is already created in AWS insatnces and select master machine

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69c4bd3c-fb96-4e34-93ce-bb3ab176f5e4" />


Click Connect

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/608b56e0-275b-4854-a135-2f54886dd0ea" />


Click SSH Client

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5cf59bd9-ec79-446c-96eb-e36e05c17a2a" />


Copy URL

>ssh -i "Batch2.pem" ubuntu@ec2-18-237-178-192.us-west-2.compute.amazonaws.com

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e5cd3cef-ad51-4604-8e02-b74981dec51c" />


Now past that url in Gitbash

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/327cb240-6f1f-4b6a-8db5-718510aab388" />


switch to root user below command run

>Sudo -i

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/47049e39-538e-4a1e-8810-36c90abbed3b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/51bd5a55-81ce-4fff-84df-f8ad2e20fedb" />


update the all packages ,please run below command

>sudo apt-get update

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5486332-2033-4550-a134-c556657debfc" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3b76e193-7495-4fb8-9cce-37f2a6732f16" />


Install JDK & Maven:;
============

JDK link

https://bluevps.com/blog/how-to-install-java-on-ubuntu

MAven link

https://phoenixnap.com/kb/install-maven-on-ubuntu



>sudo apt-get install maven

>java -version

>mvn -v

Set java home environment 

>sudo vi /etc/environment

JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”

MAVEN_HOME=”/usr/share/maven”

Reload your system environment
>source /etc/environment

Veriy the variables was set correctly
>echo $JAVA_HOME

>echo $MAVEN_HOME

Insatll Jenkins on master machine::
========================================

https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-22-04

https://phoenixnap.com/kb/install-jenkins-ubuntu


In AWS any machines default passwordauthentication is disabled , 
we need to enabled in any linux machines::
=========================================


>sudo vi /etc/ssh/sshd_config

>sudo service sshd restart

In EC2 – by default password based authentication is disabled so we need to enabled::
==================================================

>sudo vi /etc/ssh/sshd_config

passwordauthentication :yes

![image](https://github.com/user-attachments/assets/99decb00-3ef0-4528-8e58-0d69bf14ce36)

In ubuntu machine default user is not sudo user,you should make user as a sudo user
>visudo


# Allow members of group sudo to execute any command

Jenkins ALL=(ALL:ALL) NOPASSWD:ALL

>su Jenkins

Switching to new user

![image](https://github.com/user-attachments/assets/86bc74b0-e31f-44aa-bcab-875ed9a3a016)

![image](https://github.com/user-attachments/assets/98b96a48-2ee3-466c-b917-26c1919b15f6)

Once installed Jenkins successfully

>we need to enabled the Inbounds and outbounds rules in AWS security groups

Inbounds rules

![image](https://github.com/user-attachments/assets/b7075d75-dd60-42d4-a282-7be861252685)

Copy public IP address and go to browser
Access Jenkins using Public IP address
http://35.86.160.156:8080/

bydefault Jenkins runs on port 8080

Jenkins home path/var/lib/Jenkins

How to change the port number in Jenkins::

https://stackoverflow.com/questions/28340877/how-to-change-port-number-for-jenkins-installation-in-ubuntu-12-04

>sudo nano /etc/default/jenkins


Now Go to Node Machine::
==============
Please insatll JDK & Maven in node machine and setup environemnt varibles

>sudo apt-get install maven

>java -version

>mvn -v

Set java & Maven home environment::
====================================

>sudo vi /etc/environment


1.press i from your keyboard

2.press the esc from your keyboard

3. shift+:

4. wq

5. press Enter



JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”

MAVEN_HOME=”/usr/share/maven”

Reload your system environment

>source /etc/environment

Veriy the variables was set correctly

>echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME
/usr/share/maven



>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node
2.user should provide the sudo permissions
>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled


NOTE::
========
1. user should provide the sudo permissions

2. passwordauthentication should be enabled

3. run any command from /root user only


Class Note::
===============

Jenkins master::

1.java & maven need install

2.setup environemnt variabels

3.install jenkins in master machine

4.provide the sudo permission to the jenkins user

5.passwordauthentication shobe enabled

6.ssh-keygen -t ed25519  -->generated the privte & public keys

NOTE:: if authorized_keys file is there or not, if not there you shoube be create the authrized_keys file

7.copy the public/private/ keys to node machine

NOTE1:: copy the public keys to authorized_keys file

NOde::

1.java & maven need install

2.setup environemnt variabels

3.need to create the user as node--->adduser node

4.provide the sudo permission to node user

5.passwordauthentication shobe enabled




04/09/2025::
==============


Master Node Configuration::

>got to manage Jenkins

>manage Nodes


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d84ee12-6b57-4dc0-ab1e-eac986474db7" />


>click new node


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e4fc0210-1d58-4e8d-abce-4587b78f51b5" />

Give Node name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bb37de5b-36c4-43ac-8f06-c2fe429ccc82" />


select Permanent Agent

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7bcfacca-9904-4d14-a5fc-6b32e8184253" />


click create


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/980d0602-42e5-4f0f-8254-53bc39f81068" />




Remote root directory

>home/node


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/465a5411-d053-4daa-91a9-04f00f3ded09" />


Launch methods via ssh

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26c1c7df-058e-4821-b817-1ef93642a831" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/abd7b2f1-c133-4873-b6df-5a5bfb4857b3" />


Host provide the node private ip addresss


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76d3229f-921e-4c26-b04e-bca84abbf6f6" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/215c2022-524d-40a4-b157-f539c19410f0" />


Add credentials ::

option-1::

this time please use credentials option SSH key with private key from node machine


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/04453cef-b083-4f10-928c-ba4dbb2547c3" />


select SSH key with private key

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be6f565c-3e3c-4c39-90c5-ba9a95451573" />


provide the ID & Deccription


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2fa28bd-70ee-4cca-800e-a7e6ae010bd2" />

User Name------> node machine user name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8201cb00-e148-43e1-ac2c-011f5ad2c3fd" />

select private key


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7663c7ac-53bc-432c-8c75-ebe36c20d204" />

give the private key of node machine


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6bf4b79e-c102-4863-8773-356cc80e6410" />


click Add


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/27ffaf4c-f2db-49fa-9917-a02cac410e0f" />


click save


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a97cc27-f023-4ffb-a33b-20c96bf2a9c7" />




Agent successfully connected


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8262c42d-3cc0-4152-935b-62849c13db8c" />

 

Execute Jenkins job using slave /node/agent/worker/helper 

Create one test slave job in Jenkins

>select Restrict where this project can be run


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/287a541a-e97c-4756-97ab-560efef29c0e" />


>select Label Expression


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ed5a566d-0b91-43e3-94e3-774cc2b14159" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/780c0899-4ea6-4407-a2db-4b6744f4da44" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f5004e8-5aeb-4c64-98db-f0985491a173" />


please create 2 job in jenkins master and setup 1 job in Node machine and 2nd job master machine, just trigger Build Now 

Please observe below screenshot 2 job running different machines 

Building on the built-in node in workspace /var/lib/jenkins/workspace/master

Building remotely on SRInfotechNode in workspace /home/node/workspace/sample

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2eadd4d0-eab0-4b06-a0ca-50a50f57ae6a" />


advantage of master & Node Integration


<img width="1292" height="737" alt="image" src="https://github.com/user-attachments/assets/8420c354-0336-483a-a6d2-e96cc7685173" />



<img width="1252" height="740" alt="image" src="https://github.com/user-attachments/assets/7a62f53f-846f-45bb-8f32-008d1819238c" />


<img width="1561" height="767" alt="image" src="https://github.com/user-attachments/assets/fcfc76ac-8e62-4c18-b894-959e513d721d" />

Session NOTE:::
===================

Master & Node Communicatiion Via SSH keys::
===========================================
>sudo -i
>sudo apt update
>java --version
>mvn -v

environment setup::

Maven home: /usr/share/maven

>sudo apt install maven

Java Home::  /usr/lib/jvm/java-17-openjdk-amd64

>sudo apt install openjdk-17-jdk

>sudo vi /etc/environment

1.press i from your keyboard
2.press the esc from your keyboard
3. shift+:
4. wq
5. press Enter

>echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME
/usr/share/maven

>ssh-keygen -t ed25519

>su <username>
>su jenkins

>visudo
		
# Allow members of group sudo to execute any command
		
jenkins ALL=(ALL:ALL) NOPASSWD:ALL

ctrl+X
yes
enter

in aws passwordauthenticatuion is disabled , you need to enabled the passwordauthentication

>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node
2.user should provide the sudo permissions
>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled

>sudo vi /etc/ssh/sshd_config
>cd ~

>ssh node@172.31.37.219


ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIOayYEJSyLHLOX25WbnoZgtL006XdmN6T5N0dlUnp7kI root@ip-172-31-44-252


--2 machines

1.master

a.java & mavne need install

b.setup environmemnt variables

c.install jenkins in master machine

d.provide the sudo permission to the jenkins user

e. passwordauthentication should be enabled

f. ssh-keygen -t ed25519 --> need to generate the keys in master

g. copy the public/private keys to Node machine

NOTE:: if authorized_keys file is there or not , if not there 

please be create both the machine

2.Node

a.java & mavne need install

b.setup environmemnt variables

c. need to create use as node-->adduser node

c.provide the sudo permission to the node user

visudo 

node ALL-(AAL:ALL) NOPASSWD:ALL

e. passwordauthentication should be enabled

if keys are copied correctly commenucation will be happend 



Ansible:: Configuration Mamagement Tool(CM)::
==============================================

Ansible is an open-source automation tool used for configuration management, application deployment, task automation, and multi-node orchestration. It helps system administrators and DevOps professionals automate IT processes to improve efficiency, reduce errors, and simplify complex workflows.


<img width="1690" height="744" alt="image" src="https://github.com/user-attachments/assets/b36c3691-3036-436f-a06f-811ba5b03ade" />


Key Features of Ansible:
================
Agentless: Ansible doesn't require any agents to be installed on the target machines. It uses SSH (or WinRM for Windows systems) to communicate with remote nodes.

Declarative Syntax: Ansible uses YAML (Yet Another Markup Language) to define the tasks, which makes it easy to read and write.

Idempotent: Ansible ensures that running the same playbook multiple times has the same effect, meaning it won’t reapply configurations if they’ve already been applied correctly.

Modular: Ansible has a large number of pre-built modules that can be used to manage various systems, applications, and services.

Playbooks: These are YAML files that describe the automation tasks you want to run. Playbooks are the heart of Ansible automation and define the "what" and "how" of your automation tasks.

Inventory Management: Ansible can manage an inventory of systems, which is used to organize and target different sets of machines.

Basic Components:
==================
Inventory: A list of hosts (machines) that Ansible will manage.

Playbook: A YAML file that defines the tasks and roles to be applied to the inventory.

Roles: A way to group related tasks and files together in a reusable manner.

Modules: Pre-built commands that Ansible can run on target systems to accomplish specific tasks (e.g., file management, system configuration, etc.).

3 linux ubuntu machines

AWS_Ubuntu 24

1)	AWS free tier

a)ACS   ----Ansible control server

b)Node1

c)Node2


all these 3 machine ping to each other





05/09/2025::
================


Ansible Control Server(ACS):: steps
============================

<img width="292" height="244" alt="image" src="https://github.com/user-attachments/assets/4121fe3b-97b2-43bd-ac04-afa213b14d36" />


Ansible Install LInk

https://www.cherryservers.com/blog/install-ansible-ubuntu-24-04


ACS::ansible control server
===========================

Please follow the below steps to setup ACS

1.install ansible

2. passwordauthentication enabled

3. create new user --->adduser ansible

4. user should provide the sudo permission

5. Generate the private & public keys --> ssh-keygen -t ed25519  

6.copy the public/private keys to Node machines

if keys are copied correctly commenucation will be happend 

NOTE1 setup::steps
==========

Please follow the below steps to setup ACS

1.install python

2. passwordauthentication enabled

3. create new user --->adduser node1

4. user should provide the sudo permission

NODE2 Setup::steps
=========================

Please follow the below steps to setup ACS

1.install python

2. passwordauthentication enabled

3. create new user --->adduser node2

4. user should provide the sudo permission

<img width="286" height="372" alt="image" src="https://github.com/user-attachments/assets/284d66db-b34b-4df0-bee4-3abc2ed651b8" />

we can search in google ansible playbook
https://docs.ansible.com/ansible/latest/user_guide/playbooks.html

https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html#basics

Python Install link::

https://docs.vultr.com/how-to-install-python-and-pip-on-ubuntu-24-04


Steps::
======
ubuntu@ip-172-31-28-207:~$ sudo -i
root@ip-172-31-28-207:~# su ansible
ansible@ip-172-31-28-207:/root$ cd ~
ansible@ip-172-31-28-207:~$ cd /etc/ansible/
ansible@ip-172-31-28-207:/etc/ansible$ ansible -m ping all
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12, but future installation of
another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
localhost | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ansiblenode2@172.31.30.200 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ansiblenode1@172.31.20.135 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
ansible@ip-172-31-28-207:/etc/ansible$




Ansible Playbooks Introduction::
==========================

Ansible playbooks are the heart of automation with Ansible. They are simple YAML (Yet Another Markup Language) files that define automation tasks in a structured, human-readable format. Playbooks allow you to automate configurations, deployments, and orchestration tasks in a clear and organized way.

1.what is playbook  

a.playbook is a text file

b.playbooks is set up of tasks

c.playbook is written in YAML or YML

d.each task is module

e.playbook is defined values key-values pairs

f.playbook is tell to the ansible , please execute the tasks

g.any configuration management tools maintained a state and each module have state


3 linux ubuntu machines::
==========================

AWS_Ubuntu 24
1)	AWS free tier 

a)ACS   ----Ansible control server

b)Node1

c)Node2



SSHKeys::
========= 

ssh-keys re generated in ACS--Ansible control Server

>ssh-keygen -t ed25519

above command is private & public keys are generated 

>copy public keys from ACS to Node1 & NOde2 inside the Authorized_keys files

NOTE::: Please verify the all the machines ,if Authorized_keys file is present OR not . if not please create the Authorized_keys all the machines manually

create file::
=========
>touch  Authorized_keys

Inventory::
============

add the all the node machines to hosts which is Ansible installed home directory 

>ubuntu@ip-172-31-6-13:~$ sudo -i

root@ip-172-31-6-13:~# su ansible

ansible@ip-172-31-6-13:/root$ cd ~

ansible@ip-172-31-6-13:~$ cd /etc/ansible/

ansible@ip-172-31-6-13:/etc/ansible$ ls

ansible.cfg  hosts  roles

Ansible installed Home Directory::
======================
>/etc/ansible/


Verify Ping the Machines::
============================

ansible@ip-172-31-6-13:/etc/ansible$ ansible -m ping all
[WARNING]: Platform linux on host node2@172.31.0.185 is using the discovered Python interprete
/usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
node2@172.31.0.185 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host node1@172.31.11.24 is using the discovered Python interprete
/usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
node1@172.31.11.24 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansible@172.31.6.13 is using the discovered Python interpret
at /usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
ansible@172.31.6.13 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}


all these 3 machine ping to each other and see beow screenshots all 3 machines pings each other


Key Concepts::
==============

Playbook: A playbook is a file that contains one or more "plays." Each play defines a set of tasks to be executed on a group of hosts. The playbook can be used for things like installing packages, managing users, configuring services, etc.

Task: A task is an individual unit of work. Tasks define specific actions, such as installing a package, starting a service, or copying a file. Tasks are executed sequentially, in the order in which they are written in the playbook.

Inventory: An inventory is a list of hosts that Ansible will manage. The inventory file defines which machines to target. An inventory can group hosts together (e.g., web servers, db servers) for easy management.

Modules: Ansible provides numerous modules that are responsible for performing specific tasks like managing packages, services, files, etc. Common modules include apt, yum, service, copy, and file.


Structure of a Basic Playbook:
===============================
A basic playbook has the following components:

YAML Header: The file begins with a --- to indicate it’s a YAML file.

 the hosts (target machines)
 become: yes   ----->Sudo user 

Tasks: Tasks define the actions to be executed on the target systems.

![image](https://github.com/user-attachments/assets/71982463-6b41-4481-af94-29c76690b0b6)

I want to see where the Ansible is installed on ACS
>cd /etc/ansible

NOTE::
==========

Playbook is written in YAML format

Inside the playbook tasks

Each task is a module

Playbook is a one of yaml file

Yaml file is a collection of key-value pairsset of all tasks

Playbook is tell to the ansible what are the tasks can be performed

Each task  one module

Module is a smallest item of ansible

Module can be used to individual or smallest task can be performed

Any configuration management tool should maintain ‘state’


hosts: all (apply all we can be mentioned in inventory )

become: yes  (become user as a sudo user)

tasks:


we can search in google ansible playbook

https://docs.ansible.com/ansible/latest/user_guide/playbooks.html

https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html#basics





08/09/2025::
===========


install git example playbook::
==============================

---
- hosts: all

  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

     
note:::default state is present 
update_cache: yes tells Ansible to run the apt-get update command on the remote machine before performing any further package operations (like installing or upgrading packages).
become: yes  # Elevate privileges to execute tasks as root

java install playbook::
https://www.geeksforgeeks.org/how-to-install-java-using-ansible-playbook/




java and git install playbook::
---
- hosts: all
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

  -  name: Install Java
    
     apt:
     
       name: openjdk-17-jdk
     
       state: present

>sudo vi demo.yml

copy git playbook code to demo.yml

---
- hosts: all
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

     

Run the playbook::
===============

>ansible-planbook <playbookname>

>ansible-playbook demo.yml

![image](https://github.com/user-attachments/assets/9bc02cd9-6749-4a09-a7d3-218110fd00d1)

ansible@ip-172-31-28-207:/etc/ansible$ ansible-playbook demo.yml

![image](https://github.com/user-attachments/assets/7df9edfc-af27-4815-b340-482237dfc368)


PLAY [all] **************************************************************************************************************************************

TASK [Gathering Facts] **************************************************************************************************************************
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12, but future installation of
another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [localhost]
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [ansiblenode2@172.31.30.200]
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [ansiblenode1@172.31.20.135]

TASK [install git] ******************************************************************************************************************************
ok: [localhost]
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]

PLAY RECAP **************************************************************************************************************************************
ansiblenode1@172.31.20.135 : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
ansiblenode2@172.31.30.200 : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
localhost                  : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

ansible@ip-172-31-28-207:/etc/ansible$


install git and jdk17 insatlled playbook::
======================================

---
- hosts: localhost
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes
     
  -   name: Install Java jdk17 on ubuntu machine
 
      apt:
      
        name: openjdk-8-jdk
      
        state: absent
      
        update_cache: yes

Usefull Google links::
===========

https://docs.ansible.com/ansible/2.9/modules/list_of_all_modules.html
https://docs.ansible.com/ansible/2.9/modules/apt_module.html#parameters
https://www.geeksforgeeks.org/how-to-install-java-using-ansible-playbook/
https://www.yamllint.com/
https://www.geeksforgeeks.org/how-to-install-tomcat-using-ansible-playbook/




Executing ansible in 2 ways
1.	Adhoc command  yearly base
2.	Playbook (YAML/YML) format use for repetitive work

When we can use adhoc commands  ->I want restart servers yearly base 

if you can use system inventory, below is the command
>ansible-playbook <playbookname>
>ansible-playbook hello-world.yml

I don’t want to use system level inventory

Inventory::
==========
where hosts/ipaddress are stored

I want to create my own inventory

>Cd /etc/ansible

![image](https://github.com/user-attachments/assets/e03cd989-34e8-46f5-88d0-9af56f11b6d9)

![image](https://github.com/user-attachments/assets/7a4d1993-1c1e-4da6-94b0-eeb105cb0d36)

![image](https://github.com/user-attachments/assets/79f8fb33-19d1-47a9-b26e-aff30d75d408)

>cat /etc/ansible/hosts

Sudo vi hosts

Copy all hosts

![image](https://github.com/user-attachments/assets/bcda07ba-ab66-4b86-bf67-f7ad9c556230)

I want categories into Inventory groups::
===================================

In Ansible, inventory groups are used to organize and categorize hosts (machines or servers) into logical groups. This allows you to apply tasks to specific sets of servers, simplifying playbook management and execution. An inventory is a list of managed hosts and their associated metadata, and groups are one of the key components of that structure.

Here’s a detailed explanation of Ansible inventory groups

1. What Are Inventory Groups?
An inventory group in Ansible is a way to group hosts based on a shared characteristic. For example, you might have groups for different environments (e.g., dev, prod), different types of servers (e.g., web_servers, db_servers), or other logical categories that fit your needs.

static inventory groups defined in the standard INI or YAML format.

# Define groups of hosts:: >sudo vi hosts

[web_servers]
node1@172.31.11.24

[App_servers]

node2@172.31.0.185
ansible@172.31.6.13

[DB_servers]

node1@172.31.11.24
node2@172.31.0.185
ansible@172.31.6.13
 
i want to insatll 3 spfwares :: below playbook name -----> installsoftware.yml
==============================

---
- hosts: web_server
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

  -  name: install tree
    
     apt:
     
       name: tree
     
       state: present  

  -  name: install apache
  
     apt:
     
       name: apache2
     
       state: present

once above two files created run the below command

>ansible-playbook -i hosts installsoftware.yml
     
![image](https://github.com/user-attachments/assets/36d33a9a-b113-402c-80f7-1e9c404a245b)

>ansible -i hosts -m ping Webserver

Best practice is you need to create our own inventories

>sudo vi hosts

after ran the above yaml, please try to access all machines with IPaddresss

![image](https://github.com/user-attachments/assets/4a7778cd-6b97-4822-ad5e-11bbdde82231)

![image](https://github.com/user-attachments/assets/96a67d2a-993a-47ff-aa79-3dc8cd7aa06a)

![image](https://github.com/user-attachments/assets/01ee5e45-446e-42f2-a47f-c8b3e2fbe2f5)

Please enabled Inbound and Outbound rules::
=======================================

Inbound and outbound rules refer to the types of network traffic that are allowed or denied to and from a system, such as a server, virtual machine, or network device. These rules are typically defined in firewalls or security groups (such as in cloud environments like AWS, Azure, or Google Cloud). The primary goal is to control which data can enter or leave a network, ensuring security and proper access control.

Here’s a detailed explanation of inbound and outbound rules:

 Inbound Rules::
Inbound rules control traffic entering a system or network. These rules define which types of external traffic are allowed to reach a server, instance, or device.

Common Uses:
Allowing specific users or services to access the system.

Restricting access to the system from unauthorized users.

Opening ports for services like web servers (HTTP, HTTPS), SSH, database connections, etc

Allowing incoming traffic on port 80 (HTTP) so that users can access a web server.

Outbound Rules::
Outbound rules control traffic leaving a system or network. These rules define which traffic is allowed to exit a server or device and reach external destinations.

Common Uses:
Allowing a server to access external services like APIs, databases, or external servers.

Restricting unwanted traffic from the system to external destinations.

Controlling the flow of outgoing traffic to ensure compliance with security policies.

Allow HTTP/HTTPS: Allow outbound traffic on ports 80 (HTTP) and 443 (HTTPS) to any IP:



![image](https://github.com/user-attachments/assets/0e51f799-d746-45a5-94cb-f358ade65ba2)

![image](https://github.com/user-attachments/assets/8fa024b7-0999-40f7-94cb-3eaa018fbd41)

![image](https://github.com/user-attachments/assets/2ca3de47-8bea-4f5a-a35e-0238788cb7c7)




09/09/2025::
================


Install LAMP on ubuntu 24.04::
==================================

A LAMP stack stands for Linux, Apache, MySQL, and PHP, which is a popular open-source software stack used for web development. It provides everything you need to set up a dynamic website or web application.

Here’s a quick overview of each component:

Linux: The operating system (in this case, Ubuntu).

Apache: The web server that serves your website’s files.

MySQL: The database management system for storing and retrieving data.

PHP: The programming language used for dynamic web page generation.



Manual Steps::
====================

https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu


>sudo apt update

>sudo apt install apache2

>sudo apt install mysql-server

>sudo apt install php

>sudo apt install libapache2-mod-php

>sudo apt install php-mysql

>sudo systemctl restart apache2

>sudo apt install php-cli

>sudo nano /var/www/html/info.php

above steps are manually installed all required softwares in LAMP project but my requirement is to write a Playbook for those manuall steps

Playbook for LAMP::  phppackage.yml
=====================



---
- hosts: all

  become: yes

  tasks:
  
  -  name: install apache2

     apt:

     name: apache2

     state: present

     update_cache: yes

  -  name: install php

      apt:

      name: php

      state: present  

  -  name: install mysql-server

     apt:

      name: mysql-server

      state: present
     
  -  name: install libapache2-mod-php

     apt:

     name: libapache2-mod-php

     state: present
                   
  -  name: install  php-mysql

     apt:

     name: php-mysql

     state: present
     
  -  name: restart apache

     service:

     name: apache2

      enabled: true

     state: restarted

  -  name: install php-cli

     apt:

     name: php-cli

      state: present 

  -  name: copy module info.php

     copy:

     src: info.php

     dest: /var/www/html/info.php     


Copy Module::
=========

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.html

Service Module::
==================

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_module.html

info.php ::
==========


hosts grouping:
================

![image](https://github.com/user-attachments/assets/2eb4e4d2-bda2-44fa-8e86-d4b5bd51ed9e)


[web_servers]
node1@172.31.11.24

[App_servers]

node2@172.31.0.185
ansible@172.31.6.13

[DB_servers]

node1@172.31.11.24
node2@172.31.0.185
ansible@172.31.6.13


Reference flow::
==============
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ls
hosts  info.php  installsoftwares.yml  phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi hosts
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ansible-playbook -i hosts phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi info.php
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ansible-playbook -i hosts phppackage.yml

PLAY [Webservers] *********************************************************************************************

TASK [Gathering Facts] ****************************************************************************************
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12,
but future installation of another Python interpreter could change the meaning of that path. See
https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [localhost]
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at
/usr/bin/python3.12, but future installation of another Python interpreter could change the meaning of that
path. See https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [ansiblenode2@172.31.30.200]
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at
/usr/bin/python3.12, but future installation of another Python interpreter could change the meaning of that
path. See https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [ansiblenode1@172.31.20.135]

TASK [install apache2] ****************************************************************************************
ok: [ansiblenode2@172.31.30.200]
ok: [ansiblenode1@172.31.20.135]
ok: [localhost]

TASK [install php] ********************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install mysql-server] ***********************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install libapache2-mod-php] *****************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install  php-mysql] *************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [restart apache] *****************************************************************************************
changed: [ansiblenode2@172.31.30.200]
changed: [localhost]
changed: [ansiblenode1@172.31.20.135]

TASK [install php-cli] ****************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [localhost]
ok: [ansiblenode2@172.31.30.200]

TASK [copy module info.php] ***********************************************************************************
changed: [localhost]
changed: [ansiblenode2@172.31.30.200]
changed: [ansiblenode1@172.31.20.135]

PLAY RECAP ****************************************************************************************************
ansiblenode1@172.31.20.135 : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
ansiblenode2@172.31.30.200 : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
localhost                  : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0



Please execute above steps we will see the php insatlled on all 3 machines

![image](https://github.com/user-attachments/assets/d49aa2d0-69ad-4c40-8408-2ccf3edbf838)

![image](https://github.com/user-attachments/assets/74b9e6dd-8fb1-452f-85f1-faffd48d7dae)

![image](https://github.com/user-attachments/assets/6d58255a-e6ea-44b7-a4e2-39f8598358b3)


info.php::
===========

  <body>
    <h1><?php
phpinfo();</h1>

   


loop::
===========


In Ansible, loops are used to repeat tasks over a list of items, making automation more efficient and reducing redundancy in playbooks. You can loop through arrays, dictionaries, and other types of data in Ansible to execute tasks multiple times.

There are several ways to use loops in Ansible, and here are the most common methods:

1. Using loop keyword
The loop keyword is the most common way to iterate over a list of items. Here's an example of how to use it:

https://spacelift.io/blog/ansible-loops

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html


Examples::
==========

---
- hosts: Webservers

  become: yes

  tasks:

    - name: Install all packages
   
      apt:
    
	name: "{{ item }}"

        state: latest

     loop:
        -  apache2
        -  php
        -  php-mysql
        -  libapache2-mod-php
        -  php-cli
    -  name: restart apache

        service:

       name: apache2

        enabled: true

       state: restarted

    -  name: copy module info.php

       copy:

       src: info.php

       dest: /var/www/html/info.php  




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/375e7785-3440-448e-bee3-e4e92ee5da53" />



http://34.227.192.10/info.php


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ed0477eb-5c9e-4902-9443-abdcd0a0fc79" />


please verify all the node machines 


http://13.218.99.248/info.php


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/58969708-7c41-4a97-ac0d-7edf78dc8e37" />





10/09/2025::
============

Setup module in ansible::
============================


https://docs.ansible.com/ansible/latest/collections/ansible/builtin/setup_module.html
Setup module is used to collect the facts
Facts information gather from nodes called facts

>ansible -I hosts -m setup Webserver

Using filter command

>ansible -i hosts -m setup -a "filter=*os*" Webserver

ansible_os_family": "Debian"

Ansible when statements

https://docs.ansible.com/ansible/latest/user_guide/playbooks_conditionals.html#the-when-statement


ansible_os_family": "Debian"

When condition is always used bottom of the script and using scrips we can able to run a playbook on a different platforms 

1.Debian

2.Redhat
---
- hosts: Webserver

  become: yes

  tasks:
  - name: install apache

    apt:
      name: apache2

    state: present

    update_cache: yes

    when: ansible_os_family == "Debian"  
  - name: install apache

    yum:

    name: httpd

     state: present

    when: ansible_os_family == "Redhat"




In Ansible, variables are used to store values that can be referenced and used throughout your playbooks, roles, and tasks. This allows for dynamic, reusable, and flexible automation. Here’s a basic breakdown of how Ansible variables work and the different ways you can define and use them:


define variables in 3 places::
===============================

1.	Inventory level  lowest priority

   a. host level variabels
  
  node1@172.31.27.17 package_name=apache2
  
  package_name=httpd
  
  b. group level variabels

[web_servers]
node1@172.31.27.17 

package_name=apache2

2.playbook level  ---2nd highest priroty 

vars:
    package_name: git

3.	Command line level –highest level priority

>ansible-playbook -i srinfotechhosts -e "package_name=apache2" variable.yml

Inventory variables: These are defined in the inventory file (or dynamic inventory) for specific hosts or groups.

[webservers]
ansiblenode1@172.31.20.135  package_name=git
ansiblenode2@172.31.30.200 package_name=apache2
localhost 

[webservers:vars]
ansiblenode2@172.31.30.200 
localhost 

package_name=httpd

Playbook variables: You can define variables directly within your playbooks using the vars section.

---
- hosts: Webservers

  become: yes

  vars:

  pacakge_name: git

  tasks:
    
    - name: Install all packages

      apt:

      name: "{{ pacakge_name }}"

      state: present

      Command-line variables: You can pass variables to your playbooks at runtime using the -e or --extra-vars option.
      

      >ansible-playbook -i hosts -e "package_name=apache2" variables2.yml



Ansible resolves variable values based on a specific precedence order. The order from highest to lowest precedence is:
====================================================================================================================

Extra-vars (-e on the command line): Command-line variables take the highest precedence.

Playbook variables: Variables defined within the playbook.

Inventory variables: Variables set in the inventory.

Debug & vars & register in Ansible module::
==========================================

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/debug_module.html

---
- name: Echo message on localhost

  hosts: localhost

   connection: local

   gather_facts: no

   vars:

   message: "Hello from Ansible playbook on localhost!"

  tasks:
    
    - name: Echo message and connection type

      ansible.builtin.shell: "echo '{{ message }}' ; echo 'Connection type: {{ ansible_connection }}'"

      register: echo_output

    
    - name: Display output

      debug:

      msg: "{{ echo_output.stdout_lines }}"


>ansible-playbook -i hosts -vvv variable.yaml  --------> verbose logs purpose ,please run this command


![image](https://github.com/user-attachments/assets/7d18a6e5-a53b-436b-bf26-dbe1db0e89af)



Class NOTE::
==============

name: "{{ item }}"   ---->ansible jinja2 formate


apt

copy

services

loop

setup

facts

filter

when

debug

setup --is a one module in ansible 
     --used to collect the facts--TASK [Gathering Facts] 
	 
	 Facts:: information gathering from all the nodes machines
	 
>ansible -i srinfotechhosts -m setup -a "filter=*os*" web_servers
	 
	   "ansible_os_family": "Debian",
	   
	     when: ansible_os_family == "Debian"
		 


Ansible Variable::

int a =10

1.inventory level  ----lowest priorty 

  a. host level variabels
  
  node1@172.31.27.17 package_name=apache2
  
  package_name=httpd
  
  b. group level variabels

[web_servers]
node1@172.31.27.17 

package_name=apache2

2.playbook level  ---2nd highest priroty 

vars:
    package_name: git

3.command line	--->picking the variables command line is highest priority

>ansible-playbook -i srinfotechhosts -e "package_name=apache2" variable.yml

>ansible-playbook -i srinfotechhosts -vvv -e "package_name=apache2" variable.yml -->logs





11/09/2025::
===============

Ansible Roles::
===================


<img width="1648" height="648" alt="image" src="https://github.com/user-attachments/assets/ebb677ec-7471-46ec-a449-b154fda14ff6" />


Ansible roles are a way of organizing playbooks and tasks in a modular, reusable, and maintainable structure. They allow you to break down complex playbooks into smaller, focused units of functionality that can be easily shared and reused across different projects. Here's a more detailed look at Ansible roles:

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html

1.Written ansible in a reusable fashion

2.How do I use someone else’s work

3.Ansible galaxy is a place where we can find reusable roles

https://galaxy.ansible.com/

4.Which we can use in your script



install roles

 > Ansible-galaxy install <rolename>

 >ansible-galaxy install my_role

create my own role::

> ansible-galaxy init <rolename>

>ansible-galaxy init my_role



Structure of Ansible Roles::
===================

my_role/
├── defaults/
│   └── main.yml            # Default variables
├── files/
│   └── somefile            # Files to be copied to the target
├── handlers/
│   └── main.yml            # Handlers (usually for service restarts)
├── meta/
│   └── main.yml            # Metadata about the role
├── tasks/
│   └── main.yml            # The main tasks (this file includes other task files if needed)
├── templates/
│   └── config.j2           # Jinja2 templates for dynamic file creation
├── tests/
│   └── test.yml            # Test playbooks to verify the role works
├── vars/
│   └── main.yml            # Custom variables


Using Roles in Playbooks
Once you've defined a role, you can use it in your playbook like this:

---
- name: Example Playbook using roles
  hosts: all
  become: yes
  roles:
    - my_role

Benefits of Using Roles
Reusability: Roles can be reused across different playbooks and projects.

Modularity: Roles allow you to organize your playbook into smaller, manageable parts.

Clarity: Each role focuses on a specific task or function, making your playbooks more understandable.

Example Role: Installing Tomcat

https://galaxy.ansible.com/ui/standalone/roles/robertdebock/tomcat/install/


Create my own role

> Ansible-galaxy init rolename

![image](https://github.com/user-attachments/assets/af275783-63b6-40ab-a319-645db283a40f)

![image](https://github.com/user-attachments/assets/34cfe34b-b8bc-4026-9014-0c07c952c3af)

Install tomcat

If you're looking to install or use an Ansible role for Tomcat from Ansible Galaxy, you can search for available roles and collections related to Tomcat. Here's how you can find and use a role related to Tomcat from Galaxy.
1.	Search for a Tomcat Role

https://galaxy.ansible.com/

To search for a role related to Tomcat on Ansible Galaxy, you can use the following command:
bash
Copy
ansible-galaxy search tomcat
This will return a list of roles related to Tomcat that you can install and use.

2. Install a Tomcat Role
Once you’ve found a suitable role for Tomcat, you can install it using the ansible-galaxy install command.
For example, if you find a role called geerlingguy.tomcat, you can install it by running:
bash
Copy

> ansible-galaxy install geerlingguy.tomcat

This will download and install the role into your ~/.ansible/roles/ directory (or the path defined in your ansible.cfg file).
3. Use the Installed Tomcat Role in Your Playbook
After installing the role, you can use it in your playbook. Here’s an example of a simple playbook that installs and configures Tomcat:
yaml
Copy

Deploywar.yml::
=============

---
- hosts: localhost
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
 
  > ansible-playbook -i hosts Deploywar.yml
  

![image](https://github.com/user-attachments/assets/306fd1fc-8c51-40f7-81b6-41a44e6ee915)

  
This will use the geerlingguy.tomcat role to set up Tomcat on your webservers hosts.

https://galaxy.ansible.com/robertdebock/tomcat

![image](https://github.com/user-attachments/assets/29cfc5e4-b8e6-494b-a462-d8a11699df12)

Deploywar.yml

![image](https://github.com/user-attachments/assets/d7f4d510-bee2-4d32-ad56-7906a8574e93)

![image](https://github.com/user-attachments/assets/adad9ea6-ed52-457e-a9eb-adb2d19ad026)

![image](https://github.com/user-attachments/assets/a4c880aa-f378-4085-9122-3ef93a25e09a)


By default  tomcat run port 8080

http://18.236.181.244:8080/

http://34.216.173.44:8080/manager/html

![image](https://github.com/user-attachments/assets/fa5faaeb-ec9e-43f2-9184-7bf46f1433c4)


> /opt/tomcat/conf

>sudo vi tomcat-user.xml

><role rolename="manager-gui"/>

<role rolename="manager"/>

 <role rolename="manager-script"/>

 <role rolename="manager-jmx"/>
 
 <role rolename="manager-status"/>
 
 <role rolename="tomcat"/>

 <role rolename="admin"/>

 <user username="admin" password="admin" roles="manager-gui,manager-script,manager-jmx,manager-status,tomcat,admin,manager"/>


 <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/6f29bc01-cc9c-4917-9add-e65325cb83f0" />


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/f2b606e6-58ff-48ed-a79b-2aecbee644f2" />


We can seen shutdown.sh & startup.sh
>sudo sh shutdown.sh

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/6a10157d-80ae-40d2-8ed2-5eefbecea344" />


>sudo sh startup.sh

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/62c3f5f5-e26d-4014-81c1-ec194e6fd2e5" />


After added we need to restart the tomcat
>sudo service tomcat status

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/9007a5d6-1b03-4c6c-b2f5-29ec69913240" />


Resolutions for tomcat manager access::
=======================================

https://stackoverflow.com/questions/36703856/access-tomcat-manager-app-from-different-host


For Tomcat v8.5.4 and above, the file <tomcat>/webapps/manager/META-INF/context.xml has been adjusted:

<Context antiResourceLocking="false" privileged="true" >
    <Valve className="org.apache.catalina.valves.RemoteAddrValve"
         allow="127\.\d+\.\d+\.\d+|::1|0:0:0:0:0:0:0:1" />
</Context>

		Change this file to comment the Valve:
<Context antiResourceLocking="false" privileged="true" >
    <!--
    <Valve className="org.apache.catalina.valves.RemoteAddrValve"
    allow="127\.\d+\.\d+\.\d+|::1|0:0:0:0:0:0:0:1" />
    -->
</Context>

After that, refresh your browser (not need to restart Tomcat), you can see the manager page.


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/f1ba1fed-334a-4c30-9ec3-f3b73ccdeada" />


Most of the work is done 
Where is my war file



Deploy Onlinebook store war to tomcat server using roles::
==============================================================

>If war file is available in local machine use copy module

>if war file is available other machine(internet) use get_url module

Tomcat by default install

>/opt/tomcat

From root folder we need to access webapps folder in tomcat otherwise permission denied

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/d9c49b34-6eb5-4c60-9a09-6caa62258acf" />


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/baebcc3a-b9f9-47ff-9290-94e96ee4e621" />



---
- hosts: Webservers
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
  tasks:
  - name: copy war
    get_url:
      url: https://srinfotech.s3.us-west-2.amazonaws.com/jobs/AnsibleIntegartedWith+Jenkins/5/onlinebookstore.war
      dest: /opt/tomcat/webapps/onlinebookstore.war


![image](https://github.com/user-attachments/assets/d43d4d4a-ee8d-4dd8-af09-b71dfdf2da6f)

Create S3 Bucket in AWS account::
===============================

Go to AWS account and search S3 bucket 

S3=SSS=simple storage services

![image](https://github.com/user-attachments/assets/8c1b5637-9392-414d-ab0b-21bf9d882609)

Select S3

![image](https://github.com/user-attachments/assets/c62a298f-185d-43ec-9d62-8b874e7627ec)

Click Create bucket

![image](https://github.com/user-attachments/assets/097eedf8-8e2f-48f5-876f-2c3debfccda8)

Bucket name provide

![image](https://github.com/user-attachments/assets/669f5b5a-d4e4-43ee-add1-e6be36171ec4)

Object Ownership  ---- ACLs enabled selected


Unchecked Block all public access


![image](https://github.com/user-attachments/assets/61cac919-cbbd-4b39-9121-d1ed20e33bcd)

Ackened 

![image](https://github.com/user-attachments/assets/9edcd3b0-c71a-4e78-8132-0469a192cd82)

Click crete bucket

![image](https://github.com/user-attachments/assets/c0b39afe-325c-4d82-9ea6-2204896c1f55)

S3 bucket is created in AWS

![image](https://github.com/user-attachments/assets/702e2185-29cd-43d2-9176-ad9788907bc8)

S3 bucket Created successfully


![image](https://github.com/user-attachments/assets/3c2855d7-ae2c-4f18-8ce7-3b766211b811)

Click Bucket

![image](https://github.com/user-attachments/assets/3000b5bc-8691-40cc-b5ee-e378fe813bf6)


Click Upload 


![image](https://github.com/user-attachments/assets/71efca18-9c4a-4bad-97ff-6e6baf6b559c)

Click Add Files


![image](https://github.com/user-attachments/assets/e74175f3-ca04-47bb-977b-9f9df1cf7139)

Select Onlinebookstore.war file

![image](https://github.com/user-attachments/assets/89cac099-5c85-4a29-91e9-8868f2e2f020)

Select check box to upload the onlinebookstore.war file

![image](https://github.com/user-attachments/assets/30c81ce3-4605-45e9-90bd-b719dac4d875)

Click Upload

![image](https://github.com/user-attachments/assets/85a5204d-b660-4d0c-8983-fc24b05427e4)

Upload Succeeded

![image](https://github.com/user-attachments/assets/11d79c2d-c353-404c-be41-130608b34dcb)

Copy URL

![image](https://github.com/user-attachments/assets/147864ff-fc89-4ae1-b104-b383cccba33b)

![image](https://github.com/user-attachments/assets/37ad0996-d054-4a3b-aa57-c0480254c1c1)

Copy url to below script:: onlinebookstore.yml
===================

---
- hosts: localhost
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
  tasks:
  - name: copy war
    get_url:
      url: https://srinfotech.s3.us-west-2.amazonaws.com/jobs/AnsibleIntegartedWith+Jenkins/5/onlinebookstore.war
      dest: /opt/tomcat/webapps/onlinebookstore.war

[image](https://github.com/user-attachments/assets/402272bc-6604-4840-a406-c1cc8e95dcc6)

run the playbook

>ansible-playbook -i hosts onlinebookstore.yml

[image](https://github.com/user-attachments/assets/4ed55d65-f16e-4314-8dba-c3a34c3ee5c2)

Success

[image](https://github.com/user-attachments/assets/592b947e-d422-4430-9729-98724403ce0d)

Verify deployment in Tomcat server

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d684c18-b2f2-4423-955c-b49381c069f0" />


http://54.218.133.244:8080/onlinebookstore/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b9844e78-13b9-4f8f-81ae-e3570c154d08" />





12/09/2025::
==============


Integrated Ansible & Tomcat & S3 With Jenkins::
===============================================


<img width="1658" height="659" alt="image" src="https://github.com/user-attachments/assets/85499e98-21ec-4a2c-aabd-3da2ed245ade" />



S3 bucket creation and integrate S3 with Jenkins::
=====================================================

Go to AWS account and search S3 bucket 

S3=SSS=simple storage services


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4e33113d-eb98-4698-afe0-7f8cb408cdaf" />


 

Select S3


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e84a1343-0546-4f4f-b893-7daf06e3102d" />


 

Click Create bucket

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6bfd7268-9b17-4f27-ab49-de7c0b5dbdc4" />



AWS region  --virgenia

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e4409642-7012-4d56-a5a6-c3538e08c02c" />



Bucket name provide


 

Object Ownership  ---- ACLs enabled selected


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c70111a2-32de-478c-b3a6-d07ffdae7977" />



Unchecked Block all public access


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d189e2d-acdb-4916-9479-f5d60cf75c59" />



Ackened 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7974546a-fb2c-47e4-9ba8-f546b8b8ba9b" />



Click crete bucket



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/741009c2-c3b6-476f-992e-a427e8f1599d" />


 

S3 bucket is created in AWS


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8e984a31-ed36-4b7b-b24d-fad25742cce8" />


 

First installed Jenkins in AWS ubuntu machine

Installed S3 publisher plugin

Found S3 profile at system configuration


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aed033d1-2942-4674-888e-baa19124e183" />


 

Second step::
Create IAM role in AWS account

 IAM----> Indentity Access Management

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/04977423-4c53-4e34-9cfd-0e562c70b6e2" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4605e66b-87c1-46b3-9870-1c77aba8d748" />


 

Click Users

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5cb8da36-c32c-458a-ace3-5a3030b01d61" />


 

Click create user


 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5ec439c1-6f79-4e04-a760-845b663f73b6" />



Provide the user name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a900d05-4427-4e90-aefd-3cbc393a8d63" />


 
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1cd30a12-b8d4-422e-80fb-710a3d8b60c1" />


 
Click next
 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/96ddc6c1-3d33-4f16-bc21-52b87dde776f" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dfaa67ba-28c6-4111-89d7-7d4009b5f892" />

 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/15dd1e6a-5b6a-48df-a01a-a5a10bf32d57" />


 
 
select S3 policies


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/443e9b97-88ce-4050-82a6-1175b031f33a" />




User created successfully

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f95449c8-f412-43f4-a3dd-c6c399e3f5a3" />


 
User name::

SRInfotech

Console password::

wv9PC8%3


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/23b2214e-b14b-449c-97eb-c9ac365b3b56" />


  


Create access & secret keys:;

Open new user test


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2c81aed4-10cb-4796-9fec-f40f91d3f652" />



Click create access key

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f4f17a10-5db8-476d-967f-d2044701fb54" />




Select Application running on an AWS compute service


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7e12d35b-b095-48d6-bf58-f659aa6f1bf3" />


 

Click next





Access keys created


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0580c3b4-e5f0-4398-b8d5-772fb11f6679" />


 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/eae25e69-c918-4b66-8a1d-38a3d9655589" />




Integaretd S3 with Jenkins


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1cb3d21d-9c6d-4b34-afc6-c7dd20ccdefc" />


 

Provided access and secret key

Click test connection


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60b57bed-42ae-45d2-8d51-7ea1c0039fd3" />


 

Check passed


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7394e83a-de5e-49bd-b708-d8207b8133c2" />



Bucket region us-east-1

 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1787457e-4e35-4b1a-aba3-75baf19cecb0" />


 

Destination bucket:: should be give AWS bucket name

 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aa86d517-cdf8-4ff3-a831-7f264bc81035" />


 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b7c2123e-b2a7-465c-a872-afccfc01fef3" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/839cbab1-d1f6-439f-9068-7ee2d6dae1f3" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7045f250-77a5-4687-9b33-c0de5ba53d26" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5bdd20e2-c8ed-4a86-ae42-26afc62bffbc" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b3b59c26-7ac5-4880-9ed3-8e1b02e683b5" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e6f9bdd1-05fb-4d20-b4cc-b4f5da39c361" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0e3e01ef-c0cc-404c-9c94-98c1794ebcad" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/861390cb-6d8b-42e5-84d3-f0a4094345a4" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/84942dea-94a8-4112-a786-61646a97cc8c" />



Should be enabled Manage artifacts options


 Publish artifacts to S3 Bucket Build is still running
Publish artifacts to S3 Bucket Using S3 profile: S3Publisher
Publish artifacts to S3 Bucket bucket=srinfotech3, file=onlinebookstore.war region=us-east-1, will be uploaded from slave=false managed=true , server encryption false
Finished: SUCCESS

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/853ad6fa-e0c0-4c41-bcb5-9109fa3f79aa" />





15/09/2025::
===============



 Docker Introductions::
=================

Docker is an opensource & Applicatuions level virtualization technology and it's called containirazition.

Docker is an open-source platform that automates the deployment, scaling, and management of applications in lightweight, portable containers. Containers are isolated environments that package an application and all its dependencies (such as libraries, binaries, and configurations) to ensure it runs uniformly across different computing environments.

<img width="1162" height="449" alt="image" src="https://github.com/user-attachments/assets/6f4d8e0c-cc94-4210-84be-f7d7898aad1d" />


Docker is a platform and that make it easier to create, deploy, and run applications using containers. Containers are lightweight, standalone, and executable units that include everything needed to run a piece of software, including the code, runtime, libraries, and system tools.

container ::
==============
1.container is an insolation area of executuions of your applications
 OR
 instance of images are called containers
2.Containers are created from “images”
3. Containers are the core of Docker. They are lightweight, portable, and isolated environments where applications run.
  Docker is run your software packages /Applications  in containers called containarizations.

4. if you build a docker container for your application called containerization
5. containers have it’s own boundaries  

who will create containers?
Ans --docker images are created the containers

 Docker Images:
 ===============

 docker image is a package with all dependencies and the necessary 
information to create the container and docker image derived from multiple base images.

An image is a snapshot of a container, a blueprint that defines what the container will contain and how it will behave when run. It consists of an application and its dependencies. Docker images are built using a Dockerfile

Docker Registry::
====================

A Docker Registry is a system for storing and distributing Docker images. It is a centralized location where Docker images can be uploaded (pushed), stored, and downloaded (pulled) by users and applications. Docker images are the building blocks of containers, and registries provide a way to manage, version, and share these images across different environments.

Default registry :: https://hub.docker.com/

Physical & Virtual & Hypervisors/VMwares::
=============================================

1.tomcat & nodejs containers have it’s own process tree,own files systems,own network interfaces own storage,ram…etc
2.when you want to give application to your team/testers  docker is the best choice and when you want give system to your team/ testers VMwares are best choice.
3.application level virtulization docker is the best choice and OS level virtulization VMwares are best choice
4.individually scale the your application very easy in docker

<img width="1162" height="449" alt="image" src="https://github.com/user-attachments/assets/05494c3a-210c-4a65-a07e-59f6170d17cf" />



Example:: For festival season In your organization leave management application multiple employees are applied leaves at the same time in that scenario docker is very easy to scale the one more application but physically it’s very difficult so docker is the best choice


<img width="1162" height="449" alt="image" src="https://github.com/user-attachments/assets/4645b5bb-9c8f-485c-b2d2-bcf8a2c34fbb" />




16/09/2025::
==============

Install Docker in Ubuntu machine::
=====================================

Please follow below link steps to install the docker in ubuntu and please read all the content in that link

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04

once installed docker please verify below commands::

>docker --version

root@ip-172-31-20-86:~# docker --version
Docker version 28.0.4, build b8034c0

root@ip-172-31-20-86:~# docker info
Client: Docker Engine - Community
 Version:    28.0.4
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.22.0
    Path:     /usr/libexec/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v2.34.0
    Path:     /usr/libexec/docker/cli-plugins/docker-compose

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 0
 Server Version: 28.0.4
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Using metacopy: false
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: systemd
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 05044ec0a9a75232cad458027ca83437aae3f4da
 runc version: v1.2.5-0-g59923ef
 init version: de40ad0
 Security Options:
  apparmor
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.8.0-1024-aws
 Operating System: Ubuntu 24.04.2 LTS
 OSType: linux
 Architecture: x86_64
 CPUs: 2
 Total Memory: 3.82GiB
 Name: ip-172-31-20-86
 ID: 201c6f4b-75d3-4326-adf5-00b9a82a8d4d
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 Experimental: false
 Insecure Registries:
  ::1/128
  127.0.0.0/8
 Live Restore Enabled: false

if above page is came without any erros, it means docker is installed in your machine


Docker High Level Client -Server Architecture::
==================================


<img width="1700" height="665" alt="image" src="https://github.com/user-attachments/assets/0c95b9d4-34ac-4795-aa30-addb1952b6a3" />



Docker's high-level architecture revolves around several components that work together to provide containerization and isolation for applications


Docker Client (CLI)::
=================

The Docker Client is the primary interface for interacting with Docker. It can be a command-line interface (CLI), like the docker command, or a graphical interface (GUI) in some tools.

It allows users to interact with Docker's features, such as building containers, running containers, and managing containers and images.

It sends requests to the Docker Daemon to execute commands.

Docker Daemon (Dockerd)::
====================

The Docker Daemon (also known as dockerd) is the core component of Docker. It runs in the background on the host system.

The daemon is responsible for managing Docker containers, images, networks, and volumes. It listens for Docker API requests and handles container lifecycle operations such as starting, stopping, and building containers.

The Docker Daemon can communicate with multiple Docker clients, allowing for distributed management of containers.

Flow:
============
1.The Docker Client sends a command to the Docker Daemon.

2.The Docker Daemon interacts with containers, images, and storage volumes.

3.The Docker Daemon can pull images from a Docker Registry.

4.The Docker Daemon runs containers based on the images and handles networking and storage.

Docker commands::
====================

 >docker pull <imagename>

 >docker pull hello-world

 >docker images   ----used to display the all images

 > docker image ls ----used to display the all images
 
 >docker run ---used to build the images and create the container


Class Note Docker commands::
==============================


Docker commands::

>docker pull <imagename>

>docker pull hello-world

>docker images

Common Commands:
  run         Create and run a new container from an image
  
  exec        Execute a command in a running container
 
  ps          List containers
  
 
  build       Build an image from a Dockerfile
  
  bake        Build from a file
 
  pull        Download an image from a registry
 
  push        Upload an image to a registry

  images      List images
 
  login       Authenticate to a registry
 
  logout      Log out from a registry
 
  search      Search Docker Hub for images
 
  version     Show the Docker version information
  
  info        Display system-wide information

>docker pull <imagename>:<tagname>

>docker pull hello-world:latest

>docker run hello-world:latest

>docker ps

>docker ps -a

>docker rm <containerID> OR <containerName>

NOTE:: one image we can able to cerate number of containers

>docker rm $(docker ps -a)

i want install jenkins using docker conatiners

>docker run -p 8080:8080 jenkins/jenkins:jdk17\

>docker run -d -p 8080:8080 jenkins/jenkins:jdk17
 running the contaenr in background
 
 >docker run -d -p 8080:8080 jenkins/jenkins:jdk17
 
 go to the inside the conatainers pleas euse below command
 
 >docker exec -it <containerID> /bin/bash

 >docker exec -it 1d9f1ee478e5 /bin/bash

Create the Jenkins container::
=================================

>docker run -d -p 8080:8080 jenkins/jenkins:jdk21


http://35.155.150.89:8080/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/530aabac-2e7f-4db6-aa07-bde32e46cd12" />



>docker ps

above command is used to verify the how many containers are running




17/09/2025::
================


Create the Nginx web based application container::
=======================================================

>docker run -d -p 80:80 nginx:latest

http://35.155.150.89/

![image](https://github.com/user-attachments/assets/003a7ca7-5a81-4ea6-8b60-3c1dd0b7a74d)


>docker ps

above command is used to verify the how many containers are running, you can seee nginx container is running state



detached mode::
=================

Docker detached mode refers to running a container in the background

>docker run -d <image_name>

example::
> docker run -d nginx

Where:

-d is the flag for detached mode.

<image_name> is the name of the Docker image you want to run.

> docker run -d nginx

This command will:

Run the nginx container in detached mode.

Start the container in the background.

To view the containers running in detached mode, you can use the docker ps command:
======================================

>docker ps

Stopping a Container::
=================

>docker stop <containerID>

Start a Container::
=================

>docker start <containerID>

To run a command inside a running container:
======================

>docker exec -it <container_id_or_name> <command>
>docker exec -it 5336d949f33b /bin/bash

>root@5336d949f33b:/# hostname
5336d949f33b
>root@5336d949f33b:/# hostname -i
172.17.0.3


![image](https://github.com/user-attachments/assets/c7114894-3fcd-46b0-b393-6f296d23b845)

NOTE:::
=========

>docker exec -it 5178eb58223a /bin/bash
Use this command inside the container

>ctrl pq
Outside the containers

Lab practice::
===============

take one nginx web server

>docker pull nginx

root@ip-172-31-20-86:~# docker pull nginx
Using default tag: latest
latest: Pulling from library/nginx
6e909acdb790: Pull complete
5eaa34f5b9c2: Pull complete
417c4bccf534: Pull complete
e7e0ca015e55: Pull complete
373fe654e984: Pull complete
97f5c0f51d43: Pull complete
c22eb46e871a: Pull complete
Digest: sha256:124b44bfc9ccd1f3cedf4b592d4d1e8bddb78b51ec2ed5056c52d3692baebc19
Status: Downloaded newer image for nginx:latest
docker.io/library/nginx:latest

>docker images

root@ip-172-31-20-86:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   latest    be95e0848c42   7 days ago     466MB
nginx             latest    53a18edff809   7 weeks ago    192MB

>docker run -d -p 80:80 nginx

root@ip-172-31-20-86:~# docker run -d -p 80:80 nginx
3d1a52d091b05878e079b89002aa57b460c5263a585a8add0ecc671608d1f999

>docker ps

root@ip-172-31-20-86:~# docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS         PORTS                                 NAMES
3d1a52d091b0   nginx     "/docker-entrypoint.…"   3 seconds ago   Up 3 seconds   0.0.0.0:80->80/tcp, [::]:80->80/tcp   thirsty_shaw

>docker exec -it 3d1a52d091b0

root@ip-172-31-20-86:~# docker exec -it 3d1a52d091b0  /bin/bash
docker: 'docker exec' requires at least 2 arguments

root@ip-172-31-20-86:~# docker exec -it 3d1a52d091b0 /bin/bash
root@3d1a52d091b0:/# hostname
3d1a52d091b0
root@3d1a52d091b0:/# hostname -i
172.17.0.3

root@5336d949f33b:/# ls
bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@5336d949f33b:/# cd opt/
root@5336d949f33b:/opt# ls
root@5336d949f33b:/opt# cd ..
root@5336d949f33b:/# ls
bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@5336d949f33b:/# cd usr/
root@5336d949f33b:/usr# ls
bin  games  include  lib  lib64  libexec  local  sbin  share  src
root@5336d949f33b:/usr# cd lib
root@5336d949f33b:/usr/lib# ls
apt  dpkg  init  locale  lsb  mime  nginx  os-release  sasl2  ssl  systemd  terminfo  tmpfiles.d  udev  x86_64-linux-gnu
root@5336d949f33b:/usr/lib#
root@5336d949f33b:/usr/lib# docker images
bash: docker: command not found
root@5336d949f33b:/usr/lib# docker imagesexit
bash: docker: command not found
root@5336d949f33b:/usr/lib# read escape sequence
root@ip-172-31-20-86:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   latest    be95e0848c42   7 days ago     466MB
nginx             latest    53a18edff809   7 weeks ago    192MB
ubuntu            latest    a04dc4851cbc   2 months ago   78.1MB
hello-world       latest    74cc54e27dc4   2 months ago   10.1kB
root@ip-172-31-20-86:~# docekr runRead from remote host ec2-34-204-17-141.compute-1.amazonaws.com: Connection reset by peer
Connection to ec2-34-204-17-141.compute-1.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer

we can see below nginx web page and nginx is running on containers

![image](https://github.com/user-attachments/assets/878995bc-58b1-4f20-982e-2d60f105891d)



Lab Practice::
====================


root@ip-172-31-39-182:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
root@ip-172-31-39-182:~# docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21
aca7ec14bfc5f057f73dc4cf294e920a63712bbd5f838b5205e5e00faa542318
root@ip-172-31-39-182:~# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 seconds ago   Up 6 seconds   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:~# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   43 seconds ago   Up 43 seconds   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:~# java --version
Command 'java' not found, but can be installed with:
apt install default-jre              # version 2:1.17-75, or
apt install openjdk-17-jre-headless  # version 17.0.14+7-1~24.04
apt install openjdk-21-jre-headless  # version 21.0.6+7-1~24.04.1
apt install openjdk-19-jre-headless  # version 19.0.2+7-4
apt install openjdk-20-jre-headless  # version 20.0.2+9-1
apt install openjdk-22-jre-headless  # version 22~22ea-1
apt install openjdk-11-jre-headless  # version 11.0.26+4-1ubuntu1~24.04
apt install openjdk-8-jre-headless   # version 8u442-b06~us1-0ubuntu1~24.04
root@ip-172-31-39-182:~# docker exec -it aca7ec14bfc5 /bin/bash
jenkins@aca7ec14bfc5:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@aca7ec14bfc5:/$ sudo apt update
bash: sudo: command not found
jenkins@aca7ec14bfc5:/$ hostname
aca7ec14bfc5
jenkins@aca7ec14bfc5:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@aca7ec14bfc5:/$ cd /var/lib/
jenkins@aca7ec14bfc5:/var/lib$ ls
apt  dpkg  git  misc  pam  shells.state  systemd
jenkins@aca7ec14bfc5:/var/lib$ exit
exit
root@ip-172-31-39-182:~# cd /var/lib/
root@ip-172-31-39-182:/var/lib# ls
PackageKit  command-not-found  grub           os-prober     shim-signed              ucf
amazon      containerd         hibinit-agent  pam           snapd                    udisks2
app-info    dbus               ieee-data      plymouth      sudo                     unattended-upgrades
apport      dhcpcd             landscape      polkit-1      swcatalog                update-manager
apt         docker             libuuid        private       systemd                  update-notifier
boltd       dpkg               logrotate      python        tpm                      usb_modeswitch
chrony      fwupd              man-db         sgml-base     ubuntu-advantage         vim
cloud       git                misc           shells.state  ubuntu-release-upgrader  xml-core
root@ip-172-31-39-182:/var/lib# cd ..
root@ip-172-31-39-182:/var# cd ..
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 minutes ago   Up 7 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:/# docker exec -it aca7ec14bfc5 /bin/bash
jenkins@aca7ec14bfc5:/$ cd /var/jenkins_home/secret
bash: cd: /var/jenkins_home/secret: No such file or directory
jenkins@aca7ec14bfc5:/$ ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
jenkins@aca7ec14bfc5:/$ cd secrets
bash: cd: secrets: No such file or directory
jenkins@aca7ec14bfc5:/$ cd ..
jenkins@aca7ec14bfc5:/$ ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
jenkins@aca7ec14bfc5:/$ pwd
/
jenkins@aca7ec14bfc5:/$ cd /var/jenkins_home/
jenkins@aca7ec14bfc5:~$ ls
config.xml                     jenkins.telemetry.Correlator.xml  plugins                   secrets      users
copy_reference_file.log        jobs                              secret.key                updates      war
hudson.model.UpdateCenter.xml  nodeMonitors.xml                  secret.key.not-so-secret  userContent
jenkins@aca7ec14bfc5:~$ cd secrets
jenkins@aca7ec14bfc5:~/secrets$ ls
initialAdminPassword  jenkins.model.Jenkins.crumbSalt  master.key
jenkins@aca7ec14bfc5:~/secrets$ cat initialAdminPassword
3268b754fc93442e9ea3cf22c40fcc8e
jenkins@aca7ec14bfc5:~/secrets$ read escape sequence
root@ip-172-31-39-182:/# docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21
1b6159a409c358d5a2db6ecc34b13cf29e8f1d94ca249722a47424d02a8d6bc1
docker: Error response from daemon: failed to set up container networking: driver failed programming external connectivity on endpoint unruffled_pare (f76e7f84de1872354f3caf9f2c4d2ee9bf83c468178a614d407f1c5d35df00f3): Bind for 0.0.0.0:5000 failed: port is already allocated

Run 'docker run --help' for more information
root@ip-172-31-39-182:/# docker run -d -p 8081:8081 -p 5001:5001 jenkins/jenkins:jdk21
601ef30a9a97b2ef1ab13a6956d603edbc23cd2d2717cb4d2db41f4b88e148ae
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   8 seconds ago    Up 8 seconds    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS              PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   2 minutes ago    Up About a minute   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   14 minutes ago   Up 14 minutes       0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   3 minutes ago    Up 3 minutes    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   16 minutes ago   Up 16 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker exec -it 601ef30a9a97 /bin/bash
jenkins@601ef30a9a97:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@601ef30a9a97:/$ cd /var/jenkins_home/
jenkins@601ef30a9a97:~$ ls
config.xml                     jenkins.telemetry.Correlator.xml  plugins                   secrets      users
copy_reference_file.log        jobs                              secret.key                updates      war
hudson.model.UpdateCenter.xml  nodeMonitors.xml                  secret.key.not-so-secret  userContent
jenkins@601ef30a9a97:~$
jenkins@601ef30a9a97:~$ exit
exit
root@ip-172-31-39-182:/# docker run -d -p 8585:8585 jenkins/jenkins:jdk21
bc684af40e16b2c7eb91de87e952ec7a1ae0bab608bc9d0e17bad723ce853d69
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 seconds ago    Up 7 seconds    8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 minutes ago    Up 7 minutes    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 jenkins/jenkins:jdk21
a800fb0e6d7cd81cefdb33b1ded7019c478fbd8ebd232498c99316a092b92660
root@ip-172-31-39-182:/# docker psdock
docker: unknown command: docker psdock

Run 'docker --help' for more information
root@ip-172-31-39-182:/#
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED              STATUS              PORTS                                                                                                           NAMES
a800fb0e6d7c   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   About a minute ago   Up About a minute   8080/tcp, 0.0.0.0:80->80/tcp, [::]:80->80/tcp, 50000/tcp                                                        romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   2 minutes ago        Up 2 minutes        8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   9 minutes ago        Up 9 minutes        0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   22 minutes ago       Up 22 minutes       0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker pull srinfotech
Using default tag: latest
Error response from daemon: pull access denied for srinfotech, repository does not exist or may require 'docker login': denied: requested access to the resource is denied
root@ip-172-31-39-182:/# docker pull nginx
Using default tag: latest
latest: Pulling from library/nginx
dad67da3f26b: Pull complete
4eb3a9835b30: Pull complete
021db26e13de: Pull complete
397cc88dcd41: Pull complete
5f4a88bd8474: Pull complete
66467f827546: Pull complete
f05e87039331: Pull complete
Digest: sha256:dc53c8f25a10f9109190ed5b59bda2d707a3bde0e45857ce9e1efaa32ff9cbc1
Status: Downloaded newer image for nginx:latest
docker.io/library/nginx:latest
root@ip-172-31-39-182:/# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
nginx             latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker run -d -p 80:80 nginx:latest
78f28d3d450fa094d496e22de149de21141ffd1e884772251922121a7b40422d
docker: Error response from daemon: failed to set up container networking: driver failed programming external connectivity on endpoint interesting_mclaren (f76b2b0d8ace4755840ce6f55c5da9f57bfed6e0f29dd8a41991b31217fc3f6a): Bind for 0.0.0.0:80 failed: port is already allocated

Run 'docker run --help' for more information
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
a800fb0e6d7c   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   10 minutes ago   Up 10 minutes   8080/tcp, 0.0.0.0:80->80/tcp, [::]:80->80/tcp, 50000/tcp                                                        romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   11 minutes ago   Up 11 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   18 minutes ago   Up 18 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop a800fb0e6d7c
a800fb0e6d7c
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 nginx:latest
585b90814ed4871098000ddaf38376502a490bc2f38bfe625d47a3ddd7f0c85f
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
585b90814ed4   nginx:latest            "/docker-entrypoint.…"   9 seconds ago    Up 9 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             festive_euler
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   32 minutes ago   Up 32 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
nginx             latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/SrInfotechnginx:latest
Error parsing reference: "srinfotech7358/SrInfotechnginx:latest" is not a valid repository/tag: invalid reference format: repository name (srinfotech7358/SrInfotechnginx) must be lowercase
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/srinfotechnginx:latest
root@ip-172-31-39-182:/# docker images
REPOSITORY                       TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins                  jdk21     52e1941f479f   21 hours ago   471MB
nginx                            latest    9a9a9fd723f1   2 days ago     192MB
srinfotech7358/srinfotechnginx   latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker login -u srinfotech7358

i Info → A Personal Access Token (PAT) can be used instead.
         To create a PAT, visit https://app.docker.com/settings


Password:

WARNING! Your credentials are stored unencrypted in '/root/.docker/config.json'.
Configure a credential helper to remove this warning. See
https://docs.docker.com/go/credential-store/

Login Succeeded
root@ip-172-31-39-182:/# docker push srinfotech7358/srinfotechnginx
Using default tag: latest
The push refers to repository [docker.io/srinfotech7358/srinfotechnginx]
cd38dca3d982: Mounted from library/nginx
d35594dd7e6d: Mounted from library/nginx
126eaee18409: Mounted from library/nginx
6380429cac56: Mounted from library/nginx
13fcb2d303e8: Mounted from library/nginx
151f9feea563: Mounted from library/nginx
7fb72a7d1a8e: Mounted from library/nginx
latest: digest: sha256:3004321c732af3becb9dc247f5e8926faba9186aa67960e15767996abcec588b size: 1778
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
585b90814ed4   nginx:latest            "/docker-entrypoint.…"   10 minutes ago   Up 10 minutes   0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             festive_euler
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   22 minutes ago   Up 22 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   29 minutes ago   Up 29 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 585b90814ed4
585b90814ed4
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   23 minutes ago   Up 23 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   30 minutes ago   Up 30 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 srinfotech7358/srinfotechnginx:latest
9f5173c50d14631bd31c8270f79a45db441e8c66db5b730dbb7197de65594c20
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   9 seconds ago    Up 8 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             vibrant_dewdney
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   24 minutes ago   Up 24 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   43 minutes ago   Up 43 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   25 minutes ago   Up 25 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   32 minutes ago   Up 32 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   44 minutes ago   Up 44 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps -a
CONTAINER ID   IMAGE                                   COMMAND                  CREATED              STATUS                        PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   About a minute ago   Exited (137) 27 seconds ago                                                                                                                   vibrant_dewdney
585b90814ed4   nginx:latest                            "/docker-entrypoint.…"   12 minutes ago       Exited (0) 2 minutes ago                                                                                                                      festive_euler
78f28d3d450f   nginx:latest                            "/docker-entrypoint.…"   13 minutes ago       Created                                                                                                                                       interesting_mclaren
a800fb0e6d7c   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   23 minutes ago       Exited (143) 13 minutes ago                                                                                                                   romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   25 minutes ago       Up 25 minutes                 8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   32 minutes ago       Up 32 minutes                 0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
1b6159a409c3   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   33 minutes ago       Created                                                                                                                                       unruffled_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   44 minutes ago       Up 44 minutes                 0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker start 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# Read from remote host ec2-35-155-150-89.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-35-155-150-89.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer


Usefull commands:
===============

>docker --version

>docker info

>docker pull <imagename>

>docker pull ubuntu =docker pull ubuntu:latest

>docker images

>docker run -d ubuntu

>docker ps -aq

>docker rmi <imagenname>

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>docker exec -it aca7ec14bfc5 /bin/bash     --->inside the container comamnd

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>ctrl+pq or exit

>docker image tag nginx srinfotech7358/srinfotechnginx:latest


Class Note::
=============

Docker Introduction::

--docker is a open source contaniraztion platform
--application level virtulazition platform docker is best choice 
--lightweight platform
--

container:: insolated area of running your application

images:: image is package with all the dependencies and the necessary information to 
create the contaienrs

if you build a docker containers for your application called containarization

who created the containers?

images are created by containarization

Docker registry::

storage area of images called docker registry

default registry---docker hub

>docker images

>docker pull <imagename>:tagname
>docker pull jenkins/jenkins:jdk21
>docker run -d -p 8080:8080 jenkins/jenkins:jdk21
>docker exec -it 1cd47478b564 /bin/bash     ----> this cpommand is used to go inside the contaienr

>docker run -d -p 9090:9090 jenkins/jenkins:jdk21

>docker stop <containerID>
>docker stop 6cd503941b8a
>docker rmi <imagename>
>docker rmi hello-world -f
>docker run -d -p 80:80 nginx:latest

>docker login -u srinfotechbatch2

>docker image tag <imagename> <userofdockerhub/imagenametagname:imagetagname>

>docker image tag jenkins/jenkins srinfotechbatch2/srinfotechjenkins:latest
>docker tag nginx srinfotechbatch2/nginxapp:latest
>docker push srinfotechbatch2/nginxapp
>docker run -d -p 80:80 srinfotechbatch2/nginxapp:latest



18/09/2025::
==============

Dockerfile Introduction::
=================

A Dockerfile is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container.

dockerfile is a text file, and it have set up of all instructiuons

https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/


Dockerfile::dockerfile is text file, and it have set up of all instructiuons

FROM nginx or ubuntu or 

LABEL "AUthor =nagaraju@gamil.com"

RUN apt update && apt-get install jenkins -y

COPY . .  ----src destnations

ADD  . . -----src destinatuion

CMD ["echo",".jar"]

ENTRYPOINT ["echo", "war"]

EXPOSE 8080,8085

ENV APP_HOME ="Ifocus SOlutions pvt ltd"

WORKDIR $APP_HOME /app

VOLUME 

Key Components of a Dockerfile:
==========================

FROM: Specifies the base image for the Docker image you're creating.

FROM ubuntu:20.04

RUN: Executes commands inside the container, often used to install dependencies.

RUN apt-get update && apt-get install -y python3

COPY or ADD: Copies files from your local machine into the container.

COPY . /app

WORKDIR: Sets the working directory for any subsequent commands in the Dockerfile.


WORKDIR /app

CMD: Specifies the command to run when a container is started from the image.

CMD ["python3", "app.py"]

EXPOSE: Defines the network ports the container will listen on at runtime.

EXPOSE 8080

ENV: Sets environment variables inside the container.
ENV APP_ENV=production
CMD & ENTRPOINT can be executed starting of the container

CMD & ENTRYPOINT Different::
===========================
--use CMD you can change the value but ENTRYPOINT not possible to change the value at the starting of the container
--CMD you can change the argument value 
--ENTRYPOINT can’t change the argument value

CMD ["echo",".jar"]
ENTRYPOINT ["echo", "war"]

CMD/ENTRYPOINT ====should have something which runs till your app is alive

Note::
=======
life time of your container -->time which your cmd/entrypont is alive


Example Dockerfile:::
====================

Here’s a simple Dockerfile example that builds a nodejs web app:

>root@ip-172-31-18-253:~# sudo vi Dockerfile


# Use an official Node.js runtime as a base image
FROM node:18

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .

RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 3000
EXPOSE 3000

# Run the application
CMD ["node", "index.js"]


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c1edbe8-fbb3-43bf-bc35-571bd1d92180" />


Example package.json
=======================

root@ip-172-31-18-253:~# sudo vi package.json


{
  "name": "my-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "dependencies": {
    "express": "^4.18.2"
  }
}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/83c6cdd5-3141-4b8c-bec8-0d06bd1a83e4" />


Example index.js
==================

root@ip-172-31-18-253:~# sudo vi index.js


const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('Hello from Docker!');
});

app.listen(port, () => {
  console.log(`App running at http://localhost:${port}`);
});



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5902a90a-0eba-4646-8f19-67db7d073fb3" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63bb34d1-774d-48e0-9848-67215348c430" />


Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

Build the Docker image:
==========================

root@ip-172-31-18-253:~# docker build -t srinfotechnodejs .

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcc12017-f3e4-437a-be2b-5015105f163d" />

root@ip-172-31-18-253:~# docker images
REPOSITORY         TAG       IMAGE ID       CREATED         SIZE
srinfotechnodejs   latest    90e50223164e   7 seconds ago   1.13GB
root@ip-172-31-18-253:~#

Create & Run the container:
=============================

>docker run -d -p 80:80 srinfotechnodejs:latest

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c1995df6-1cec-42cf-9b54-39c4a8ed966e" />



root@ip-172-31-18-253:~# docker run -d -p 3000:3000 srinfotechnodejs:latest

04ab1eb49a96ad9ecc7b4d84eebf0462c05dd97db02f50d5436796427dc010cf

root@ip-172-31-18-253:~#


root@ip-172-31-18-253:~# docker ps
CONTAINER ID   IMAGE                     COMMAND                  CREATED              STATUS              PORTS                                         NAMES
82bf288b2a2d   srinfotechnodejs:latest   "docker-entrypoint.s…"   About a minute ago   Up About a minute   0.0.0.0:3000->3000/tcp, [::]:3000->3000/tcp   distracted_jemison
root@ip-172-31-18-253:~#


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a4b5f3d8-313d-4203-9d81-d42c5b752f61" />


Clone the Spring-micro service Project::
=========================================

>git clone https://github.com/srinfotechbatch3/spring-ms.git

root@ip-172-31-18-253:~# git clone https://github.com/srinfotechbatch3/spring-ms.git
Cloning into 'spring-ms'...
remote: Enumerating objects: 266, done.
remote: Counting objects: 100% (169/169), done.
remote: Compressing objects: 100% (91/91), done.
remote: Total 266 (delta 55), reused 103 (delta 31), pack-reused 97 (from 1)
Receiving objects: 100% (266/266), 29.17 MiB | 38.34 MiB/s, done.
Resolving deltas: 100% (84/84), done.
root@ip-172-31-18-253:~#


A **Dockerfile** is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container. Essentially, it's the blueprint for creating Docker images.

### Key Components of a Dockerfile:
1. **FROM**: Specifies the base image for the Docker image you're creating.
   ```dockerfile
   FROM ubuntu:20.04
   ```

2. **RUN**: Executes commands inside the container, often used to install dependencies.
   ```dockerfile
   RUN apt-get update && apt-get install -y python3
   ```

3. **COPY** or **ADD**: Copies files from your local machine into the container.
   ```dockerfile
   COPY . /app
   ```

4. **WORKDIR**: Sets the working directory for any subsequent commands in the Dockerfile.
   ```dockerfile
   WORKDIR /app
   ```

5. **CMD**: Specifies the command to run when a container is started from the image.
   ```dockerfile
   CMD ["python3", "app.py"]
   ```

6. **EXPOSE**: Defines the network ports the container will listen on at runtime.
   ```dockerfile
   EXPOSE 8080
   ```

7. **ENV**: Sets environment variables inside the container.
   ```dockerfile
   ENV APP_ENV=production
   ```

### Example Dockerfile
Here’s a simple Dockerfile example that builds a Python web app:

```dockerfile
# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install the required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port the app runs on
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]
```

### Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

1. **Build the Docker image**:
   ```bash
   docker build -t my-python-app .
   ```

2. **Run the container**:
   ```bash
   docker run -p 5000:5000 my-python-app
   ```

The Dockerfile streamlines the process of creating consistent and reproducible environments, making it easier to deploy applications across different systems.


Please try Below Example on Docker file:
============================================

https://docs.docker.com/get-started/workshop/02_our_app/


Spring Micro Services Aplication::
=======================

https://github.com/srinfotech7358/spring-ms.git

LAB Practice::
==============

root@ip-172-31-32-42:~# git clone https://github.com/srinfotech7358/spring-ms.git
Cloning into 'spring-ms'...
remote: Enumerating objects: 242, done.
remote: Counting objects: 100% (145/145), done.
remote: Compressing objects: 100% (78/78), done.
remote: Total 242 (delta 47), reused 103 (delta 31), pack-reused 97 (from 1)
Receiving objects: 100% (242/242), 29.16 MiB | 3.85 MiB/s, done.
Resolving deltas: 100% (76/76), done.
root@ip-172-31-32-42:~# ls
getting-started-app  snap  spring-ms
root@ip-172-31-32-42:~# cd spring-ms/
root@ip-172-31-32-42:~/spring-ms# ls
Dockerfile  azure-pipeline.yml  azure-pipelines.yml  deploy.yaml  pom.xml  src
root@ip-172-31-32-42:~/spring-ms# sudo vi Dockerfile
root@ip-172-31-32-42:~/spring-ms# docker build -t srinfotech .
[+] Building 43.6s (12/12) FINISHED                                    docker:default
 => [internal] load build definition from Dockerfile                             0.0s
 => => transferring dockerfile: 256B                                             0.0s
 => WARN: FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)   0.0s
 => [internal] load metadata for registry.access.redhat.com/ubi8/openjdk-11:lat  0.9s
 => [internal] load metadata for docker.io/library/maven:3.6.3-jdk-11            1.0s
 => [auth] library/maven:pull token for registry-1.docker.io                     0.0s
 => [internal] load .dockerignore                                                0.0s
 => => transferring context: 2B                                                  0.0s
 => [internal] load build context                                                0.3s
 => => transferring context: 30.64MB                                             0.3s
 => [stage-1 1/2] FROM registry.access.redhat.com/ubi8/openjdk-11:latest@sha25  25.4s
 => => resolve registry.access.redhat.com/ubi8/openjdk-11:latest@sha256:28b35ee  0.0s
 => => sha256:28b35eea470174a39befd8eb9250a3276b79a4f6e7dac7872 1.47kB / 1.47kB  0.0s
 => => sha256:8be99c30a4e5b021129310847bddca64a93fb38b0c8dfeac482b4 596B / 596B  0.0s
 => => sha256:0c46377f1021ce6db9f2457907fe43fd1001b2ecc1ae2ac 30.70kB / 30.70kB  0.0s
 => => sha256:e0348fdb2685077d22116d294a90a253709aba78815882a 39.49MB / 39.49MB  2.6s
 => => sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59 113.69MB / 113.69MB  18.7s
 => => extracting sha256:e0348fdb2685077d22116d294a90a253709aba78815882a57fcc53  2.7s
 => => extracting sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59ffa6acb6f2  6.4s
 => [stage1 1/3] FROM docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2  16.5s
 => => resolve docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2a5e64f7d  0.0s
 => => sha256:1801d353e27e68d60355b371ddfd2ed8d06204bc3266f1746 2.42kB / 2.42kB  0.0s
 => => sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd 50.43MB / 50.43MB  1.0s
 => => sha256:1d29ccf46ef2a5e64f7de3d79a63f9bcffb4dc56be0ae3daed5ca 549B / 549B  0.0s
 => => sha256:e23b595c92ada5c9f20a27d547ed980a445f644eb1cbde7cf 8.93kB / 8.93kB  0.0s
 => => extracting sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd0909bb3  3.6s
 => => sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01 7.83MB / 7.83MB  1.4s
 => => sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b 10.00MB / 10.00MB  1.7s
 => => sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59 51.84MB / 51.84MB  3.1s
 => => sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac15 5.29MB / 5.29MB  2.8s
 => => sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d774 213B / 213B  3.1s
 => => sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede046 9.58MB / 9.58MB  3.7s
 => => sha256:355e8215390faee903502a9fddfc65cd823f1606f0533 202.81MB / 202.81MB  6.8s
 => => sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c1 855B / 855B  4.1s
 => => sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5fed 363B / 363B  4.3s
 => => extracting sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01b0ec2  0.6s
 => => extracting sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b7228293  0.3s
 => => extracting sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59d332f18  2.9s
 => => extracting sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac1506121  0.2s
 => => extracting sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d7740  0.0s
 => => extracting sha256:355e8215390faee903502a9fddfc65cd823f1606f053376ba2575a  3.0s
 => => extracting sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede0464c293  0.2s
 => => extracting sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c15  0.0s
 => => extracting sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5feda  0.0s
 => [stage1 2/3] COPY . .                                                        1.2s
 => [stage1 3/3] RUN mvn clean package                                          24.0s
 => [stage-1 2/2] COPY --from=stage1 target/*.jar app.jar                        0.1s
 => exporting to image                                                           0.1s
 => => exporting layers                                                          0.1s
 => => writing image sha256:a1aa2587a6a74ca2d5e113d039a0c5198d12f54919056285ec3  0.0s
 => => naming to docker.io/library/srinfotech                                    0.0s

 1 warning found (use docker --debug to expand):
 - FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)
root@ip-172-31-32-42:~/spring-ms# docker images
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
srinfotech   latest    a1aa2587a6a7   17 seconds ago   410MB
test         latest    944581c42756   7 minutes ago    166MB
root@ip-172-31-32-42:~/spring-ms# docker run -d -p 8080:8080 srinfotech:latest
eb3d6d70bc9e049db0255b30f406b9559f7b03d1e82862d59205f363e1b8087e
root@ip-172-31-32-42:~/spring-ms# docker ps
CONTAINER ID   IMAGE               COMMAND               CREATED         STATUS         PORTS                                                             NAMES
eb3d6d70bc9e   srinfotech:latest   "java -jar app.jar"   6 seconds ago   Up 5 seconds   8443/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 8778/tcp   fervent_bassi
root@ip-172-31-32-42:~/spring-ms# Read from remote host ec2-34-222-12-103.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-34-222-12-103.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer



Application up & running::
=============================

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03d89434-a183-4a0e-8733-2f1dc4d65cef" />

