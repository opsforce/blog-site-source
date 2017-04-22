title: Github quick setup
categories: git
tags: [git,github]
summary: Github quick setup
---
We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line
```bash
echo "# site" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:opsforce/site.git
git push -u origin master
```
…or push an existing repository from the command line
```bash
git remote add origin git@github.com:opsforce/site.git
git push -u origin master
```
