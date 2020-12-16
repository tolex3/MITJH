# MITJH

#### In order to copy/paste the git setup-code lines below, click the pen/edit button to the right ####

To be able to collaborate on code/text etc, I suggest each of you create a fresh
directory, (which is currently not under Git!) on you local machine.

Once that new directory is created, go to that directory ($cd MyNewDir) and run
the below code to initialize git and to connect to the Github MITJH repo.

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

and then, after having done a local git commit, to push changes up to github, do: 
git push

Then, merging of changes are done on github.

The general idea is that the main branch is always kept with the lastest "tested", 
running code, while any changes/additions are done in the personal
dev-branches.

If this new repo gets really busy with parallel work (which I doubt :-) some discipline must be observed
in order for us not stepping on each other's toes: 

A SIMPLE team development process could be as: 

1) download main branch from Github main branch : 
1.1) On your local machine do :
1.1.1) git checkout -b <new_branch_name>
1.1.2) git pull origin main
1.2.3) do whatever development 
1.2.4) git add <any new files>
1.2.5) git commit -a -m 'commit message'
1.2.6) git push --set-upstream origin <new_branch_name>
1.2.7) git push  
1.2.8) then goto Github, and merge the changes into the main branch there.  



