
HTTPS 
echo "# MEAN_SAMPLE" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fmukendi/MEAN_SAMPLE.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/fmukendi/MEAN_SAMPLE.git
git push -u origin master


SSH
echo "# MEAN_SAMPLE" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:fmukendi/MEAN_SAMPLE.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin git@github.com:fmukendi/MEAN_SAMPLE.git
git push -u origin master


//// NOTES ////

git remote set-url origin git@github.com:fmukendi/MEAN_SAMPLE.git

git remote set-url origin https://github.com/fmukendi/MEAN_SAMPLE.git

git remote show origin

git remote -v

git remote rm origin

git commit -m  'commit message'

git commit -am  'commit message'

git status