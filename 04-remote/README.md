## 04-Remote

This folder contains practice for working with remote repositories in Git. The goal is to learn how to <b> connect a local repo to GitHub, push/pull changes, clone repos, and manage remotes. <b>

## Commands practiced

- `git remote add origin <url>` - Connect local repo to remote
- `git remote -v` - Verify remote URLs
- `git push -u origin main` - First push, sets upstream
- `git push` - Push commits to GitHub
- `git clone <url>` - Clone repo locally
- `git fetch origin` - Download changes (no merge)
- `git pull origin main` - Fetch and merge changes
- `git remote show origin` - Detailed remote info

## Tasks and Output:

<ol>
<li> Create demo.txt file </li>
![Created demo.txt](<created demo.txt in remote.png>)

<br>

<li> Stage and commit demo.txt file </li>
![Added demo.txt](<added demo.txt.png>)
![Committed demo.txt](<committed demo.txt.png>)

<br>

<li> Add a remote repo and verify it </li>
![Connected to remote repo](<connected to remote repo and verified it.png>)

<br>

<li> Push the commits to remote repo </li>
![Pushed the commits to remote repo](<pushed the commits to remote.png>)

<br>

<li> Modify demo.txt file and commit it </li>
![Modified and committed demo.txt](<modified and committed demo.txt.png>)

<br>

<li> Push the modifications to remote repo </li>
![Pushed the modification of demo.txt](<pushed the modifications of demo.txt.png>)

<br>

<li> Clone another remote repo locally </li>
![Cloned remote repo](<cloned another repo.png>)

<br>

<li> Commit some changes directly from GitHub i.e. remotely </li>
![Committed changes to GitHub](<comitted changes to github.png>)

<br>

<li> Check commit history </li>
![Commit history before fetching](<commit history before fetching.png>)

<br>

<li> Fetch the changes made through GitHub </li>
![Fetched the changes](<fetched the changes made.png>)

<br>

<li> Check commit history after fetching the changes </li>
![Commit history after fetching](<commit history after fetching.png>)

<br>

<li> Pull the changes made through GitHub </li>
![Pulled the changes](<pulled the changes.png>)

<br>

<li> Check commit history after pulling the changes </li>
![Commit history after pulling](<commit history after pulling.png>)

<br>

<li> Check remote repo details </li>
![Remote repo details](<git remote show orgin.png>)