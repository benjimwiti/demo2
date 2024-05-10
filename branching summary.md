CLONING TIC TAC TOE; https://github.com/karwanjiru/tic-tac-toe/branches;
  git clone https bentictactoe;

ADDING THE BRANCH TO THE REMOTE REPOSITORY
  git push -u origin HEAD;
  git; package manager i think;
  push; operation or function;
  -u ; --set-upstream-to=origin/main;
  origin; git remote -v; check remote repositories assiciated with the clone; fetch and push references;
  main; branch name to be tracked by the clone; ----\
                                                ---------
                                                tracking; literally staying by the main-branch's side; incase of referencing
  git ls-remote --heads origin; view the already existing branches on remote repo; helpful for troubleshooting; pushing to the origin from a branch not on the repo;

  PULLING AND PUSHING
  git fetch origin; loads all changes to the remote repo onto the local server;
  git log origin/main; views a log of all commits to any branch on the remote repo;
  git branch -a; after loading the changes you can view new branches; 
  git pull origin main<branch> ; get changes made to main branch;
  git push origin benny<branch>
  
  
  
  
