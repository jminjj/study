pwd
mkdir
git init
git add $filename
git commit -m '$version_description'
git commit -am '$version_description'
git status
git diff
git log
git log $commit_id
git log -p
git reset $commit_id --hard
git revert $commit_id

git branch
git branch $branch_name
git checkout $branch_name

@ master branch
git merge $branch_name
git branch -D $branch_name

