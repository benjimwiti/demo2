#Demo-2

LOCAL SERVER TO GITHUB
A method she says - creating a github repository, then linking to the local repo.
create local-repo.
intialize it; git init
create github-repo.
copy the ssh link on the first page.
paste location; git remote add origin <paste>

#3rd change
added html
made a new branch; git checkout -b name of branch.
switching between branches; git checkout name.
tab fill function; also fills from any part of the word to be filled

#4th change
Merging of the branch
first check the differences; use git diff nameOfBranch.
to merge locally; git merge nameOfBranch.
merging on github; not just yet.
pushing branch to github; git push -u(--set-upstream) branchname;or git push origin adding-html.

#5th change
Pull Requests-PRs.

#6th change
its actually quite easy. 
it's a merging request; requesting the main branch to pull in the branch;

#7th change
Undoing the changes from git
git reset HEAD~1 == unstages the previous(~1) commit
git log == shows a list of all commits,
            you could then copy the hash 🤷 and run
            git reset hashValue == unstages those commits
git reset --hard hash == deletes changes that point onwards

#Updating clones
git branch -m ma main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a

https://github.com/codeSTACKr/markdown-crash-course = **STYLE UP YOUR MARKDOWN**

#deleting folders and files in github
involves tracking the main branch; delete from your local branch and then push the changes
git rm -r <folder/file name> ;

