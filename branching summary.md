TABLE OF CONTENTS
- [CLONING TIC TAC ~~TOE~~](#cloning-tic-tac-toe)
  - [ADDING THE BRANCH TO THE REMOTE REPOSITORY](#adding-the-branch-to-the-remote-repository)
  - [ORIGIN **=\>** remote repository](#origin--remote-repository)
  - [*Code formatting*](#code-formatting)
    - [highlighting code **;**](#highlighting-code-)
  - [to actually understand  the scope manenoz wipe whatever you knew about declaring costants](#to-actually-understand--the-scope-manenoz-wipe-whatever-you-knew-about-declaring-costants)
  - [PULLING AND PUSHING](#pulling-and-pushing)
  - [DELETING BRANCHES](#deleting-branches)
  - [DELETING COMMITS](#deleting-commits)
  - [RESET TO MATCH MAIN BRANCH](#reset-to-match-main-branch)
  - [**THE ULTIMATE WEAPON** _for git and github beginners_ :joy:](#the-ultimate-weapon-for-git-and-github-beginners-joy)
    - [Project based learning](#project-based-learning)
      - [Option one *advanced*](#option-one-advanced)
- [Plain images and image links](#plain-images-and-image-links)
- [Quick check list](#quick-check-list)

CTRL+SHIFT+P to open command palette in VS Code 

Type `markdown all in one` *ensure u have the markdown all in one extension* `create table of content`

[![Dynamic XML Badge](https://img.shields.io/badge/dynamic/xml)
](https://shields.io/badges/dynamic-xml-badge)

[![Static Badge](https://img.shields.io/badge/_Ben's_github_profile-check_it_out-indigo?style=flat&logo=accusoft&logoColor=#acdde7&logoSize=64x64&labelColor=steelpink)
](https://github.com/benjimwiti)
---
---
# CLONING TIC TAC ~~TOE~~
---
 https://github.com/karwanjiru/tic-tac-toe/branches
 
  git clone *https* _bentictactoe_ || this clone actually still exists under --**/directEd main/TTT/**

## ADDING THE BRANCH TO THE REMOTE REPOSITORY

  git push origin benji --this line is quite enough, it checks if such a branch exists remotely if not it creates the remote branch and tracks it

  git push -u origin HEAD;

   ***git*** **;** package with functions

   ***push*** **;** function within object

  ***-u*** **;** --set-upstream-to=;

***HEAD*** **;** current branch


  ORIGIN **=>** remote repository
  --

   1. git remote -v; 
   - check remote repositories assiciated with the clone; fetch and push references;
  - main; branch name to be tracked by the clone; 
  - tracking; literally staying by the main-branch's side; 
  1. git ls-remote --heads origin; view the already existing branches on remote repo; helpful for troubleshooting; pushing to the origin from a branch not on the repo;

*Code formatting*
--
###  highlighting code **;** 
- I'm highlighting `const`and `let` keywords uses in javascript 
- variables declared with `var` have global scope
- those declared using `let` and `const` have block scope

  to actually understand  the scope manenoz wipe whatever you knew about declaring costants
  --
  - Global scope  **;** is what u actually think it is ; a variable availabe globally in the script ==such variables are declared using var
  
  ```js
  const = "I can have either scopes defined below"
  let = "Me too!!"
  ```
  - Fuction scope **;** declared when fuction runs and crushed when function completes execution
  - Block scope **;** availabe within the curly braces 
 such  as the ones used in conditional statements and in loops

 ``` js
 for() {}
 if() {}
 ```
  ## PULLING AND PUSHING
  >git fetch origin; 
  >>loads all changes to the remote repo onto the local server;
  
  
  >git log origin/main;
  >> views a log of all commits to any branch on the remote repo;
  
  >git branch -a; 
  >>after loading the changes you can view new branches;
 
  
  >git pull origin `branch(main)`> ;
  >> get changes made to main branch;

  >git push origin `branch(benny)`
  


  ## DELETING BRANCHES
  remotely; git push origin --delete <branch>
  locally; git branch -d <branch>
  
  | Commands | description |
  | :--- | :--: |
  | git push origin HEAD| To push to the branch of the same name on the remote|
  |git branch -a| list all branches|
  |git branch --set-upstream-to=origin/benny diana-styles| diana-styles will now track remote benny branch -run git remote show origin-apparently the local ref is different from remote push ref|

[below is a toggle block--this is an MarkDown comment]: #
   <details>
   <summary> HEAD </summary>
       Think of it as a literal head which is peeping through a wall and viewing branch activity ready to snap a photo; it basically reprensents the current branch you are on and which  will make a commit Think of it as a bookmark that says, "I'm currently working on this commit."
   </details>


                           
 
                           


## DELETING COMMITS
[this is a callout i think he refers to the bulb]: #
> :bulb: do you want to revert to a working commit and delete commits above that 

1.git fetch origin;
2.git log;
.git reset --hard <hash> ; resets to specified hash/commit 
.git push origin <branch> -f ; forcefully change the remote repository;
.git pull origin <branch> ; you have two branches; this will reset a branch to allow a pull;

## RESET TO MATCH MAIN BRANCH
>git fetch origin
>
>git reset --hard origin/main

  
## **THE ULTIMATE WEAPON** _for git and github beginners_ :joy:
### Project based learning 
Objective **;** understand the reply given for the command below ;

#### Option one *advanced*
- Clone my repo if  you're feeling bold [my repo](https://github.com/Petunia675/team-collaboration "tic tac toe/2024/ group 1")

- Create your new local repo and link it to your local clone

>git remote show origin

```
* remote origin
  Fetch URL: https://github.com/Petunia675/team-collaboration.git
  Push  URL: https://github.com/Petunia675/team-collaboration.git
  HEAD branch: main
  Remote branches:
    BENJI            tracked
    Diana            tracked
    Diana-styles     tracked
    benji            tracked
    ian-branch       tracked
    ian-media        tracked
    ian-media-branch tracked
    main             tracked
    nai-branch       tracked
    purity-branch    tracked
  Local branches configured for 'git pull':
    Diana-styles merges with remote Diana-styles
    main         merges with remote main
  Local refs configured for 'git push':
    BENJI        pushes to BENJI        (local out of date)
    Diana-styles pushes to Diana-styles (local out of date)
    main         pushes to main         (local out of date)
```

[home](#cloning-tic-tac-toe)

[top]: https://www.youtube.com/watch?v=ftOBvusMHjQ

[how its made-*md files*][top]

---
---
# Plain images and image links
plain image
![Just a plain image](./img/plain-image.jpg)

*clicking on image below should take you to gratisography.com page where you can download whacky images freely.*
[![Just a plain image](./img/plain-image.jpg)](https://gratisography.com/)

 
# Quick check list
- [X] learning MARKDOWN
- [ ] selecting career path
- [ ] filling out the directEd career form