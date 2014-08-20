GitHub
======
(main source of information [here](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1))

Concepts
--------
* **Repository** ("repo"): a directory or storage space for your projects. It can be a folder on your computer or a storage space on GitHub. You can keep code files, text files, image files...
* **Version control**: conservation of "snapshots" of every point in time in the project’s history (saving is not overwriting).
* **Commit**: taking a "snapshot" of your repository at that point in time, giving you a checkpoint to which you can reevaluate or restore your project to any previous state.
* **Branch**: version that you "obtain" to work with.
* **Merge**: action that you do in order to write the changes from your branch to the "master" branch (the main directory of the project).

Comands
-------
* **git init**: initializes a new Git repository (you must be in a specific repository/directory) and you can start to send new commands.
* **git config**: sets up Git's configuration.
* **git help**: gives the list of the 21 most common commands. Writing also the name of the command (e.g.: *git help init*), it gives information about this specific command.
* **git status**: checks the status of your repository (which files are inside it, which changes still need to be committed, and which branch of the repository you’re currently working on).
* **git add**: brings new files from your directory/repository to Git’s attention, including them in Git’s "snapshots" of the repository.
* **git commit**: takes a "snapshot" of the repository (usually it goes *git commit -m "Message here."*, adding then explanatory messages).
* **git branch**: builds a new branch (or timeline of commits, changes and file additions carried out from you) with the title writed after the command (e.g.: *git branch branch_name*).
* **git checkout**: allows to "check out" a repository without being inside (navigational command), viewing the master branch (e.g.: *git checkout master_name*) or another branch (e.g.: *git checkout branch_name*).
* **git merge**: merges your changes back to the master branch, which is visible to all collaborators.
* **git push**: "pushes" the changes you commit up to the GitHub website.
* **git pull**: "pulles" the changes down from GitHub website to you local computer (obtain the most up-date version).

Configuration
-------------
1. **SignUp**: in [GitHub](https://github.com/).
2. **Install locally**: `sudo aptitude install gib`
3. **Define name**: `git config --global user.name "JoseRH"`
4. **Define email**: `git config --global user.email "used_email_address"`
5. **Add credentials**: `git config --global credential.helper cache`
6. **Define time for credentials**: `git config --global credential.helper 'cache --timeout=3600'`
 
Creating repositories
---------------------


