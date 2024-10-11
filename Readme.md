## Steps when Creating github repo

1. Create the project locally
2. git init
3. git add .
4. git commit -m "message"
5. create remote repository
6. copy the remote repo url (HTTPs)
7. Run git remote add origin <HTTPS URL>

- if selected the SSH and ran it:
  - git remote set-url origin \<the HTTPS url\>

8. git branch -M main
9. git push -u origin main

## to create new branch and switch to it

1. git branch \<branch name\>
2. git checkout \<branch name\>

OR

1. git checkout -b \<branch name\>

## to merge the changes in main

1. git checkout main
2. git merge \<branch name\>
3. :q to quit if you dont want to add any message

# Want to practice more use this link: https://learngitbranching.js.org/
