# Website
First version of my website

Directions to SSH
1. Generate SSH key: If you haven't already done so, you need to generate an SSH key. You 
  can generate an SSH key using the ssh-keygen command on your terminal. Follow the prompts to generate your SSH key.
  
2. Add your SSH key to your GitHub account: Once you've generated your SSH key, you need to add it to your GitHub account. 
  Go to your GitHub account settings, click on "SSH and GPG keys" and then click "New SSH key". Copy the contents 
  of your public SSH key (typically found in ~/.ssh/id_rsa.pub) and paste it into the "Key" field.
  
3. Verify your SSH connection: To verify that your SSH connection is working properly, enter the following command in your 
  terminal: ssh -T git@github.com. You should see a message that says "Hi username! 
  You've successfully authenticated, but GitHub does not provide shell access."
  
4.Clone your repository: To clone your repository using SSH, go to your repository on GitHub and click
  on the green "Code" button. Select "SSH" from the dropdown menu and copy the SSH URL. 
  Then, in your terminal, navigate to the directory where you want to clone your repository and 
  enter the following command: git clone git@github.com:<username>/<repository>.git. Replace <username> and <repository> with your 
  GitHub username and repository name, respectively.

Once you've cloned your repository, you can make changes to your code and push them to your GitHub repository 
  using Git commands like git add, git commit, and git push.
