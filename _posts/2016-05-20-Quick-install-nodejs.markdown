---
layout: post
title:  "Quick install Nodejs"
date:   2016-05-20 17:36:29 +0530
categories: nodejs proxy ubuntu
---

In this post you will learn how  to easy install nodejs.(For unix)

`It is recommended to install nodejs through **nvm** which helps you manage nodejs versions and switch between them.`

Steps:


- Use install script using wget
    
    `wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash`
     
    or install updated version of nvm from [here](https://github.com/creationix/nvm#install-script).
- Check nvm installation by `command -v nvm`. It will show nvm as output.
- Now to install latest version of nodejs run `nvm install stable'.
- It will show you installed nodejs version at the end.

You can switch between nodejs version using `nvm use <version>`.



