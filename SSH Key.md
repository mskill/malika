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


SSH and GPG keys, Click 'New SSH Key' and use CTRL + V to paste the key that we copied using the clip command.

- Click 'Add' and now follow the further instructions given in the reading.
