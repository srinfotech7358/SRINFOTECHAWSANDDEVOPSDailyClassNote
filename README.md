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


