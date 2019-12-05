# GitHub Tutorial

_by freddy norori_

---
## Git vs. GitHub
git status: inspects the contents of the working directory and staging area
git add: adds to the staging area
git commit: adds to your repository
git log: lets you view commits stored in the repository chronologically
git diff: checks the differences between the working directory and the staging area

---
## Initial Setup
**git config** Used to shape/order/put togeter or order something.
1. Use git config --global user.email "you@example.com
   - Example:git config --global user.email _"jondoe@hstat.org"_
2.git config --global user.name "Your Name"
3.git config --global user.name "Your Name" then press the enter key
4.eval "$(ssh-agent -s)"
5.ls -al ~/.ssh you should now see a file named id_rsa.pub
6.cat ~/.ssh/id_rsa.pub then copy all of the result to your clipboard
7.o to https://github.com/settings/keys > New SSH Key
Title: ide50
Key: paste your ssh key
Press the green Add SSH key button
8.do sudo nano ~/.ssh/config
9.Paste the following:
Host github.com
 Hostname ssh.github.com
 Port 443
10.ssh -T git@github.com
Type yes, press ENTER, and you should see
11. and know you are done
---
## Repository Setup



---
## Workflow & Commands
