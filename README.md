# Easley Now-We-Know Document

## What?
- Now-We-Know Document is a Knowledge Sharing Document

## So What?
- We can store our notes for later

## Now what? (We write down some content for review)
- a repo is a regular folder that git is tracking
- creating a repo
- If you make your repo on GitHub 1st, you don't have to "git init". You only clone.
- Before you you "git add", you can run "git diff" to see what files/lines are changed.

## Questions so far about git and GitHub
what does git init do?
    - git init turns a regular ol' folder into a git repository on your computer
    - specifically, "git init" generates the .git folder in your parent folder.
    - we go "git init" once and only once if we're starting the repo on your computer
    - if you clone a repo from GitHub, you can skip the init.

when we create a repository in GitHub, what about the readme, gitignore, license?
- we can completely skip the readme, gitignore, license checkboxes
- you can click readme or gitignore template if you'd like...
- Recommend starting w/ the readme.

"git remote -v" shows the remotes you have setup. If you clone a repo from GitHub, you don't need to add the GitHub remote..


## Recap
- Big Picture: 
    - Git tracks changes to one or more lines in one or more files.
    - GitHub is a way of setting a backup
    - Git is tracking changes and when we make a copy of a git repo (we're making a copy of all the history of all the changes)
    - The git program runs on laptops, servers, computers
    - git runs on your laptop
    - git runs on GitHub's network
    - we're using GitHub as our backup..
- Mental Images
    - Git is a permanent record with a time machine 
    - Each commit is like a saved game that we can visit
- Best Practices
    - Save early, safe often
    - Commit early and commit often
    - Think of commits like "hard saves"
    - (At least) push your commits twice a day
        - one before lunch
        - one at the end of your day
    - Once you've done some work, the "adding, committing, and pushing" process can take 30 seconds - 2 minutes... 
    - If you're "commiting and pushing" 40 times a day, that's overkill.
- Advice
    - Commit after you a thing/feature/exercise
    - Commit after each curriculum exercise 
    - Commit after you finish a stage in the DS pipeline
- Other GREAT times to commit
    - As soon as you fix a gnarly freakin' bug. PUt your fix in the commit message
    - We might commit right when we discover a gnarly bug... commit message should be a description of the bug.

## Recommended Workflow
- Make a new repository every time we start a new project/module
- More on GitHub > less, b/c you're showing your portfolio!!!
- Specific Workflow:
    - https://github.com/new to make a new github repo
    - Check the README box and click "create repo"
    - Click on the green "Code" button to show the git address that looks like git@github.com:CodeupClassroom/easley-now-we-know.git
    - copy that git address
    - Open up your terminal and navigate to your projects folder (that will be the parent folder for this repo locally)
    - On your terminal run the following commands:
    - `git clone git@github.com:CodeupClassroom/easley-now-we-know.git`
    - you will now have a folder named the same thing as the repo