# who am i ?? 
 > Hamza Rashed Syrian from Daraa . I studied civil engineering in Syria, but I could not continue because of the war in Syria .. Then I left Syria and came to Jordan ..
I am now working as a full stack developer
* this is my website for more information [My Website](https://hamzarashed.herokuapp.com/)
* and this is my github account [GitHub](https://github.com/Hamza-Rashed/)

# Explore the tech!

In today's blog, I am going to talk about **Git**, a tool used by software developers. _So, let's get started!_

1. ### What is Version Control?
Simply, version control is a system that makes a log of the code files versions, and allows the developer to revisit the different versions of these files. By doing this, one can compare changes, track modifications, and revert to a previous versions. Thus, mistakes in any changed version can be andone and avoided.
There are 3 types of VS, local, centralized and distributed. One example of a distributed version control is ***Git***, that will be explained in the next section.

2. ### What is Git?
_Git_ is a distributed version control system. This meand that every time the developer saves a new version of the project (commit), _Git_ creates a snapshot of the file and stores a reference to it. There are several functionalities that _Git_ can do, some are explained as follows:
  * Local Operations: most Git operations are done locally, this allowa the developer to continue work on a project even when not online.
  * Tracking Changes: any small change done on a file, is automatically tracked and saved by _Git_.
  * Loss of Data: _Git_ handles and reverse data loss and damage than can occur on a file. 
  * States: files on _Git_ can be in 3 states, committed, modified (where file is changed but not committed to the database), and staged (which means that the file is flagged so that its changes can be committed in the next snapshot).
  
  Git can be downloaded locally on any machine running Mac OS X, Windows or Linux. Although dealing with _Git_ is usually done using the **terminal** (command line), _Git_ includes a Graphical User Interface that can be accessed by the developer.
  
  The following sections include steps for configuring and setting up _Git_ on your device. _So, let's gid depper into that!_
  
   1. ##### Initial Customization: After installing _Git_, two steps must be done, the developer inserts his **identity info**, which includes username and password. This is done using the command `git config --global user.name "name"`, `git config --global user.email "example@email.com"`.
   
   2. ##### Default Text Editor: The developer chooses his default text editor using the command `$ git config --global core.editor EditorName`.
   
   3. ##### Check Settings: One can check their settings the command `git config --list `.
   
   4. ##### Getting Help: One can ask for help using several commands: `git help command`, `git command --help` or `man git-command`.
   
   5. ##### Setting up a Git Repository:
      * Importing: 
         `$ cd test`
         `$ git init`
         `$ git add *.c`
         `$ git add LICENSE
         `$ git commit -m “any message here”
         
      * Cloning:
         `$ git clone https://github.com/test`
         
   6. ##### The Life Cycle of File Status:
   After editing a file, _Git_ flags it as **modified**. You **stage** the modified file. Then, **commit** staged changes:
   
   * Check File Status:
         `$ git status`
        
      * Tracking and Staging a New File:
         `git add filename`
         
      * Committing a File:
         `$ git commit -m “made change x,y,z”`
         
      * Committing All Changes:
         `$ git commit -a`
         
      * Pushing Changes:
         `$ git push origin master`
         
      * Stashing Changes: temporarily removes changes and hides them, giving the developer a clean working _dir_. it is done using the command `git stash`. once the developer is ready to continue working on changes, `git stash apply` is used to retrieve the hidden changes.
      
   
