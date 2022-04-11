---
layout: default
title: Check for an SSH key
parent: Setting Up SSH
nav_order: 1
---

# Check For Existing Public SSH Keys

Before beginning this guide, you should first check if your device already has a public SSH key set up. You can do this by following the guide below.

|  ![Info Icon](../../assets/images/info.png) | If you know that you already have a public SSH key set up on your device, please begin this guide at [Step 3: Adding An SSH Key to GitHub.](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/SSHinGithub/).|


## Step 1: Open Terminal

On your Mac device, open the Terminal app. It should look something like the following:

![An image showing the appearance of a new terminal window](../../assets/images/Terminal-start.png)


## Step 2: Check for existing keys

In Terminal, enter the following command:

`ls -al ~/.ssh`

![An image showing the command line with show directory command typed in](../../assets/images/Terminal-enter-command-check-ssh.png)

This command is telling your machine to print out a list of the files and directories present in your default SSH key directory.

|  ![Info Icon](../../assets/images/info.png) | If you suspect that you may have SSH keys set up elsewhere on your device (other than the default location), you can replace "ssh" in the above command with your target directory (e.g. `ls -al ~/.target-directory). |

## Step 3: Check for any of the following file names

After typing in the command from Step 2, if you see any of the following file names, you may already have an SSH key set up:

* id_rsa.pub
* id_ecdsa.pub
* id_ed25519.pub

These files would appear like the following:

![An image showing the results of the show directory command where there are pre-existing SSH keys](../../assets/images/Terminal-check-for-ssh.png)


|  ![Info Icon](../../assets/images/info.png) | If you receive an error that ~/.ssh doesn't exist, then you do not have an existing SSH key pair. |

## Step 4: If you have an existing key

If you have any of the files from Step 3 already on your device, you already have a generated SSH key and you can skip ahead to [adding your SSH key to your local device.](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/addnewSSH/)


## Next: [Generate a new SSH key](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/generateSSHKey/)