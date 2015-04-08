cd ~/Documents/R/

#link local repo to remote repo
git remote add origin https:github.com/crmonk/datasciencecoursera.git

#create new empty local repo
git init

#clone remote github repo to local repo
git clone https://github.com/crmonk/datasciencecoursera.git

# track changes - all files added
git add .

# track changes - updates (or name changes/ deletions)
git add -u

# track changes - both added and updates
git add -A

#commits to local repo
git commit -m "this is a message describing what I changed"

#sync to github remote repo
git push

#creates branch
git checkout -b "branchname" 

#what branch are you on?
git branch

#switch branch
git checkout master

 

