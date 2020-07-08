## Create GitHub Account

- Go to GitHub page to create an account:
[Click Here](https://github.com/join)

- Provide the necessary details to create an account as shown below:

![image](https://user-images.githubusercontent.com/25001852/86441214-79068280-bd29-11ea-913d-c575c8ff8282.png "Git Create Account")

and click 'Create account'.

- Click `Verify` to verify the account and click 'Done' 

![image](https://user-images.githubusercontent.com/25001852/86436621-4310d080-bd20-11ea-866a-8ba864d08211.png "Verify")

- After verification done. Click `Join a Free Plan`

![image](https://user-images.githubusercontent.com/25001852/86436707-6b003400-bd20-11ea-8c51-7a5d58ca1bc5.png 'Join Free Plan')

- Select the details as shown below and click `Complete Setup`

![image](https://user-images.githubusercontent.com/25001852/86431692-13a79700-bd13-11ea-9dcf-ae779bb2feb1.png "Complete Setup")

- Verify your `Email Address`

![image](https://user-images.githubusercontent.com/25001852/86437013-304acb80-bd21-11ea-9310-3a0b1ee12497.png "Verify Email")

Email is verified

![image](https://user-images.githubusercontent.com/25001852/86431929-b52ee880-bd13-11ea-8ccf-6bb854408f70.png)


## SSH Key Generation
- Launch Git Bash.
- Type the following, replacing <your email address> with the email address that is linked to your Github account, and hit Enter:

`ssh-keygen -t rsa -b 4096 -C "<your email address>"`

This will generate a new SSH key.

- Next, you will be prompted to enter a directory to save the key. I simply press Enter to accept the default location, which is a .ssh folder in the home directory. In ther words, you will be able to locate the key in `~/.ssh/id_rsa`

- You will then be prompted to choose a passphrase. I prefer not to have a passphrase; so just press Enter and Enter again to confirm the empty passphrase.

Now, if you navigate to the .ssh directory, i.e., if you run the following in the Git Bash terminal,

`cd ~/.ssh`

and then,

`ls`

To the list the contents of the .ssh directory, you should find “id_rsa” and “id_rsa.pub” in the list of contents, where “id_rsa” is the private version of your key and “id_rsa.pub” is the public version of your key.

- Finally, you will need to add the SSH key to the ssh-agent, which is meant to help with the authentication process. To do that, first you need to start the ssh-agent, so run the following in the Git Bash terminal:

`eval "$(ssh-agent -s)"`

- And then add the key to the agent by running the following in the Git Bash terminal:

`ssh-add ~/.ssh/id_rsa`

- Copy the command using the below command:

`cat ~/.ssh/id_rsa.pub | clip`

- Now, Open GitHub and go to Setting 

![image](https://user-images.githubusercontent.com/25001852/86890946-b0a36f00-c11b-11ea-837e-b4402f4c591d.png)

Under Personal settings, select “SSH and GPG keys”, as shown below:

![image](https://user-images.githubusercontent.com/25001852/86891261-2b6c8a00-c11c-11ea-9684-338dbadf38a3.png)

click the button to add a new SSH key

![image](https://user-images.githubusercontent.com/25001852/86891396-61aa0980-c11c-11ea-957c-0753f446b356.png)

Provide the title. Then select the Key field, and press Ctrl-v to paste the key from the clipboard buffer. The pasted key should have your email address at the end, as shown below:

![image](https://user-images.githubusercontent.com/25001852/86891784-04fb1e80-c11d-11ea-94a6-20ec7bc2abf4.png)

and click 'Add SSH Key'.

Now, the SSH key is added to your account.
