---
layout: default
title: Add SSH to Github Account
parent: Setting Up SSH
nav_order: 4
---

# Adding an SSH Key to Your GitHub Account

Now that you have generated an SSH key and linked it to your device, it is time to add it to your GitHub account.

## Step 1: Log into your GitHub Account
First, log into your GitHub account at [GitHub.com](https://github.com/login).

If you do not currently own a GitHub account, one can be made [here](https://github.com/signup).

Upon logging in, you will be taking to you GitHub home page, which will look something like this:

![](../../assets/images/GitHub_home_page.png)

## Step 2: Navigate to your account settings page
In the top right corner, click the little circle profile icon, and select "Settings" from the drop down list, as pictured below:

![](../../assets/images/addSSHstep2.png)

This will take you to your profile page, which should be similar to the following:

![](../../assets/images/settings-profile-page.png)

## Step 3: Go to the SSH Keys page
Click the "SSH and GPG Keys" option from the column on the left, like this:

![](../../assets/images/settings-click-SSH.png)

Doing so should bring you to this page:

![](../../assets/images/SSH_keys_page.png)

## Step 4: Add a new SSH key
Click the green button in the top right labelled "New SSH Key", which looks like this:

![](../../assets/images/New_SSH_Key.png)

Doing so should take you to a page that looks similar to this:

![](../../assets/images/Add_key_page.png)

Here you should input the SSH key you generated previously [see here for instructions on how to generate an SSH key](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/generateSSHKey/). You can also add a title to make distinguishing between keys easier.

Once you are done, click the green "Add SSH Key" button to add your newly generated key to GitHub

![](../../assets/images/finally_add_ssh_key.png)

## Step 5: Authenticate your account credentials
Clicking the "Add SSH Key" button will take you to a page prompting you to authenticate your credentials by entering your password again. Do so, and you should be taken back to the "SSH and GPG Keys" page from step 3b. However, this time, you should be able to see your newly added SSH key in the field under "SSH Keys", like the picture below.

![](../../assets/images/key_added_successfully.png)

## Congratulations!
You have now added an SSH key to your GitHub account, and are ready to start [cloning repositories with it](https://dlepke.github.io/Deanna-Wilson-Ray/docs/UsingSSHWithGit/forkandclone/).