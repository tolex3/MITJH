# MITJH

To be able to collaborate on code/text etc, I suggest each of you create a fresh
directory, (which is currently not under Git!) on you local machine.

Once that new directory is created, go to that directory ($cd MyNewDir) and r
un the below code to initialize git and to connect to the Github MITJH repo.

Code to run to initialize local repo:

echo "# MITJH" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tolex3/MITJH.git
git push -u origin main


For collaboration, I suggest that each contributor makes changes in a local 
branch on their local machine, eg I've added tole_dev branch on my local machine by doing:

git checkout -b tole_dev
git push --set-upstream origin tole_dev

and then to push changes up to github, do: 
git push

Then, merging of changes are done on github.

The general idea is that the main branch is always kept with the lastest "tested", 
running code, while any changes/additions are done in the personal
dev-branches.



