---
layout: default
title: How to Git push with SSH
parent: Using SSH With Git
nav_order: 2
---

## How to Git Push with SSH
This portion of the guide assumes that you have completed all of the steps necessary to generate, add, and set up an SSH Key with your Github account.

## Step 1: Navigate to your project directory
In a new terminal window, navigate to the working directory of the project you wish to push to your Github repository. A few commands that could work:

`cd myWorkingDirectory`
`open ~/.myWorkingDirectory`

## Step 2: Add your changes to a commit
Assuming you have already made new changes to your repository, enter the following commmand:

`git add .`

The "." is telling git to add all changed files to your latest commit.

## Step 3: Commit your changes
In your terminal, enter the following command:

`git commit -m"my commit details"`

Where the information between the double quotes relates to the work you are pushing to your repository.

## Step 4: Push your changes
Now all that's left is to push your changes to your repository. If you have set up your SSH key correctly, all that you need to do is enter the following into the terminal:

`git push -u origin`

And that's it! If all is well, you should receive confirmation that your push was succesful. If, instead, you receive any errors then you can head over to our [troubleshooting](https://dlepke.github.io/Deanna-Wilson-Ray/docs/troubleshooting/) guide for assistance.