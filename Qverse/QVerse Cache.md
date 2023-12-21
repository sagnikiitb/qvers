https://github.com/sagnikiitb/qvers

How to Git any local repo to github :

#!/bin/bash
git init
git add .
git commit -m "Initial commit"
git config --global user.name "sagnikiitb"
git config --global user.email "200040127@iitb.ac.in"
git remote add origin https://github.com/sagnikiitb/qvers.git
git push -u origin master


