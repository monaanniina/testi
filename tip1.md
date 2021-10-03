# Git/GitHub tip No. 1: Clone almost anything
There are many interesting projects available from GitHub and other public Git repositories that you can clone freely to your own computer. Why would you want to do that? One reason is to learn something about coding style, practice, and tools in a language of interest, including commit log commenting style (see tip No. 4). A second reason is to learn how a given project accomplishes its goals. A third reason, should the licensing both permit you to do so and make sense for your purposes, would be to incorporate the project into your own endeavor or product. Double-check the license, by the way, so that you don’t run into compliance issues later on.

The definition of git clone from the manual page:

Clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository (visible using git branch -r), and creates and checks out an initial branch that is forked from the cloned repository’s currently active branch.

After the clone, a plain git fetch without arguments will update all the remote-tracking branches, and a git pull without arguments will in addition merge the remote master branch into the current master branch, if any.
