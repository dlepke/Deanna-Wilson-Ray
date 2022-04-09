---
layout: default
title: Introduction
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Introduction
{: .fs-9 }
Greetings, User!

The purpose of this guide is to assist you with setting up an SSH key with your Github account so that you can easily push your work to a code repository on GitHub. By using an SSH key, there is no need for the hassle of tokens that may expire or be forgotten!

### Table of Contents
* [Intended Users](#Intended-Users)
    * [Prerequisite Knowledge](#Prerequisite-Knowledge)
    * [Software Requirements](#Software-Requirements)
    * [Procedures Overview](#Procedures-Overview)
* [Why Use SSH](#Why-Use-SSH)
* [Typographical Conventions](#Typographical-Conventions)
* [Notes and Warning Messages](#Notes-and-Warning-Messages)

## Intended Users {#Intended-Users}
This guide is for Mac users who are:
* Beginner or Intermediate level programmers with a basic knowledge of their computer's command-line interface
* Individuals with little to no knowledge of what "SSH" is or how to set it up on a local device

### Prerequisite Knowledge {#Prerequisite-Knowledge}
You should already have:
* Git already set up on their workstations
* A Github account
* A basic understanding of the command line interface for the Git version control tool

### Software Requirements {#Software-Requirements}
Prior to using this guide, please make sure that you have the newest version of Git installed on your device. If you aren't sure, you can check which version you have by entering:  
`"git --version"`  
in Terminal. If you need to do a fresh install of Git, you can find the latest version [here.](https://git-scm.com/download/mac)

### Procedures Overview {#Procedures-Overview}
The main sections of the documentation are as follows:
* Checking for existing SSH keys
* Generating a new GitHub SSH key
* Adding a new SSH key to your local device
* Forking, cloning, and pushing to a repo from the command line
* Pushing changes to GitHub

## Why Use SSH? {#Why-Use-SSH}
These days, passwords can be easy to forget, hard to remember, and require constant updates if a data breach occurs. To avoid the issues a compromised password can cause, Github users are able to create what are known as "SSH key pairs" that provide a secure, reliable way to authenticate a user's credentials.

While setting up an SSH key pair initially requires more time than regular username/password combinations, the end result is an SSH key that is more secure than a password and less vulnerable to compromise.

This guide aims to make the process simple and easy to follow.

If you would like to learn more about SSH key pairs, [click here](https://www.thorntech.com/passwords-vs-ssh/).

## Typographical Conventions {#Typographical-Conventions}
In this guide, we will provide commands for you to enter into Terminal. These commands will appear like this:
`This is how a Terminal command will look`


## Notes and Warning Messages {#Notes-and-Warning-Messages}
Throughout these instructions, we will use special symbols to alert you to important relevant information or aspects to be aware of.

| Symbol | Description|  
|----------|-------------|
|![](/assets/images/danger.png) | **Danger:** This symbol indicates a dangerous action that could lead to a crash or other major issue.|
|![](/assets/images/warning.png) | **Warning:** This symbol denotes a warning. We highly recommend that you read and keep this in mind when proceeding. |
|![](/assets/images/info.png) | **Info:** This symbol is to alert you to additional information or potentially useful tips that may be of use or interest. |
|![](/assets/images/success.png) | **Success:** This symbol means a job well done. Congratulations!|

