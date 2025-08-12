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


