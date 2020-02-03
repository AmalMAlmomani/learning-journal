
### Seeing Your Remotes:
   - git remote: view the short names, such as “origin,” of all specified remote handles.
      - git remote -v: view all the remote URLs next to their corresponding short names.
      
### Adding Remotes:
   - create a new remote Git repository with a short name, `git remote add shortname url`
   
### Fetching:
   - entails pulling data that you don’t have from a remote project, `git fetch [remote-name]`
   
### Pushing:
   - To push your changes “upstream” for sharing, `git push [remote-name][branch-name]`
   - This command pushes committed changes from your local “master” branch upstream to the “origin” server.
  
### Renaming/Removing Remotes:
   - Rename:
     -  `git remote rename`
   - Remove:
     - `git remote rm`
     
 **Reminder: “origin” is simply the default remote name when you use the git clone command.**
 
 ### Undoing Actions:
   - Commit Mistakes: when you need to alter a commit message or forgot to add some files.
     - `git commit --amend`
   - Unstaging a File:
     - `git reset HEAD` command unstaged the index.html file
   - Undo a Committed Snapshot:
     - `git revert` command, This command appends a new commit that undoes changes introduced by a specific commit. This prevents Git from losing history.
   - Unmodifying a File:
     - `git checkout` command, To have a file return to its state when you last committed.
     - **NOTE**: `git checkout -- file` erases any changes made to the file because you are copying another file over it.
