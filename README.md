# How To upload Files on GitHub (using VSCode)

Table of contents
=================

- [How To upload Files on GitHub (using VSCode)](#how-to-upload-files-on-github-using-vscode)
- [Table of contents](#table-of-contents)
  - [Prerequisites:](#prerequisites)
  - [1. Setting User details](#1-setting-user-details)
  - [2. Open folder in VSCode](#2-open-folder-in-vscode)
  - [3. Publishing to Github](#3-publishing-to-github)
  - [4. Adding new changes or new file](#4-adding-new-changes-or-new-file)
  - [5. Want to delete a file](#5-want-to-delete-a-file)
  - [6. How to view my Repository](#6-how-to-view-my-repository)
- [THANK YOU for reading this tutorial.](#thank-you-for-reading-this-tutorial)



---
## Prerequisites:

1. You must have a Github account. If not - create one (it's free):
<a href = "https://github.com/signup" target= "_blank"> GitHub - Sign Up </a>

2. VSCode and Git must be installed on your Computer.
    - Install official git release: [Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) or if you want to have GitBash: <a href = "https://gitforwindows.org/" target= "_blank"> Download Git for Windows (and Git BASH) </a>

    - Install VSCode: <a href="https://code.visualstudio.com/download" target="_blank"> Download VSCode </a>

---

*Note: While doing this tutorial, if VSCode asks for sign in, then simply sign in with your GitHub account and give all permissions required.*

---
## Setting User details

*Note: This is one time process only. Just do it once and you are good to go.*

1. Open Command Prompt (cmd.exe) or GitBash

1. Set user name:

    ```bash
    git config --global user.name "Your User Name"
    ```

1. Set user email (can be your GitHub account email or any other email address, but using your GitHub email is recommended for linking commits to your GitHub profile):
    ```bash
    git config --global user.email "Your Email"
    ```

Now you can close the terminal.

---
## Open project folder in VSCode

1. Open VSCode
2. Select file > Open Folder

![openFolder](./images/vscode-open-folder.png)

3. now select your Project Folder that you want to upload.

[***Note: you must have at least 1 file (even empty) in the folder or its descendants, because git did not track empty folders***.

![selectFolder](./images/vscode-select-folder.png)

---
## 3. Publishing to Github

1. Select Source Control Option

![selectSourceControl](./images/vscode-select-source-control.png)

2. Now click on Publish to GitHub

![publishToGitHub](./images/vscode-publish-to-github.png)

3. Select option for private or public repository

    private => only you can see the repository

    public => anyone can see the repository

![selectPrivatePublic](./images/vscode-select-private-public.png)

4. Now uncheck the checkbox of those file that you don't want to upload

![uncheckFiles](./images/vscode-uncheck-files1.png)

I don't want to upload file.txt file so I am unchecking it.

![uncheckFiles2](./images/vscode-uncheck-files2.png)

5. then press OK

Now it will start uploading your files to your GitHub repository.

![uploadingFiles](./images/vscode-uploading-files.png)

after few second Upload will complete.

![uploadComplete](./images/vscode-upload-complete.png)

Now click on Open on GitHub to view the repository.

Now repo will be opened in your browser.

![openGitHub](./images/open-github.png)

Now in your VScode you will see a new file named as `.gitignore`. This file specifies which files and directories should be excluded from Git and uploading to GitHub.

![gitignore](./images/gitignore.png)

---
## 4. Adding new changes or new file

I have added a new file in my repository named newProgram.c
![addNewFile](./images/add-new-file.png)

Now click on Source control button.This will show all the changes that i have made in my repository.

![changes](./images/changes.png)

Now write commit message(type anything you want) and click on commit changes(the tick option).

![commitChanges](./images/commit-changes.png)

Click on Yes

![yes](./images/yes.png)

Now click on three dot and click on push option.

![pushChanges](./images/push-changes-three-dot.png)

![pushChanges](./images/push-changes-push.png)

Open your browser.

![openBrowser](./images/open-browser.png)

Referesh the page to view all new file/ changes you have made.

![viewChanges](./images/view-changes.png)

All new changes are updated in your repository.

If in future you want to add new commit then you can do it by repeating this step again.

[Note : new commit means new changes in your repository]

[want to add more changes](#4-adding-new-changes-or-new-file)

---
## 5. How to delete a file

Simply delete the file in your VSCode and follow [Step 4](#4-adding-new-changes-or-new-file) (as this is a change).

---
## 6. How to view my Repository

1. open your gitHub account

![openGitHub](./images/open-github-account.png)

2. Now click on Repositories

![repositories](./images/view-all-repo.png)

3. Now click on your repository that you want to view.

---
# THANK YOU for reading this tutorial.
