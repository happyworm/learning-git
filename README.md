# Learning GitHub Commands and Features.

## The Command Ref.


## Tutorials.

Tutorials and cheatsheets:

* [git - the simple guide](http://rogerdudler.github.com/git-guide/)
* [git cheat sheets](http://help.github.com/git-cheat-sheets/)

## This MD Markdown stuff.

Useful links:

* [Markdown Syntax](http://daringfireball.net/projects/markdown/syntax)
* [GFM - GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/)

## Changing this log to track changes...

1. Used git add . and then git commit
2. Used this command git commit -a to remove the old README
3. pushed the text for 0 and 1 above. NB: This was commit 2nd change.
4. made this list an ordered list. NB: Called this the 4th change to line up commit msgs.
5. Commands 'git branch development' and 'git checkout development' and changed the file and then 'git commit' and push like 'git push' ie., Without a remote branch name. THIS HAD NO EFFECT. (Locally though both branches seemed to note that the readme.md file had changed.)
6. Command 'git push origin development'. CREATED REMOTE development BRANCH, BUT FILES WHERE OLD.
7. Command 'git commit -a' while still in local development branch. Then 'git push origin development'. WORKED! REMOTE DEVELOPMENT BRANCH NOW CONTAINED THE NEW FILES. Switching between local branches works. And git staus seems happy on both branches. Reviewing order and commands again above.
8. Changed file in development branch. Did a 'git add .' in the development branch. Commited changes. Required 'git commit -a' for changes to be read in. Reviewed master banch. Branches fine. Pushing to remote development branch.