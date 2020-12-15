# MITJH

To be able to collaborate on code/text etc, I suggest each of you create a fresh
directory, (which is currently not under Git!) on you local machine.

Once that new directory is created, go to that directory ($cd MyNewDir) and run the below code to initialize git and to connect to the Github MITJH repo.

echo "# MITJH" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tolex3/MITJH.git
git push -u origin main