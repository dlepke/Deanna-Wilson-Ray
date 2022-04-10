---
layout: default
title: Troubleshooting Guide
nav_order: 4
---

# Troubleshooting

|Issue|Likely Cause|Suggested Solution|
|-----|-----|-----|
|Clicking "Add SSH Key" when trying to add a new SSH key to GitHub results in an error message being displayed at the top of the page|SSH key was not spelled properly|Check the spelling to ensure it matches the generated key.|
|`ssh-add` illegal option `--K` error|You may be using a version of MacOS in which the -K flag is deprecated.| If you are using Monterey, you can try to use `--apple-use-keychain` instead. Otherwise, check for the equivalent flag for your version of MacOS.|
|Bad configuration option: usekeychain error|You may have omitted the UseKeychain line from your config file (if you did not attach a passphrase to your SSH key).| Add the line `IgnoreUnknown UseKeychain` to your config file.|
|Errors regarding `ed25519` keys being unavailable on your system| You may be using legacy or otherwise software.|You can generate a key using other algorithms instead, though they may be less secure.|
|Command-Line Error `bits has bad value` |You may have entered in SSH key generation command incorrectly.|Make sure there are no typos in your command and that you are using the correct flags.|
|Errors regarding `eval "$(ssh-agent -s)"`|Your system may be set up to require administrative access for this command, or you may be using a legacy version of MacOS.|If you receive an error regarding a requirement to have root access, try entering `sudo -sh -H` before entering the `eval` command.|
| | |Depending on the terminal version you are using, you may need to enter `exec ssh-agent bash` instead of the `eval` command.|
| | |Depending on the terminal version you are using, you may need to enter `exec ssh-agent zsh` instead of the `eval` command.