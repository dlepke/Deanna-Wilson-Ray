---
layout: default
title: Generate an SSH key
parent: Setting Up SSH
nav_order: 2
---

[//]: # (---)
[//]: # (layout: default)
[//]: # (title: Code)
[//]: # (parent: UI Components)
[//]: # (has_children: true)
[//]: # (nav_order: 6)
[//]: # (---)

[//]: # (---)
[//]: # (layout: default)
[//]: # (title: Code with line numbers)
[//]: # (parent: Code)
[//]: # (grand_parent: UI Components)
[//]: # (permalink: /docs/ui-components/code/line-numbers/)
[//]: # (---)

# Generate A New SSH Key

If you haven't already, [check if you already have a public SSH key set up.](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/checkforSSH/)

If you have already generated a public SSH key, please skip to the next step: [Adding a public SSH key to your local device.](https://dlepke.github.io/Deanna-Wilson-Ray/docs/settingUpSSH/addnewSSH/)

1. Open Terminal  
2. Enter the following command into Terminal:  

`ssh-keygen -t rsa -b ed25519 -C "your_email@example.com"`  

![](../assets/images/info.png) This will generate a new SSH key on your device, using the Ed25519 algorithm. You can learn about this algorithm [here](https://en.wikipedia.org/wiki/EdDSA#Ed25519).  

3. When you're prompted to "Enter a file in which to save the key," simply press Return (or Enter on a non-Apple keyboard).

This will accept the default file location for your new SSH key.

4. When you're prompted to "Enter passphrase", you can either:  
    * Enter a secure passphrase (you will have to type this in every time you use your SSH key)  
    * Immediately press Return on your keyboard to skip and have no passphrase

5. 