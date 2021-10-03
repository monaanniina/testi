# Stash before switching branches
A software developer’s workflow is rarely linear. Users have the gall to report bugs, managers have the audacity to prioritize tickets other than the one you picked to work on, and you yourself might change your mind about what you want to do.

There you are, with three files committed for a release, and a fourth file in a changed but non-working state. (The git status command will tell you all of this if you don’t happen to remember where you were.) All of a sudden you need to work on a bug fix in a production version. You need to switch branches pronto, but you can’t. Your working directory is dirty and you have two hours of work you don’t want to lose.

Enter git stash. Voilà! Now you have all of your changes stored in a WIP (work in progress) branch, and you can switch to the production branch from your clean directory. When you’re done with that, switch back to where you were with git stash apply.
