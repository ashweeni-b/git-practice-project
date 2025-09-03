## 05-Branching-Merging

This folder contains practice for working with branches and merging in Git.

## Commands practiced

- `git branch <name>` - Creates a branch
- `git branch` - Lists the branches
- `git checkout <name>` OR `git switch <name>` - Switches the branches
- `git checkout -b <name>` - Creates and switches the branch simultaneously
- `git merge <branch>` - Merges the branch into current branch
- `git merge --abord` - Cancels the merge
- `git branch -D <name>` - Deletes the branch locally
- `git push origin --delete <name>` - Delete the branch remotely
- `git rebase main` - Rebase branch onto main

## Tasks and Output:

<ol>
<li> Create feature-1 branch and switch to it </li>
![Created feature-1 branch](<created feature-1 branch.png>)

<br>

<li> Create a file name feature1.txt  </li>
![Created feature1.txt](<created feature1.txt.png>)

<br>

<li> Add feature1.txt and commit it </li>
![Committed feature1.txt](<added feature1.txt and committed it.png>)

<br>

<li> Switch to the main branch </li>
![Switch to main branch](<switched to main branch.png>)

<br>

<li> Merge the feature and the main branch </li>
![Merged feature-1 branch](<merged feature-1 branch.png>)

<br>

<li> Check commit history after merging </li>
![Commit history after merging](<commit history after merging.png>)

<br>

<li> Delete feature-1 branch and check the branches </li>
![Deleted feature-1 branch](<deleted feature-1 branch.png>)

<br>

<li> Create feature-2 branch </li>
![Created feature-2 branch](<created feature-2 branch.png>)

<br>

<li> Create a file name feature2.txt </li>
![Created feature2.txt](<created feature2.txt.png>)

<br>

<li> Add feature2.txt and commit it </li>
![Committed feature2.txt](<added and committed feature2.txt.png>)

<br>

<li> Rebase the branches and check commit history </li>
![Rebased the branches](<rebased with main.png>)

<br>

<li> Create feature-3 branch </li>
![Created feature-3 branch](<created feature-3 branch.png>)

<br>

<li> Create a file name conflict.txt </li>
![Created conflict.txt](<created conflict.txt.png>)

<br>

<li> Add conflict.txt and commit it </li>
![Committed conflict.txt](<added and committed conflict.txt.png>)
![Viewed commit history](<commit history after committing conflict.txt.png>)

<br>

<li> Switch to the main branch </li>
![Switched to main branch](<switch to main branch from feature-3.png>)

<br>

<li> Add conflicting line to conflict.txt through main branch </li>
![Added line to conflict.txt](<added line from main branch to conflict.txt.png>)

<br>

<li> Add conflict.txt and commit it through main branch </li>
![Committed conflict.txt](<committed conflict.txt.png>)
![Commit history after modifying conflict.txt from main](<commit history after modifying conflict.txt from main.png>)

<br>

<li> Merge the feature-3 branch with main branch </li>
![Merged the branches](<merged feature-3 with main.png>)
![Merge conflict error arised](<merge conflict error.png>)
![Resolved the conflict](<resolved conflict.png>)
![Repo status after resolving the conflict](<status after resolving conflict.png>)
![Added and committed the conflicts](<added and committed the reolved conflict.png>)

<br>