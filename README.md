# new-project

Create a new GitHub repository, open a terminal and execute the following commands:
- mkdir new-project
- cd new-project
- git init
- echo "# new-project" >> README.md
- git add README.md
- git commit -m "init"
- git branch -M main
- git checkout -b development (and add some changes to the README.md file)
- git add README.md 
- git commit -m "Updated README.md"
- git checkout main 
- git merge development
- git remote add origin `<link-to-your-github-repository>`
- git push --all -u origin 
