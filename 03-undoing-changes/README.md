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
<li> Check status and history </li>
![Checked history and status](<checked history and status before creating demo.txt.png>)

<br>

<li> Create demo.txt file </li>
![Created demo.txt](<created demo.txt file.png>)

<br>

<li> Stage and commit demo.txt file </li>
![Staged and committed demo.txt](<staged and commited demo.txt file.png>)

<br>

<li> View commit history </li>
![Checked commit history](<checked commit history.png>)

<br>

<li> Modify demo.txt by adding a new line </li>
![Modified demo.txt](<modified demo.txt file.png>)

<br>

<li> Stage and commit demo.txt file after modification </li>
![Staged demo.txt](<added modified demo.txt file.png>)
![Committed demo.txt](<committed modified demo.txt.png>)

<br>

<li> Check commit history and status after committing </li>
![Checked status before undoing](<checked status after modifying demo.txt.png>)

<br>

<li> Undo the commit by using git reset --soft and check the status</li>
![Undo the commit and checked status](<undo using git reset soft.png>)

<br>

<li> Commit the changes after resetting with soft flag </li>
![Committed changes after resetting using soft](<committed changes after git reset soft.png>)

<br>

<li> Check commit history and status before undo mixed </li>
![Checked status before git reset mixed](<checked commit history and status before git reset mixed.png>)

<br>

<li> Undo the changes by using git reset --mixed </li>
![Undo changes using git reset mixed](<undo changes using git reset mixed.png>)

<br>

<li> Check commit history and status after undo mixed </li>
![Checked status after git reset mixed](<checked status after git reset mixed.png>)

<br>

<li> Commit the changes after resetting with mixed flag </li>
![Committed changes after resetting using mixed](<committed changes after git reset mixed.png>)

<br>

<li> Undo the changes by using git reset --hard </li>
![Undo changes using git reset hard](<undo using git reset hard.png>)

<br>

<li> Check commit history and status after undo hard </li>
![Checked status after git reset hard](<checked status after git reset hard.png>)

<br>

<li> Modify demo.txt to add a new line </li>
![Modified demo.txt](<modified demo.txt with a new line.png>)

<br>

<li> Stage and commit the modifications </li>
![Staged and committed the modifications](<staged and committed the modifications.png>)

<br>

<li> Revert the modifications done </li>
![Reverted the modifications](<revertted the modifications.png>)

<br>

<li> Check commit history after reverting the modifications </li>
![Checked history after reverting the modifications](<checked the history after reverting.png>)

<br>

<li> Create a new file temp.txt </li>
![Created temp.txt](<created temp.txt.png>)

<br>

<li> Stage and commit the changes </li>
![Staged and committed temp.txt](<added and committed temp.txt.png>)

<br> 

<li> Modify the temp.txt by adding new line and check the status </li>
![Modified and checked status](<modify and check status.png>)

<br>

<li> Discard the modifications by using git checkout and check the status </li>
![Discarded the modifications and checked status](<git checkout and status.png>)

<br>

<li> Again modify temp.txt by adding new line and check the status </li>
![Modified again and checked status](<again modify and check status.png>)

<br>

<li> Discard the modifications by using git restore and check the status </li>
![Discarded and check status](<git restore and status.png>)

<br>

<li> Setup untracked files and folders and check the directory </li>
![Setup the files and folders](<setup the clear directory.png>)

<br>

<li> Clean untracked files and folders and check the directory </li>
![Cleaned untracked files](<clear untracked files and check the directoy.png>)

<br>