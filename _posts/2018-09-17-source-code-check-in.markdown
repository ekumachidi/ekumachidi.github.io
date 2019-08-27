---
layout: post
title:  Source code check-in with git
date:   2018-09-17 07:11:50 +0100
img: 4.jpg
tags: [Git, Team Foundation Server, Vsts, Github, Version Control, Source code]
---

My organisation is transitioning and adopting git as the defacto VCS system. As someone at the forefront of this adopttion, I get asked too often about how to check in source-codes to git repositories on TFS having explained the process over and over I decided to just write this step by step guide on how to check-in source codes to git repositories from the command line.

Source code check in simply means uploading source codes to a remote repository. Checkout is the opposite of check-in; simply means to download a copy of the source code from the repository.

1.  Navigate to the root of the project you want to check in `cd ~/users/myUsername/ProjectFolder`

Assuming it’s a new repository

2\. Initialize the new repository `git init`

3\. Add the source files to the new repository `git add .` to add all the files in the folder OR `git add filename.ext` to add specific files

4\. Commit the newly added files `git commit -m "Commit message"` the `-m` flag lets git know that you’re going to supply a commit message.

5\. Add a link to the online repository `git remote add remoteName url` eg `git remote add origin [https://github.com/username/testproject.git](https://github.com/username/testproject.git)`

6\. Check-in the source codes to the remote repository `git push origin -u` this command will push all the existing branches on your local machine to the new online repository.

7\. In some environments you may have SSL issues you can add this to your git config `git config http.sslVerify false`

_….End of process._