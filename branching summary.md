#CLONING TIC TAC TOE; https://github.com/karwanjiru/tic-tac-toe/branches;
  git clone https bentictactoe;

#ADDING THE BRANCH TO THE REMOTE REPOSITORY
  git push origin benji
  git push -u origin HEAD;
  git; package manager i think;
  push; operation or function;
  -u ; --set-upstream-to=origin/main;
  origin; git remote -v; check remote repositories assiciated with the clone; fetch and push references;
  main; branch name to be tracked by the clone; ----\
                                                ---------
                                                tracking; literally staying by the main-branch's side; incase of referencing
  git ls-remote --heads origin; view the already existing branches on remote repo; helpful for troubleshooting; pushing to the origin from a branch not on the repo;

  #PULLING AND PUSHING
  git fetch origin; loads all changes to the remote repo onto the local server;
  git log origin/main; views a log of all commits to any branch on the remote repo;
  git branch -a; after loading the changes you can view new branches; 
  git pull origin main<branch> ; get changes made to main branch;
  git push origin benny<branch>


  #DELETING BRANCHES
  remotely; git push origin --delete <branch>
  locally; git branch -d <branch>
  
git push origin HEAD;  To push to the branch of the same name on the remote; 
research line above; HEAD -Think of it as a literal head which is peeping through a wall and viewing branch activity ready to snap
                           a photo;
                           it basically reprensents the current branch you are on and which  will make a commit
                           Think of it as a bookmark that says, "I'm currently working on this commit."
git branch -a;to list all branches
git branch --set-upstream-to origin/benny;

#DELETING COMMITS
1.git fetch origin;
2.git log;
.git reset --hard <hash> ; resets to specified hash/commit 
.git push origin <branch> -f ; forcefully change the remote repository;
.git pull origin <branch> ; you have two branches; this will reset a branch to allow a pull;


    
  
  
