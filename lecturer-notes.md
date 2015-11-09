# Lecturer notes
This file has been added to contain notes written from the Lecturer's perspective.

### No push before pull
You can't push new commits to the remore repo unless a pull of other user's new changes has been done first. However, `git status` seems to return a message that the local repo is up to date with origin/master even though no pull request has been made after a change by another user.

### Editing online
A markdown file like this one can easily be edited online, straight from GitHub. How do you then get it to the local repo on your own machine? A `git pull`should do the trick, I guess.

## Fetch vs. Pull
####Local change
The difference is apparently that `fetch`updates the local copy of origin/master but doesn't merge, so you can see the changes made by other people before incorporating them, whereas `pull`will fetch and then merge straight away so assumes you know about and are happy to have all changes pushed to that branch by other users.

####Remote change
Once this change has been made online and put origin/master ahead of my local copy, it's time to try a `fetch`to see if I can change and push without merging first. I suspect that would require making a branch.
