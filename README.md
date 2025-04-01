# Git Basic Mini Project 2
<p> This is a mini project to practice Git commands. </p>
<p> The project is aimed to help you understand the basic commands of Git. </p>

## Task 1: Create a new repository
1. Created a new repository on github and then cloned it to your local machine.
![](./img/repo_img_1.png)

2. Cloning the repository using SSH methods.
![](./img/cloning-using-ssh-key_2.png)

3. Created folder for the repo using `mkdir` command.
![](./img/created-folder-for-the-project_4.png)

4. Cloned to the local machine using the command line.
    <p> This command will create a local copy of the repository on your machine. </p>
```git clone <repository-url>```
    <p> The command will create a directory with the same name as the repository. </p>

![](./img/cloned-to-localhost_3.png)

5. Moved to the cloned directory using `cd` command.

![](./img/moved-into-the-repo_6.png)

6. Created a new file using `touch` command.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](./img/created_index.html_7.png)

7. Checked the status of the repository using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](./img/check-if-changes-staged_8.png)

8. Added the file to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](./img/staged_index.html_9.png)

9. Committed the changes using `git commit` command.
```git commit -m "<commit-message>"```
    <p> This command will commit the changes to the repository. </p>
![](./img/commit_and_push-to-main_10.png)

10. Successfully pushed the changes to the remote repository using `git push` command.
```git push origin <branch-name>```
    <p> This command will push the changes to the remote repository. </p>
![](img/successfully_pushed_11.png)

11. Check current branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](img/chech-current-branch_12.png)

12. Created a new branch for Tom using `git checkout -b` command.
```git checkout -b <branch-name>```
    <p> This command will create a new branch and switch to it. </p>
![](img/created_&switched_update-nav_13.png)

13. Confirmed the branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](img/check-branch-switch_14.png)

14. Editing the html file on Tom's branch.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](img/Tom-nav_15.png)

15. Confirmed the changes using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](img/checking-changes-in-tom_16.png)

16. Added the changes to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](img/staging_&_confirming_tom_17.png)

17. Commit and push the changes to the remote repository using `git commit` and `git push` commands.
```git commit -m "<commit-message>"```
```git push origin <branch-name>```
    <p> This command will commit the changes to the repository. </p>
    <p> This command will push the changes to the remote repository. </p>
![](img/commit_&_pushed_tombranch_18.png)

18. Switched back to the main branch using `git checkout` command.
```git checkout <branch-name>```
    <p> This command will switch to the specified branch. </p>
![](img/switched-back-to-main_19.png)

19. Pulled changed from update-nav branch using `git pull` command.
```git pull origin <branch-name>```
    <p> This command will pull the changes from the specified branch. </p>
![](img/pull-changes-from-updatebranch-to-main_20.png)

20. Checkout and switched to add-contact-info branch using `git checkout` command.
```git checkout <branch-name>```
    <p> This command will switch to the specified branch. </p>
![](img/checkout_&_switch_to_add-contact_info_21.png)

21. Confirm changes and push to the remote repository using `git status` and `git push` commands.
```git status```
```git push origin <branch-name>```
    <p> This command will show you the current status of the repository. </p>
    <p> This command will push the changes to the remote repository. </p>
![](img/confirming_changes_&_pushed-to_github_22.png)
![](img/backup_for_22.png)

