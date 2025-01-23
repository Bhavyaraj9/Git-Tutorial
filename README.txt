1. git init -> Powers your folder to be managed by git , and intialises a new empty repository.
                It also creates a .git folder that has all the relevant logic to manage versions of your project.

2. Working area -> There can be a bunch of files that are not currently handled by git.
                It means that changes done or to be done in those files are not managed by git yet.
                A file which is in working area is considered to be not in the staging area. When 
                we do `git status` and we see abunch if 'untracked files' then these are actually called to be in the working area.

3. Staging area -> What all files are going to be part of the next version that we will create.
                   This staging area is a place where git know what changes will be done from the last version to latest version.

4. Repository area -> This area contains the details of all your previous registered version.
                      And the files in this area, git already manages them and know their version history.

5. 'git add <file> -> move files from working area to staging area.

6. git rm --cached <file> -> move files back from staging to working area.

7. Commit -> commit is a particular version of the project. It captures a snapshot of the project staged changes and creates a version out of it.

8. git commit -> registers staging changes to commit.

9. git log -> list down all the commits of the repository.If you want to exit out of git log prompt
             press `q`.

10.  git restore <file> -> It removes all files changes from the staging area to be commited. This can be useful if we did some dirty piece of code 
                          and no more want it. Instead of deleting every change line by line, we can restore it or you can say restore last clean version of the file.

11. git restore --staged <filename> -> It removes file from changes from staging area to working area.                  
                           
12.              