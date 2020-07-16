## Hands-on Lab: Creating and merging branches in your GitHub repo
<img style="float:left;" src="images/IDSNlogo.png" width="200" height="200"/>

<b>Effort:</b> 20 min

## Objectives
After completing this lab you will be able to:
1. Create a branch
2. Commit changes in the child branch
3. Open a pull request (PR)
4. Merge the PR into the master branch

## Pre-requistes
This hands-on lab requires you to have already created a GitHub account, and added a project to it, as illustrated in the [previous lab](GitHub1_Getting_Started.md.html)

## Exercise 1: Creating a branch
You can create or delete branches directly on GitHub.

- Currently, there is one branch as shown below:

![image](images/Check_Repo.png "Check Repo")

- On GitHub, navigate to the main page of the repository.

- Click the `Branch selector` menu. Enter the name of the branch you want to create and press `Enter`. 

![image](images/Enter_branch_name.png "Enter_branch_name")

You will then see that your repository has two branches.

![image](images/Branch_number_changed.png "Branch_number_changed")

Whatever is in the master file is copied to the child branch. But when we add a file or edit any file in child branch that will not reflect in the 'Master' branch.

## Exercise 2: Adding a file in the Child Branch

- Click `Add file` and select `Create New file` to create a file in the repository.

![image](images/Create_file_branch.png "Create_file_branch")

- Provide the file name and the extension of the file. For example, testchild.py and add the lines.

![image](images/Add_content_branch.png "Add_content_branch")

- Scroll down the page after adding the text. Add a description of the file (optional) and click Commit new file.

![image](images/Commit_branch_file.png "Commit_branch_file")

The file is added to the child branch.

## Exercise 3: Open a Pull Request

You can check the master branch now there is no testchild.py file by selecting the `Branch selector` menu 

![image](images/Master_check.png "Master_check")

Or you can also compare the file as shown below with the option given Compare and pull request.

![image](images/Compare_Pull.png "Compare_Pull")

- Scroll down the page, you will get 1 file changed

![image](images/File_Changed.png "File_Changed")

- Scroll up and create a pull request using the option Create Pull request. In the highlight, you can see the arrow which means that you are comparing and creating a pull request. Add the comments (optional) to create a request.

![image](images/Create_Pull_Request.png "Create_Pull_Request")


## Exercise 4: Merge the Pull Request

To accept the pull request, click the `Pull Requests` tab to see a summary of pending pull requests. If you are happy with the changes, click `Merge Pull request` to accept the pull request and perform the merge. You can add a comment if you want.

![image](images/Merge_Request.png "Merge_Request")

- Once you click Merge Pull request, you will see a button Confirm merge.

![image](images/Confirm_Merge.png "Confirm_Merge")

Your request is now merged successfully.

![image](images/Merge_Success.png "Merge_Success")

Now, the child branch is completely merged with the Master branch. You can check the Master branch is having the testchild.py file.

![image](images/File_Add_Master.png "File_Add_Master")

## Summary

In this document, you have learned how to create a branch, edit and commit the changes, open a pull request, and merge the request.

## Author(s)
<h4> Malika Singla <h4/>

### Other Contributor(s) 
Rav Ahuja

## Changelog
| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
| 2020-07-14 | 0.3 | Rav Ahuja | Changed logo, updated title, intro, objectives, added Effort, Authors and Changelog |
| 2020-07-13 | 0.2 | Malika Singla | Added to GitLab and made some formatting changes, added objectives, etc. |
| 2020-06-30 | 0.1 | Malika Singla | Drafted initial version |
