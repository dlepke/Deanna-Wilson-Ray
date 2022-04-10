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