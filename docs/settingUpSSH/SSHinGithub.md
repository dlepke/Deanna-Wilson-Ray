---
layout: default
title: Add SSH key to GitHub account
parent: Setting Up SSH
nav_order: 4
---

# Adding an SSH Key to Your GitHub Account

Now that you have generated an SSH key and you have linked it to your device, the next step is adding it to your GitHub account.

## Step 1: Log into your GitHub Account

If you are not already signed into your GitHub account, log in at [GitHub.com](https://github.com/login).

![An image of Github's login page](../../assets/images/github_signin.png)

| ![Info Icon](../../assets/images/info.png) | If you do not currently have a GitHub account, you can make one [here](https://github.com/signup). |

Once you've logged in, you will be taken to the GitHub home page, which will look something like this:

![An image of Github's landing page for logged in users](../../assets/images/GitHub_home_page.png)

## Step 2: Navigate to your account settings page
In the top right corner, click the little circle profile icon, and select "Settings" from the drop down list, as pictured below:

![An annotated image of Github's landing page, with the profile button annotated](../../assets/images/addSSHstep2.png)

This will take you to your profile page, which should be similar to the following:

![An image of Github's User Profile page for logged in users](../../assets/images/settings-profile-page.png)

## Step 3: Go to the SSH Keys page
Click the "SSH and GPG Keys" option from the column on the left, like this:

![An annotated image of Github's profile page, highlighting the SSH and GPG Key button](../../assets/images/settings-click-SSH.png)

Doing so should bring you to this page:

![An image of the SSH Key page on Github](../../assets/images/SSH_keys_page.png)

## Step 4: Add a new SSH key

Now, we add the SSH key you generated earlier to your GitHub account.  

If you no longer have this key available, you can enter the following command into Terminal to copy it into your clipboard again:  

![An image of the command to copy your SSH key to your clipboard](../../assets/images/copy_key.png)

1) Click the green button in the top right labelled "New SSH Key", which looks like this:

![An annotated image of the SSH Key Page on Github, highlighting the "New SSH Key" Button](../../assets/images/New_SSH_Key.png)

2) This will take you to a page that looks similar to this:  
  
![An image of Github's Add SSH Key Page](../../assets/images/Add_key_page.png)  

3) Here you should input the SSH key you generated previously [see here for instructions on how to generate an SSH key](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/generateSSHKey/)

4) You can also add a title; this will help identify which device that SSH key is linked to

5) Once you are done, click the green "Add SSH Key" button to add your newly generated key to GitHub 

![An image of Github's SSH Add Key Page after filling in the necessary SSH Key information](../../assets/images/finally_add_ssh_key.png)

## Step 5: Authenticate your account credentials
Clicking the "Add SSH Key" button will take you to a page prompting you to authenticate your credentials by entering your password again.  

Once you've done this, you should be taken back to the "SSH and GPG Keys" page from Step 3. However, this time, you should be able to see your newly added SSH key in the field under "SSH Keys", like the picture below.

![An image of the page shown by Github upon successfuly entering a new SSH Key](../../assets/images/key_added_successfully.png)

## Congratulations!
You have now added an SSH key to your GitHub account, and are ready to start [cloning repositories with it](https://dlepke.github.io/Deanna-Wilson-Ray/docs/UsingSSHWithGit/forkandclone/).