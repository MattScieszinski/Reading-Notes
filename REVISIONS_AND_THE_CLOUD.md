# Revisions and the Cloud
With Git, I am now able to markup, create, and code on my CPU machine with text editors instead of logging into GitHub. Now, all my creations and files are cloned and connected to the cloud. 
## Cloning and Publish files from VSCode to GitHub via terminal
To go from GitHub repo to computer database to publishing files back to the GitHub repo:
1. Go to the folder you'd like to place your repo in with `cd ~/file.1/file.2/etc./`
2. In GitHub, hit the green "Download Code" button and copy the HTTPS link
3. Enter the command `git clone https://____` and paste the repository link in the blank space 
   - ***Congrats!*** The repo is now copied and linked into your hardrive and connected to the cloud

Now let's create and save a new file into the repo

4. Enter into the newly copied repo with `cd RepoName`
5. Enter `code .` to open VSCode and create a new file to work with
6. After every good saving point, `git add <file>` will add and enter your file into the repo
7. `git commit -m 'Add &/OR Update message'` is next to "Save As..." your file. `-m` tag give you the option to enter a description of why the snapshot you made changed.
8. Finally, `git push origin master` publishes the file to the repo and is now viewable in your repository

*Protip* ~ Make sure to enter `git status` after entering code from steps 4-8. This allows you to keep track of the progress of your file and to make sure you are following the right steps and check the status of the file. It is easy to plow through the steps, so make sure your work is going throught the proper procedures. Also, `git remote -v` allows you to view the link(s) your branches are fetching and pulling from (enter before steps 4-8)

## General Vocab and Code
States of Files:
**Committed** files have data securely stored in the local database. **Modified** files are changed, yet not committed. **Staged** files have been flagged for their changed version ready to be commited in the next snapshot.

*Tracked* files can be (Un)Modified or Staged; part of the latest snapshot **VS.** *Untracked* files are not in the staging area &. are not in the latest snapshot

`git stash` is useful for saving file changes as draft, for when you don't want to commit to changes nor delete the edits entirely. Enter `git stash apply` for when you are ready to commit to those changes.

### Table of Contents
- [Growth Mindset](/GrowthMindset.md)
- [Section One Summary](/SectionOne.md)
- [What is Markdown?](/LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Git Clone Exercise](GIT_CLONE.md)
- [Revisions and the Cloud](REVISIONS_AND_THE_CLOUD.md)
