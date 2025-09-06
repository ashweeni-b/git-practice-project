## 03-Undoing-Changes

This folder covers <b> fixing mistakes in Git </b>. Undoing changes is critical skill every developer must master.

## Commands practiced

- `git reset --soft HEAD~1` - Undo last commit, keep changes staged
- `git reset --mixed HEAD~1` - Undo last commit, keep changes in working directory (unstaged)
- `git reset --hard HEAD~1` - Undo last commit and discard changes completely
- `git revert <commit_hash>` - Safely revert a commit by creating a new commit
- `git checkout HEAD -- <file>` - Discard changes in a file
- `git clean -fd` - Remove untracked files/folders

## Tasks and Output:

<ol>
<li> Check status and history </li> <br> 
<img alt="Checked history and status" src="/03-undoing-changes/screenshots/checked history and status before creating demo.txt.png"> <br> <br>

<li> Create demo.txt file </li> <br> 
<img alt="Created demo.txt" src="/03-undoing-changes/screenshots/created demo.txt file.png"> <br> <br>

<li> Stage and commit demo.txt file </li> <br> 
<img alt="Staged and committed demo.txt" src="/03-undoing-changes/screenshots/staged and commited demo.txt file.png"> <br> <br>

<li> View commit history </li> <br> 
<img alt="Checked commit history" src="/03-undoing-changes/screenshots/checked commit history.png"> <br> <br>

<li> Modify demo.txt by adding a new line </li> <br> 
<img alt="Modified demo.txt" src="/03-undoing-changes/screenshots/modified demo.txt file.png"> <br> <br>

<li> Stage and commit demo.txt file after modification </li> <br> 
<img alt="Staged demo.txt" src="/03-undoing-changes/screenshots/added modified demo.txt file.png"> <br>
<img alt="Committed demo.txt" src="/03-undoing-changes/screenshots/committed modified demo.txt.png"> <br> <br>

<li> Check commit history and status after committing </li> <br> 
<img alt="Checked status before undoing" src="/03-undoing-changes/screenshots/checked status after modifying demo.txt.png"> <br> <br>

<li> Undo the commit by using git reset --soft and check the status</li> <br> 
<img alt="Undo the commit and checked status" src="/03-undoing-changes/screenshots/undo using git reset soft.png"> <br> <br>

<li> Commit the changes after resetting with soft flag </li> <br> 
<img alt="Committed changes after resetting using soft" src="/03-undoing-changes/screenshots/committed changes after git reset soft.png"> <br> <br>

<li> Check commit history and status before undo mixed </li> <br> 
<img alt="Checked status before git reset mixed" src="/03-undoing-changes/screenshots/checked commit history and status before git reset mixed.png"> <br> <br>

<li> Undo the changes by using git reset --mixed </li> <br> 
<img alt="Undo changes using git reset mixed" src="/03-undoing-changes/screenshots/undo changes using git reset mixed.png"> <br> <br>

<li> Check commit history and status after undo mixed </li> <br> 
<img alt="Checked status after git reset mixed" src="/03-undoing-changes/screenshots/checked status after git reset mixed.png"> <br> <br>

<li> Commit the changes after resetting with mixed flag </li> <br> 
<img alt="Committed changes after resetting using mixed" src="/03-undoing-changes/screenshots/committed changes after git reset mixed.png"> <br> <br>

<li> Undo the changes by using git reset --hard </li> <br> 
<img alt="Undo changes using git reset hard" src="/03-undoing-changes/screenshots/undo using git reset hard.png"> <br> <br>

<li> Check commit history and status after undo hard </li> <br> 
<img alt="Checked status after git reset hard" src="/03-undoing-changes/screenshots/checked status after git reset hard.png"> <br> <br>

<li> Modify demo.txt to add a new line </li> <br> 
<img alt="Modified demo.txt" src="/03-undoing-changes/screenshots/modified demo.txt with a new line.png"> <br> <br>

<li> Stage and commit the modifications </li> <br> 
<img alt="Staged and committed the modifications" src="/03-undoing-changes/screenshots/staged and committed the modifications.png"> <br> <br>

<li> Revert the modifications done </li> <br> 
<img alt="Reverted the modifications" src="/03-undoing-changes/screenshots/revertted the modifications.png"> <br> <br>

<li> Check commit history after reverting the modifications </li> <br> 
<img alt="Checked history after reverting the modifications" src="/03-undoing-changes/screenshots/checked the history after reverting.png"> <br> <br>

<li> Create a new file temp.txt </li> <br> 
<img alt="Created temp.txt" src="/03-undoing-changes/screenshots/created temp.txt.png"> <br> <br>

<li> Stage and commit the changes </li> <br> 
<img alt="Staged and committed temp.txt" src="/03-undoing-changes/screenshots/added and committed temp.txt.png"> <br> <br>

<li> Modify the temp.txt by adding new line and check the status </li> <br> 
<img alt="Modified and checked status" src="/03-undoing-changes/screenshots/modify and check status.png"> <br> <br>

<li> Discard the modifications by using git checkout and check the status </li> <br> 
<img alt="Discarded the modifications and checked status" src="/03-undoing-changes/screenshots/git checkout and status.png"> <br> <br>

<li> Again modify temp.txt by adding new line and check the status </li> <br> 
<img alt="Modified again and checked status" src="/03-undoing-changes/screenshots/again modify and check status.png"> <br> <br>

<li> Discard the modifications by using git restore and check the status </li> <br> 
<img alt="Discarded and check status" src="/03-undoing-changes/screenshots/git restore and status.png"> <br> <br>

<br>

<li> Setup untracked files and folders and check the directory </li> <br> 
<img alt="Setup the files and folders" src="/03-undoing-changes/screenshots/setup the clear directory.png"> <br> <br>

<li> Clean untracked files and folders and check the directory </li> <br> 
<img alt="Cleaned untracked files" src="/03-undoing-changes/screenshots/clear untracked files and check the directoy.png"> <br> <br>

</ol>
