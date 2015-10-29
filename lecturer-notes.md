# Lecturer notes
This file has been added to contain notes written from the Lecturer's perspective.

### No push before pull
You can't push new commits to the remore repo unless a pull of other user's new changes has been done first. However, `git status` seems to return a message that the local repo is up to date with origin/master even though no pull request has been made after a change by another user.

### Editing online
A markdown file like this one can easily be edited online, straight from GitHub. How do you then get it to the local repo on your own machine? A `git pull`should do the trick, I guess.
