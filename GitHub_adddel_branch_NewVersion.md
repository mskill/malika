
## Hands-o Lab 2: Add branch to repository and creating the PUSH/PULL request

### Creating and deleting branches within your repository

You can create or delete branches directly on GitHub.

## Creating a branch

- Currently, there is one branch as shown below:

![image](https://user-images.githubusercontent.com/25001852/86443488-f7185880-bd2c-11ea-8afa-24df75b2bb11.png)

- On GitHub, navigate to the main page of the repository.

- Click the `Branch selector` menu. Enter the name of the branch you want to create and press `Enter`. 

![image](https://user-images.githubusercontent.com/25001852/86453720-db687e80-bd3b-11ea-801c-ae054058469c.png "Child branch")

You will then see that your repository has two branches.

![image](https://user-images.githubusercontent.com/25001852/86443756-59715900-bd2d-11ea-9942-d3ff15328498.png "Branch number")

Whatever, is in the master file is copied to the child branch. But when we add a file or edit any file in child branch that will not reflect in the 'Master' branch.

## Adding a file in the Child Branch

- Click `Add file` and select `Create New file` to create a file in the repository.

![image](https://user-images.githubusercontent.com/25001852/86445211-9dfdf400-bd2f-11ea-96d6-5af2f3da38bb.png "New File")

- Provide the file name and the extension of the file. For example, `testchild.py` and add the lines.

![image](https://user-images.githubusercontent.com/25001852/86444945-2cbe4100-bd2f-11ea-8ed9-4bf50953546f.png "Create a file in child branch")

- Scroll down the page after adding the text. `Add description` of the file (optional) and click `Commit new file`.

![image](https://user-images.githubusercontent.com/25001852/86445112-73ac3680-bd2f-11ea-83df-7ca4cdc53f66.png "Commit in child branch")

File is added to the child branch

## Compare and Pull Request

You can check the master branch now there is no testchild.py file by selecting the `Branch selector` menu 

![image](https://user-images.githubusercontent.com/25001852/86469000-28f1e500-bd56-11ea-9191-b5705aec84b3.png "Difference")


Or you can also compare the file as shown below with the option given `Compare and pull request`.

![image](https://user-images.githubusercontent.com/25001852/86445527-2da3a280-bd30-11ea-8ffa-a88d0f236099.png "compare")

- Scroll down the page, you will get 1 file changed

![image](https://user-images.githubusercontent.com/25001852/86445603-5035bb80-bd30-11ea-9567-18d04c71376e.png "file changed")

- Scroll up and create a pull request using the option `Create Pull request`. In the highlight, you can see the arrow which means that you are comparing and creating a pull request. `Add the comments`  (optional) to create a request.

![image](https://user-images.githubusercontent.com/25001852/86446021-f71a5780-bd30-11ea-99d1-e7010d9aad5c.png)

## Merge the Pull Request

To accept the pull request, click the `Pull Requests` tab to see a summary of pending pull requests. If you are happy with the changes, click `Merge Pull request` to accept the pull request and perform the merge. You can add in a comment if you want.

![image](https://user-images.githubusercontent.com/25001852/86446556-bf5fdf80-bd31-11ea-9029-3ebaf9356c0d.png)

Once you click `Merge Pull request`, you will see a button `Confirm merge`.

![image](https://user-images.githubusercontent.com/25001852/86446749-0221b780-bd32-11ea-9741-eebde8648291.png)

Your request is now merged successfully.

![image](https://user-images.githubusercontent.com/25001852/86446923-385f3700-bd32-11ea-9be1-2942d4b4f0da.png)

Now, the child branch is completely merged with the Master branch. You can check the Master branch is having the `testchild.py` file.

![image](https://user-images.githubusercontent.com/25001852/86447135-82481d00-bd32-11ea-9607-fed8862e4155.png)


## Summary

In this document, you have learnt how to create a branch, edit and commit the changes, Open a pull request and merging the request.

