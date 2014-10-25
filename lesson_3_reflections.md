## When would you want to use a remote repository rather than keeping all your work local?  ##

Using remote repositories can be handy because we can easily make changes and make the commit all in one go. 

## Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository? ##

If I'm making changes to an open source project and a pull request gets accepted, I might not want that pull request to be on my local repo because I may be making a change that doesn't need that pull request.

## Describe the differences between forks, clones, and branches. When would you use one instead of the other? ##

Branches are part of the same repository that can later be merged into the master version. 

Clones are used when you want to copy a repository from one system to another (e.g. from GitHub to local)

Forks are used when you want to copy someone else's repository on GitHub so you can make changes to it without disturbing anything on the owner's repo. 

## WHat is the benefit of having a copy of the last known state of the remote stored locally? ##

By having the last known state of the remote stored locally, every change up to that point is made local, which reduces the amount of conflicts that may arise when I push my repository back to the remote. 

## How would you collaborate without using Git or GitHub? What would be easier, and what would be harder? ##

You could use Google Drive, or even just email files back and forth between collaborators. 

That would be difficult because there would be no "merging," just one master copy.

## When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have? ##

If I wanted to try out an experimental feature, I would use a new branch to break the code and play around with the code and see what everything does. That way if anything does end up breaking, the master branch isn't affected. 

The benefits to making a new branch is that you can have essentially two "versions" of the same code, one being in "beta," and the other being the stable release. 

But then you can get too branch-happy and have too many branches to manage.