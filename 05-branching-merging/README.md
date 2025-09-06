## 05-Branching-Merging

This folder contains practice for working with branches and merging in Git.

## Commands practiced

- `git branch <name>` - Creates a branch
- `git branch` - Lists the branches
- `git checkout <name>` OR `git switch <name>` - Switches the branches
- `git checkout -b <name>` - Creates and switches the branch simultaneously
- `git merge <branch>` - Merges the branch into current branch
- `git branch -D <name>` - Deletes the branch locally
- `git rebase main` - Rebase branch onto main

## Tasks and Output:

<ol>
<li> Create feature-1 branch and switch to it </li> <br>
<img alt="Created feature-1 branch" src="/05-branching-merging/screenshots/created feature-1 branch.png"> <br> <br>

<li> Create a file name feature1.txt  </li> <br>
<img alt="Created feature1.txt" src="/05-branching-merging/screenshots/created feature1.txt.png"> <br> <br>

<li> Add feature1.txt and commit it </li> <br>
<img alt="Committed feature1.txt" src="/05-branching-merging/screenshots/added feature1.txt and committed it.png"> <br> <br>

<li> Switch to the main branch </li> <br>
<img alt="Switch to main branch" src="/05-branching-merging/screenshots/switched to main branch.png"> <br> <br>

<li> Merge the feature and the main branch </li> <br>
<img alt="Merged feature-1 branch" src="/05-branching-merging/screenshots/merged feature-1 branch.png"> <br> <br>

<li> Check commit history after merging </li> <br>
<img alt="Commit history after merging" src="/05-branching-merging/screenshots/commit history after merging.png"> <br> <br>

<li> Delete feature-1 branch and check the branches </li> <br>
<img alt="Deleted feature-1 branch" src="/05-branching-merging/screenshots/deleted feature-1 branch.png"> <br> <br>

<li> Create feature-2 branch </li> <br>
<img alt="Created feature-2 branch" src="/05-branching-merging/screenshots/created feature-2 branch.png"> <br> <br>

<li> Create a file name feature2.txt </li> <br>
<img alt="Created feature2.txt" src="/05-branching-merging/screenshots/created feature2.txt.png"> <br> <br>

<li> Add feature2.txt and commit it </li> <br>
<img alt="Committed feature2.txt" src="/05-branching-merging/screenshots/added and committed feature2.txt.png"> <br> <br>

<li> Rebase the branches and check commit history </li> <br>
<img alt="Rebased the branches" src="/05-branching-merging/screenshots/rebased with main.png"> <br> <br>

<li> Create feature-3 branch </li> <br>
<img alt="Created feature-3 branch" src="/05-branching-merging/screenshots/created feature-3 branch.png"> <br> <br>

<li> Create a file name conflict.txt </li> <br>
<img alt="Created conflict.txt" src="/05-branching-merging/screenshots/created conflict.txt.png"> <br> <br>

<li> Add conflict.txt and commit it </li> <br>
<img alt="Committed conflict.txt" src="/05-branching-merging/screenshots/added and committed conflict.txt.png"> <br> 
<img alt="Viewed commit history" src="/05-branching-merging/screenshots/commit history after committing conflict.txt.png"> <br> <br>

<li> Switch to the main branch </li> <br>
<img alt="Switched to main branch" src="/05-branching-merging/screenshots/switch to main branch from feature-3.png"> <br> <br>

<li> Add conflicting line to conflict.txt through main branch </li> <br>
<img alt="Added line to conflict.txt" src="/05-branching-merging/screenshots/added line from main branch to conflict.txt.png"> <br> <br>

<li> Add conflict.txt and commit it through main branch </li> <br>
<img alt="Committed conflict.txt" src="/05-branching-merging/screenshots/committed conflict.txt.png"> <br> 
<img alt="Commit history after modifying conflict.txt from main" src="/05-branching-merging/screenshots/commit history after modifying conflict.txt from main.png"> <br> <br>

<li> Merge the feature-3 branch with main branch </li> <br>
<img alt="Merged the branches" src="/05-branching-merging/screenshots/merged feature-3 with main.png"> <br> 
<img alt="Merge conflict error arised" src="/05-branching-merging/screenshots/merge conflict error.png"> <br>
<img alt="Resolved the conflict" src="/05-branching-merging/screenshots/resolved conflict.png"> <br> 
<img alt="Repo status after resolving the conflict" src="/05-branching-merging/screenshots/status after resolving conflict.png"> <br> 
<img alt="Added and committed the conflicts" src="/05-branching-merging/screenshots/added and committed the reolved conflict.png"> <br> <br>

</ol>
