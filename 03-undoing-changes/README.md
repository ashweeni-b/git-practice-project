## 03-Undoing-Changes

This folder covers <b> fixing mistakes in Git <b>. Undoing changes is critical skill every developer must master.

## Commands practiced

- `git reset --soft HEAD~1` - Undo last commit, keep changes staged
- `git reset --mixed HEAD~1` - Undo last commit, keep changes in working directory (unstaged)
- `git reset --hard HEAD~1` - Undo last commit and discard changes completely
- `git revert <commit_hash>` - Safely revert a commit by creating a new commit
- `git checkout HEAD -- <file>` - Discard changes in a file
- `git clean -fd` - Remove untracked files/folders

## Tasks and Output:

<ol>
<li> Create demo.txt file </li>
![Created demo.txt](<created demo.txt.png>)

<br>

<li> Stage and commit demo.txt file </li>
![Stage and commit demo.txt](<staged and committed demo.txt.png>)

<br>

<li> View commit history </li>
![Check commit history](<Check commit history.png>)

<br>

<li> Modify demo.txt by adding a new line </li>
![Modified demo.txt](<modified demo.txt - second version.png>)

<br>

<li> Stage and commit demo.txt file after modification </li>
![Committed demo.txt](<add and commit demo.txt.png>)

<br>

<li> Check commit history and status before committing </li>
![Check status before undoing](<checked history and status before undoing.png>)

<br>

<li> Undo the commit by using git reset --soft and check the status</li>
![Undo the changes and checked the status](<undo the change and checked history and status after undoing.png>)

<br>

<li> Commit the changes after resetting with soft flag </li>


<br>

<li> Undo the changes by using git reset --mixed </li>


<br>